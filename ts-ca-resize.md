---

copyright: 
  years: 2014, 2022
lastupdated: "2022-12-01"

keywords: openshift, autoscaler

subcollection: openshift

content-type: troubleshoot

---


# Why can't I resize or rebalance my worker pool?
{: #ts-ca-resize}

When the cluster autoscaler is enabled for a worker pool, you can't [resize](/docs/openshift?topic=openshift-kubernetes-service-cli#cs_worker_pool_resize) or [rebalance](/docs/openshift?topic=openshift-kubernetes-service-cli#cs_rebalance) your worker pools. 
{: tsSymptoms}


You must edit the ConfigMap to change the worker pool minimum or maximum sizes, or disable cluster autoscaling for that worker pool. Don't use the `ibmcloud oc worker rm` [command](/docs/openshift?topic=openshift-kubernetes-service-cli#cs_worker_rm) to remove individual worker nodes from your worker pool, which can unbalance the worker pool. 
{: tsCauses}

See [Resizing or rebalancing autoscaled worker pools](/docs/openshift?topic=openshift-cluster-scaling-classic-vpc#ca_update_worker_node_pool). Further, if you don't disable the worker pools before you disable the `cluster-autoscaler` add-on, the worker pools can't be resized manually. Reinstall the cluster autoscaler, edit the ConfigMap to disable the worker pool, and try again.
{: tsResolve}

