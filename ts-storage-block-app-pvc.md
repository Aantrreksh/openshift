---

copyright: 
  years: 2014, 2022
lastupdated: "2022-11-03"

keywords: openshift

subcollection: openshift

content-type: troubleshoot

---

{{site.data.keyword.attribute-definition-list}}



# Why can't my app access or write to PVCs?
{: #block_app_failures}
{: support}

Supported infrastructure providers
:   Classic
:   VPC

When you mount a PVC to your pod, you might experience errors when accessing or writing to the PVC.
{: shortdesc}

1. List the pods in your cluster and review the status of the pod.
    ```sh
    oc get pods
    ```
    {: pre}

2. Find the root cause for why your app can't access or write to the PVC.
    ```sh
    oc describe pod <pod_name>
    ```
    {: pre}

    ```sh
    oc logs <pod_name>
    ```
    {: pre}

3. Review common errors that can occur when you mount a PVC to a pod.

| Symptom or error message | Description | Steps to resolve |
| --- | --- | --- |
| Your pod is stuck in a `ContainerCreating` or `CrashLoopBackOff` state. `MountVolume.SetUp failed for volume ... read-only.` | The {{site.data.keyword.cloud_notm}} infrastructure back end experienced network problems. To protect your data and to avoid data corruption, {{site.data.keyword.cloud_notm}} automatically disconnected the block storage server to prevent write operations on block storage instances. | See [Block storage: Block storage changes to read-only](/docs/openshift?topic=openshift-readonly_block) |
| `failed to mount the volume as "ext4", it already contains xfs. Mount error: mount failed: exit status 32`. | You want to mount an existing block storage instance that was set up with an `XFS` file system. When you created the PV and the matching PVC, you specified an `ext4` or no file system. The file system that you specify in your PV must be the same file system that is set up in your block storage instance. | See [Block storage: Mounting existing block storage to a pod fails due to the wrong file system](/docs/openshift?topic=openshift-block_filesystem) |
{: caption="Block Storage error messages" caption-side="bottom"}
{: summary="The columns are read from left to right. The first column has the symptom or error message. The second column describes the message. The third column provides steps to resolve the error."}




