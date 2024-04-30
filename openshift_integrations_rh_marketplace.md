---

copyright:
  years: 2014, 2024
lastupdated: "2024-04-29"


keywords: kubernetes, openshift

subcollection: openshift

---


{{site.data.keyword.attribute-definition-list}}




 

# Setting up the {{site.data.keyword.redhat_notm}} Marketplace
{: #rh-marketplace}

[Virtual Private Cloud]{: tag-vpc} [Classic infrastructure]{: tag-classic-inf} [{{site.data.keyword.satelliteshort}}]{: tag-satellite}

With [{{site.data.keyword.redhat_full}} Marketplace](https://swc.saas.ibm.com/en-us/redhat-marketplace){: external}, you can deploy certified {{site.data.keyword.redhat_notm}} software from an operator-based catalog to your OpenShift Container Platform clusters, including {{site.data.keyword.openshiftlong}}.
{: shortdesc}

**Required permissions**:
* The IAM **Operator** platform access role for the cluster in {{site.data.keyword.containershort_notm}}.
* The IAM **Manager** service access role in all namespaces (`cluster-admin` RBAC) for the cluster in {{site.data.keyword.containershort_notm}}.

{{site.data.keyword.redhat_notm}} Marketplace is available for clusters that run {{site.data.keyword.redhat_openshift_notm}} version 4 only.
{: note}

**Before you begin**:
*   Register for a [{{site.data.keyword.redhat_notm}} Marketplace account](https://swc.saas.ibm.com/en-us/redhat-marketplace/registration){: external}.
*   [Access your {{site.data.keyword.redhat_openshift_notm}} cluster](/docs/openshift?topic=openshift-access_cluster).
*   Make sure that the Operator Lifecycle Manager (OLM) pods in the `openshift-operator-lifecycle-manager` project and marketplace pods in the `openshift-marketplace` project are ready and running. You might have to restart a pod to return the pod to a healthy state.
    ```sh
    oc get pods -n openshift-operator-lifecycle-manager
    ```
    {: pre}

    ```sh
    oc get pods -n openshift-marketplace
    ```
    {: pre}

**To set up your cluster with {{site.data.keyword.redhat_notm}} Marketplace**:
1. Follow the [{{site.data.keyword.redhat_notm}} Marketplace instructions](https://marketplace.redhat.com/en-us/workspace/clusters/add/register){: external} to create a namespace, operator, and global pull secret for the {{site.data.keyword.redhat_notm}} Marketplace.

2. Verify that the global pull secret for the cluster is updated with the `registry.marketplace.redhat.com` secret.
    ```sh
    oc get secret pull-secret -n openshift-config --output="jsonpath={.data.\.dockerconfigjson}" | base64 --decode | grep "marketplace" -A4
    ```
    {: pre}

3. To pick up the global configuration changes, reload all the worker nodes in your cluster.
    1. Note the **ID** of the worker nodes in your cluster.
        ```sh
        ibmcloud oc worker ls -c <cluster_name_or_ID>
        ```
        {: pre}

    2. Reload each classic worker node, or replace each VPC worker node. You can reload or replace multiple worker nodes by including multiple `-w` options, but make sure to leave enough worker nodes running at the same time for your apps to avoid an outage because they are reloaded concurrently.

        **Classic**: Reload worker nodes.
        ```sh
        ibmcloud oc worker reload -c <cluster_name_or_ID> -w <workerID_1> -w <workerID_2>
        ```
        {: pre}

        **VPC**: Replace worker nodes.
        ```sh
        ibmcloud oc worker replace -c <cluster_name_or_ID> -w <workerID_1> -w <workerID_2>
        ```
        {: pre}

4. After your worker nodes are reloaded, verify that your cluster is listed in your [{{site.data.keyword.redhat_notm}} Marketplace workspace](https://marketplace.redhat.com/en-us/workspace/clusters){: external}.

Now, you can install and manage software from {{site.data.keyword.redhat_notm}} Marketplace in your cluster. For more information, see the [{{site.data.keyword.redhat_notm}} Marketplace documentation](https://swc.saas.ibm.com/en-us/redhat-marketplace/documentation/){: external}.





