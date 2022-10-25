---

copyright: 
  years: 2014, 2022
lastupdated: "2022-10-25"

keywords: openshift

subcollection: openshift


---

{{site.data.keyword.attribute-definition-list}}



# Restricting network traffic to edge worker nodes on classic infrastructure
{: #edge}

Edge worker nodes can improve the security of your {{site.data.keyword.openshiftlong}} cluster by allowing fewer worker nodes by isolating the networking workload.
{: shortdesc}

When you mark these worker nodes for networking only, other workloads can't consume the CPU or memory of the worker node and interfere with networking.

If you want to restrict network traffic to edge worker nodes in a multizone cluster, you must have at least two edge worker nodes per zone for high availability of load balancer or Ingress pods. Create an edge node worker pool that spans all the zones in your cluster, with at least two worker nodes per zone.
{: tip}

## Isolating networking workloads to edge nodes
{: #edge_nodes}

Add the `dedicated=edge` label to worker nodes on each public or private VLAN in your cluster.

The labels ensure that network load balancer (NLB) pods are deployed to those worker nodes only. For NLBs, ensure that two or more worker nodes per zone are edge nodes. Note that router pods for Ingress controllers and routes are not deployed to edge nodes and remain on non-edge worker nodes.


Before you begin

* Ensure that you have the following [{{site.data.keyword.cloud_notm}} IAM roles](/docs/openshift?topic=openshift-users#checking-perms):
    * Any platform access role for the cluster
    * **Writer** or **Manager** service access role for all namespaces
* [Access your {{site.data.keyword.redhat_openshift_notm}} cluster](/docs/openshift?topic=openshift-access_cluster).

To create an edge node worker pool,

1. [Create a worker pool](/docs/openshift?topic=openshift-add_workers#add_pool) that spans all zones in your cluster and has at least two workers per zone if you use NLBs or for version 3.11 clusters, 3 or more workers per zone if you use ALBs. In the `ibmcloud oc worker-pool create` command, include the `--label dedicated=edge` flag to label all worker nodes in the pool. All worker nodes in this pool, including any worker nodes that you add later, are labeled as edge nodes.

    If you want to use an existing worker pool, the pool must span all zones in your cluster and have at least two worker nodes per zone. You can label the worker pool with `dedicated=edge` by using the [`ibmcloud oc worker-pool label set` command](/docs/openshift?topic=openshift-kubernetes-service-cli#cs_worker_pool_label_set).
    {: tip}

    To ensure that ALB pods are always scheduled to edge worker nodes if they are present and not scheduled to non-edge worker nodes, you must create or use an existing worker pool that has at least three edge worker nodes per zone. During the update of an ALB pod, a new ALB pod rolls out to replace an existing ALB pod. However, ALB pods have anti-affinity rules that don't permit a pod to deploy to a worker node where another ALB pod already exists. If you have only two edge nodes per zone, both ALB pod replicas already exist on those edge nodes, so the new ALB pod must be scheduled on a non-edge worker node. When three edge nodes are present in a zone, the new ALB pod can be scheduled to the third edge node. Then, the old ALB pod is removed.
    {: important}

2. Verify that the worker pool and worker nodes have the `dedicated=edge` label.
    * To check the worker pool
        ```sh
        ibmcloud oc worker-pool get --cluster <cluster_name_or_ID> --worker-pool <worker_pool_name_or_ID>
        ```
        {: pre}

    * To check individual worker nodes, review the **Labels** field of the output of the following command.
        ```sh
        oc describe node <worker_node_private_IP>
        ```
        {: pre}

3. Retrieve all existing NLBs in the cluster.
    ```sh
    oc get services --all-namespaces | grep LoadBalancer
    ```
    {: pre}

    In the output, note the **Namespace** and **Name** of each load balancer service. For example, the following output shows one public NLB in the `default` namespace.
    ```sh
    NAMESPACE     NAME                                             TYPE           CLUSTER-IP       EXTERNAL-IP     PORT(S)                                     AGE
    default       webserver-lb                                     LoadBalancer   172.21.190.18    169.46.17.2     80:30597/TCP                                11m
    ```
    {: screen}

4. Using the output from the previous step, run the following command for each NLB. This command redeploys the NLB to an edge worker node. 

    ```sh
    oc get service -n <namespace> <service_name> -o yaml | oc apply -f -
    ```
    {: pre}

    Example output

    ```sh
    service "webserver-lb" configured
    ```
    {: screen}

5. To verify that networking workloads are restricted to edge nodes, confirm that NLB are scheduled onto the edge nodes and are not scheduled onto non-edge nodes.

    * NLB pods
        1. Confirm that the NLB pods are deployed to edge nodes. Search for the external IP address of the load balancer service that is listed in the output of step 3. Replace the periods (`.`) with hyphens (`-`). Example for the `webserver-lb` NLB that has an external IP address of `169.46.17.2`:
            ```sh
            oc describe nodes -l dedicated=edge | grep "169-46-17-2"
            ```
            {: pre}

            Example output
            ```sh
            ibm-system                 ibm-cloud-provider-ip-169-46-17-2-76fcb4965d-wz6dg                 5m (0%)       0 (0%)      10Mi (0%)        0 (0%)
            ibm-system                 ibm-cloud-provider-ip-169-46-17-2-76fcb4965d-2z64r                 5m (0%)       0 (0%)      10Mi (0%)        0 (0%)
            ```
            {: screen}

        2. Confirm that no NLB pods are deployed to non-edge nodes. Example for the `webserver-lb` NLB that has an external IP address of `169.46.17.2`:
            ```sh
            oc describe nodes -l dedicated!=edge | grep "169-46-17-2"
            ```
            {: pre}

            * If the NLB pods are correctly deployed to edge nodes, no NLB pods are returned. Your NLBs are successfully rescheduled onto only edge worker nodes.
            * If NLB pods are returned, continue to the next step.


6. If NLB pods are still deployed to non-edge nodes, you can delete the pods so that they redeploy to edge nodes. **Important**: Delete only one pod at a time, and verify that the pod is rescheduled onto an edge node before you delete other pods.
    1. Delete a pod. Example for if one of the `webserver-lb` NLB pods did not schedule to an edge node:
        ```sh
        oc delete pod ibm-cloud-provider-ip-169-46-17-2-76fcb4965d-wz6dg
        ```
        {: pre}

    2. Verify that the pod is rescheduled onto an edge worker node. Rescheduling is automatic, but might take a few minutes. Example for the `webserver-lb` NLB that has an external IP address of `169.46.17.2`:
        ```sh
        oc describe nodes -l dedicated=edge | grep "169-46-17-2"
        ```
        {: pre}

        Example output

        ```sh
        ibm-system                 ibm-cloud-provider-ip-169-46-17-2-76fcb4965d-wz6dg                 5m (0%)       0 (0%)      10Mi (0%)        0 (0%)
        ibm-system                 ibm-cloud-provider-ip-169-46-17-2-76fcb4965d-2z64r                 5m (0%)       0 (0%)      10Mi (0%)        0 (0%)
        ```
        {: screen}

7. Retrieve all existing ALBs in the cluster. Review the command output. For each ALB that has a **Status** of **enabled**, note the **ALB ID** and **Build**.

    ```sh
    ibmcloud oc ingress alb ls --cluster <cluster_name_or_ID>
    ```
    {: pre}

    Example output

    ```sh
    ALB ID                                Enabled   State     Type      Load Balancer Hostname                      Zone         Build                                  Status
    private-crc81nk5l10gfhdql4i3qg-alb1   true      enabled   private   e9dd35e6-us-south.lb.test.appdomain.cloud   us-south-3   ingress:1.1.1_1949_iks/ingress-auth:   enabled
    public-crc81nk5l10gfhdql4i3qg-alb1    true      enabled   public    38daf55c-us-south.lb.test.appdomain.cloud   us-south-3   ingress:1.1.1_1949_iks/ingress-auth:   healthy
    ```
    {: screen}

8. Using the output from the previous step, run the `ibmcloud oc ingress alb update` command for each enabled ALB. This command redeploys the ALB to an edge worker node. 

    When you run this command to redeploy the ALB to an edge worker node, the ALB also updates to the latest version. If you do not want to update the ALB to the latest version, include the `--version` flag and specify the version listed under **Build** in the output from the previous step. 
    {: tip}

    ```sh
    ibmcloud oc ingress alb update -c <cluster_name_or_ID> --alb <ALB_ID> [--version <build_version>] 
    ```
    {: pre}

    Example output

    ```sh
    Updating ALB pods for private-crc81nk5l10gfhdql4i3qg-alb1 to version '1.1.1_1949_iks' in cluster c81nk5l10gfhdql4i3qg...
    OK
    ```
    {: screen}

9. Verify that ALB pods are scheduled onto edge nodes and are not scheduled onto compute nodes.
    1. Confirm that all ALB pods are deployed to edge nodes. Each public and private ALB that is enabled in your cluster has two pods.

        ```sh
        oc describe nodes -l dedicated=edge | grep alb
        ```
        {: pre}

        Example output

        ```sh
        kube-system                private-crdf253b6025d64944ab99ed63bb4567b6-alb1-d5dd478db-27pv4    0 (0%)        0 (0%)      0 (0%)           0 (0%)
        kube-system                private-crdf253b6025d64944ab99ed63bb4567b6-alb1-d5dd478db-7p9q6    0 (0%)        0 (0%)      0 (0%)           0 (0%)
        kube-system                public-crdf253b6025d64944ab99ed63bb4567b6-alb1-5ff8cdff89-s77z6    0 (0%)        0 (0%)      0 (0%)           0 (0%)
        kube-system                public-crdf253b6025d64944ab99ed63bb4567b6-alb1-5ff8cdff89-kvs9f    0 (0%)        0 (0%)      0 (0%)           0 (0%)
        ```
        {: screen}

    2. Confirm that no ALB pods are deployed to non-edge nodes.

        ```sh
        oc describe nodes -l dedicated!=edge | grep alb
        ```
        {: pre}

        If the ALB pods are correctly deployed to edge nodes, no ALB pods are returned. Your ALBs are successfully rescheduled onto only edge worker nodes.



You labeled worker nodes in a worker pool with `dedicated=edge` and redeployed all the existing ALBs and NLBs to the edge nodes. All subsequent ALBs and NLBs that are added to the cluster are also deployed to an edge node in your edge worker pool. Next, prevent other [workloads from running on edge worker nodes](#edge_workloads) and [block inbound traffic to NodePorts on worker nodes](/docs/openshift?topic=openshift-network_policies#block_ingress).


## Preventing app workloads from running on edge worker nodes
{: #edge_workloads}

A benefit of edge worker nodes is that they can be specified to run networking services only.
{: shortdesc}

Using the `dedicated=edge` toleration means that all network load balancer (NLB) and, in version 3.11 clusters, Ingress application load balancer (ALB) services are deployed to the labeled worker nodes only. However, to prevent other workloads from running on edge worker nodes and consuming worker node resources, you must use [Kubernetes taints](https://kubernetes.io/docs/concepts/scheduling-eviction/taint-and-toleration/){: external}.


Before you begin
- Ensure you that have the [**Manager** {{site.data.keyword.cloud_notm}} IAM service access role for all namespaces](/docs/openshift?topic=openshift-users#checking-perms).
- [Access your {{site.data.keyword.redhat_openshift_notm}} cluster](/docs/openshift?topic=openshift-access_cluster).

Complete the following steps to prevent other workloads from running on edge worker nodes.

If you want to allow the Sysdig agent to run on your edge nodes, see [Deploying the Sysdig agent to edge worker nodes](#sysdig-edge).
{: tip}

1. Apply a taint to the worker nodes with the `dedicated=edge` label. The taint prevents pods from running on the worker node and removes pods that don't have the `dedicated=edge` label from the worker node. The pods that are removed are redeployed to other worker nodes with capacity.

    To apply a taint to all existing and future worker nodes in a worker pool:
    ```sh
    ibmcloud oc worker-pool taint set -c <cluster_name_or_ID> --worker-pool <worker_pool_name_or_ID> --taint dedicated=edge:NoExecute
    ```
    {: pre}

    To apply a taint to individual worker nodes:
    ```sh
    oc adm taint node -l dedicated=edge dedicated=edge:NoExecute
    ```
    {: pre}

    Now, only pods with the `dedicated=edge` toleration are deployed to your edge worker nodes.

2. Verify that your edge nodes are tainted.
    ```sh
    oc describe nodes -l dedicated=edge | egrep "Taints|Hostname"
    ```
    {: pre}

    Example output

    ```sh
    Taints:             dedicated=edge:NoExecute
        Hostname:    10.176.48.83
      Taints:             dedicated=edge:NoExecute
    Hostname:    10.184.58.7
    ```
    {: screen}

3. If you choose to [enable source IP preservation for an NLB 1.0 service](/docs/openshift?topic=openshift-loadbalancer#lb_source_ip), ensure that app pods are scheduled onto the edge worker nodes by [adding edge node affinity to app pods](/docs/openshift?topic=openshift-loadbalancer#lb_edge_nodes). App pods must be scheduled onto edge nodes to receive incoming requests.

4. Optional: You can remove a taint from the worker nodes.

    To remove all taints from all worker nodes in a worker pool,
    ```sh
    ibmcloud oc worker-pool taint rm -c <cluster_name_or_ID> --worker-pool <worker_pool_name_or_ID>
    ```
    {: pre}

    To remove individual taints from individual worker nodes,
    ```sh
    oc adm taint node <node_name> dedicated:NoSchedule- dedicated:NoExecute-
    ```
    {: pre}
    
## Deploying the Sysdig agent on edge worker nodes
{: #sysdig-edge}

To allow the Sysdig agent pods to be deployed to your edge worker nodes, run the following `kubectl patch` command to update the `sysdig-agent` DaemonSet. This command applies the `NoExecute` toleration to the DaemonSet to ensure that the agent pods don't get evicted from the node.

```sh
kubectl patch ds sysdig-agent -n ibm-observe --type merge --type='json' -p='[{"op": "add", "path": "/spec/template/spec/tolerations/-", "value": {"operator": Exists, "effect": NoExecute}}]'
```
{: pre}

If you used pod labels such as `dedicated=edge`, you can also apply this label to any pods that you want to allow on your edge nodes.
{: tip}


