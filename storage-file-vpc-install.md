---

copyright: 
  years: 2022, 2023
lastupdated: "2023-03-07"

keywords: openshift

subcollection: openshift


---

{{site.data.keyword.attribute-definition-list}}



# Enabling the {{site.data.keyword.filestorage_vpc_full_notm}} add-on
{: #storage-file-vpc-install}

[Virtual Private Cloud]{: tag-vpc}

{{site.data.keyword.filestorage_vpc_full_notm}} is persistent, fast, and flexible network-attached, NFS-based {{site.data.keyword.filestorage_vpc_short}} that you can add to your apps by using Kubernetes persistent volumes (PVs). You can choose between predefined storage tiers with GB sizes and IOPS that meet the requirements of your workloads. To find out if {{site.data.keyword.filestorage_vpc_short}} is the correct storage option for you, see [Choosing a storage solution](/docs/openshift?topic=openshift-storage-plan). For pricing information, see [Pricing](https://www.ibm.com/cloud/file-storage/pricing){: external}.
{: shortdesc}

{{site.data.keyword.filestorage_vpc_short}} is available for allowlisted accounts in the Washington D.C., Dallas, Frankfurt, London, Sydney, Sao Paulo, and Tokyo regions. Contact your IBM Sales representative if you are interested in getting access.
{: preview}

{{site.data.keyword.filestorage_vpc_short}} is available in Beta. Do not use this add-on for production workloads.
{: beta} 


## Prerequisites
{: #prereqs-store-file-vpc}

1. Update the `container-service` plug-in to the most recent version. You can update the plug-in by running the **`ibmcloud plugin update container-service`** command. 


1. Get a list of the add-on versions and decide which version to install for your cluster version.
    ```sh
    ibmcloud oc cluster addon versions --addon vpc-file-csi-driver
    ```
    {: pre}

    Example output
    ```sh
    OK
    Name                  Version         Supported Kubernetes Range   Supported Openshift Range   
    vpc-file-csi-driver   1.0 (default)   >=1.21.0                     >=4.7.0 
    ```
    {: pre}

1. Enable the add-on. The add-on might take a few minutes to become ready.
    ```sh
    ibmcloud oc cluster addon enable vpc-file-csi-driver --version VERSION --cluster CLUSTERID
    ```
    {: pre}


1. Verify that the add-on is enabled.
    ```sh
    ibmcloud oc cluster addon ls --cluster <cluster_name_or_ID>
    ```
    {: pre}

    Example output
    ```sh
    Name                   Version   Health State   Health Status   
    vpc-file-csi-driver    1.0.0     normal         Addon Ready
    ```
    {: pre}
