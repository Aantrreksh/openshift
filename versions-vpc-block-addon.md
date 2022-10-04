---

copyright: 
  years: 2014, 2022
lastupdated: "2022-10-03"

keywords: block, add-on, changelog

subcollection: openshift


---

{{site.data.keyword.attribute-definition-list}}



# {{site.data.keyword.block_storage_is_short}} add-on changelog
{: #vpc_bs_changelog}

View information for patch updates to the {{site.data.keyword.block_storage_is_short}} add-on in your {{site.data.keyword.openshiftlong_notm}} clusters.
{: shortdesc}

Patch updates
:   Patch updates are delivered automatically by IBM and don't contain any feature updates or changes in the supported add-on and cluster versions.

Release updates
:   Release updates contain new features for the {{site.data.keyword.block_storage_is_short}} or changes in the supported add-on or cluster versions. You must manually apply release updates to your {{site.data.keyword.block_storage_is_short}} add-on. To update your {{site.data.keyword.block_storage_is_short}} add-on, see [Updating the {{site.data.keyword.block_storage_is_short}} add-on](/docs/containers?topic=containers-vpc-block#vpc-addon-update).


To view a list of add-ons and the supported cluster versions in the CLI, run the following command.
```sh
ibmcloud oc cluster addon versions --addon vpc-block-csi-driver
```
{: pre}

To view a list of add-ons and the supported cluster versions, see the [Supported cluster add-ons table](/docs/containers?topic=containers-supported-cluster-addon-versions).





## Version 5.0
{: #050_is_block}

Version 5.0.0 is available in for allowlisted accounts.
{: preview}



### Change log for version 5.0.4-beta_1566, released 14 July 2022
{: #5.0.4-beta_1556_is_block_relnote}

- Updates the storage-secret-sidecar image to `v1.1.12`.
- Updates Golang to version `1.18.3`.
- Updates UBI image to version `8.6-854`.
- Pushes community images to `icr.io`.
- Fixes a bug for `user_tags` and `service_tags` data types.
- Changes the `volumesnapshotclass` name.
- Fixes for format errors and mount failures.
- Resolves the following CVEs:
    - [CVE-2022-29824](https://nvd.nist.gov/vuln/detail/CVE-2022-29824){: external}
    - [CVE-2021-40528](https://nvd.nist.gov/vuln/detail/CVE-2021-40528){: external}
    - [CVE-2022-22576](https://nvd.nist.gov/vuln/detail/CVE-2022-22576){: external}
    - [CVE-2022-27774](https://nvd.nist.gov/vuln/detail/CVE-2022-27774){: external}
    - [CVE-2022-27776](https://nvd.nist.gov/vuln/detail/CVE-2022-27776){: external}
    - [CVE-2022-27782](https://nvd.nist.gov/vuln/detail/CVE-2022-27782){: external}
    - [CVE-2022-25313](https://nvd.nist.gov/vuln/detail/CVE-2022-25313){: external}
    - [CVE-2022-25314](https://nvd.nist.gov/vuln/detail/CVE-2022-25314){: external}

### Change log for version 5.0.1-beta_1411, released 15 June 2022
{: #5.0.1-beta_1411_is_block_relnote}

Fixes a bug where the resource group wasn't included in the snapshot creation request payload.


### Change log for version 5.0.0-beta_1125, released 10 June 2022
{: #5.0.0-beta_1125_is_block_relnote}

Adds snapshot support.




## Version 4.4
{: #044_is_block}



### Change log for version 4.4.11_1614, released 23 September 2022
{: #4.4.11_1614_is_block_relnote}

- Updates the `storage-secret-sidecar` image to `v1.2.8`.
- Updates the golang version to `1.18.6`.
- Resolves the following CVEs: [CVE-2022-27664](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27664){: external}, [CVE-2022-32190](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-32190){: external}.



### Change log for version 4.4.10_1578, released 13 September 2022
{: #4.4.10_1578_is_block_relnote}

- Updates the `storage-secret-sidecar` image to `v1.2.7`
- Resolves the following CVEs: [CVE-2022-32206](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-32206){: external}, [CVE-2022-32208](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-32208){: external}, [CVE-2022-2526](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2526){: external}.


### Change log for version 4.4.9_1566, released 25 August 2022
{: #4.4.9_1566_is_block_relnote}

- Updates Golang to version `1.18.5`
- Updates the `storage-secret-sidecar` image to `v1.2.6`
- Resolves the following CVEs: [CVE-2022-1586](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1586){: external}, [CVE-2022-2068](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2068){: external}, [CVE-2022-1292](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1292){: external}, [CVE-2022-2097](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2097){: external}. 

### Change log for version 4.4.8_1550, released 18 July 2022
{: #4.4.8_1550_is_block_relnote}

- Updates the `storage-secret-sidecar` image to `v1.2.5`
- Updates Golang to version `1.18.3`
- Updates UBI image to version `8.6-854`
- Fixes an issue where volume mounting on node fails with already mounted error.
- Resolves the following CVEs: [CVE-2022-29824](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-29824){: external}, [CVE-2021-40528](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-40528){: external}, [CVE-2022-22576](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-22576){: external}, [CVE-2022-27774](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27774){: external}, [CVE-2022-27776](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27776){: external}, [CVE-2022-27782](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27782){: external}, [CVE-2022-25313](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-25313){: external}, [CVE-2022-25314](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-25314){: external}. 


### Change log for version 4.4.6_1446, released 24 June 2022
{: #4.4.6_1446_is_block_relnote}

- Includes an update where volume creation or expansion isn't retried if the provided volume capacity is not supported by volume profile.
- Updates the `storage-secret-sidecar` image to `v1.2.4`
- Resolves [CVE-2022-1271](https://cve.mitre.org/cgi-bin/cvename.cgi?name=2022-1271){: external}
- Adds a security fix related with image signing.



### Change log for version 4.4.5_1371, released 13 June 2022
{: #445_1371_is_block_relnote}

- Adds support for IAM trusted profiles.
- Adds IAM token caching in memory for up to 40 minutes which reduces the number of calls to IAM and improves driver performance.
- Updates the `storage-secret-sidecar` image to `v1.2.3`.
- Fixes a volume expansion error handling issue.



## Version 4.3
{: #043_is_block}


### Change log for version 4.3.7_1613, released 22 September 2022
{: #4.3.7_1613_is_block_relnote}

- Updates the `storage-secret-sidecar` image to `v1.1.15`.
- Updates the golang version to `1.18.6`.
- Resolves the following CVEs: [CVE-2022-27664](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27664){: external} and [CVE-2022-32190](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-32190){: external}.


### Change log for version 4.3.6_1579, released 12 September 2022
{: #436_1579_is_block_relnote}

- Updates the `storage-secret-sidecar` image to `v1.1.14`
- Resolves the following CVEs: [CVE-2022-32206](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-32206){: external}, [CVE-2022-32208](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-32208){: external}, [CVE-2022-2526](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2526){: external}.

### Change log for version 4.3.5_1563, released 24 August 2022
{: #435_1563_is_block_relnote}

- Updates Golang to version `1.18.5`
- Updates the `storage-secret-sidecar` image to `v1.1.13`
- Resolves the following CVEs: [CVE-2022-1586](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1586){: external}, [CVE-2022-2068](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2068){: external}, [CVE-2022-1292](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1292){: external}, [CVE-2022-2097](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-2097){: external}. 


### Change log for version 4.3.4_1551, released 18 July 2022
{: #434_1551_is_block_relnote}


- Updates the `storage-secret-sidecar` image to `v1.1.12`
- Updates Golang to version `1.18.3`
- Updates UBI image to version `8.6-854`
- Improves secret watcher in case of secret update.
- Fixes an issue where volume mounting on node fails with already mounted error.
- Resolves the following CVEs: [CVE-2022-29824](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-29824){: external}, [CVE-2021-40528](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-40528){: external}, [CVE-2022-22576](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-22576){: external}, [CVE-2022-27774](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27774){: external}, [CVE-2022-27776](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27776){: external}, [CVE-2022-27782](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-27782){: external}, [CVE-2022-25313](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-25313){: external}, [CVE-2022-25314](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-25314){: external}.




### Change log for version 4.3.2_1441, released 17 June 2022
{: #432_1441_is_block_relnote}

- Added security fix related to image signing
- Updates the `storage-secret-sidecar` image to `v1.1.11`
- Resolves [CVE-2022-1271](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1271){: external}

### Change log for version 4.3.0_1163, released 25 May 2022
{: #430_1163_is_block_relnote}

- Resolves the following CVEs: [CVE-2021-3634](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3634){: external}, [CVE-2021-3737](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3737){: external}, [CVE-2021-4189]https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-4189){: external}.
- Updates the `storage-secret-sidecar` image to `v1.1.10`
- Fixes Volume provisioning failure when in StorageClass Region is provided without zone info
- Fixes an issue where volume creation fails if only `failure-domain.beta.kubernetes.io/zone` is given in `allowedTopologies`
- `Region` support is now *DEPRECATED* in the storage class. Providing "region" detail in storage classes is deprecated in this release, this will not cause any issues with either existing PVC or new PVC. For now the default behaviour is to get the region detail from the node label only which is now mandatory for all cases.

## Version 4.2
{: #042_is_block}


### Change log for version 4.2.6_1161, released 12 May 2022
{: #426_1161_is_block_relnote}

- Updates armada-storage-secret to `v1.1.10`
- Resolves the following CVEs: [CVE-2021-3634](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3634){: external},[CVE-2021-3737](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3737){: external},[CVE-2021-4189](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-4189){: external}.


### Change log for version 4.2.5_1106, released 12 May 2022
{: #425_1106_is_block_relnote}

- Updates armada-storage-secret to `v1.1.9`
- Updates the UBI version to `8.5-243.1651231653` 
- Resolves [CVE-2022-1271](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1271){: external}.


### Change log for version 4.2.3_983, released 11 April 2022
{: #423_983_is_block_relnote}

- Updates armada-storage-secret to `v1.1.8`
- Resolves [CVE-2022-0778](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-0778){: external}.


### Change log for version 4.2.2_900, released 24 March 2022
{: #422_900_is_block_relnote}

- Updates armada-storage-secret to `v1.1.7`
- Resolves [CVE-2022-24921](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-24921){: external}.
- Update Golang to `1.16.15`


### Change log for version 4.2.1_895, released 17 March 2022
{: #421_895_is_block_relnote}

- Resolves [CVE-2022-24407](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-24407){: external}.
- Updates the `armada-storage-secret` to v1.1.6.



### Change log for version 4.2.0_890, released 28 February 2022
{: #420_890_is_block_relnote}

Updates in this version:
- Volume expansion support is now generally available.
- Removes unused variables `sizeRange` and `sizeIOPSRange` from storage classes.
- Makes `ibmc-vpc-block-10iops-tier` the default storage class via the new `addon-vpc-block-csi-driver-configmap` in the `kube-system` namespace.
- Resolves the following CVEs: [CVE-2021-3712](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3712){: external} and [CVE-2021-3521](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3521){: external}, [CVE-2022-23772](https://nvd.nist.gov/vuln/detail/CVE-2022-23772){: external}, [CVE-2022-23773](https://nvd.nist.gov/vuln/detail/CVE-2022-23773){: external}, and [CVE-2022-23806](https://nvd.nist.gov/vuln/detail/CVE-2022-23806){: external}.
- Updates Golang to version 1.16.14.
- All the storage classes that are installed with the add-on now have `allowVolumeExpansion=true`.

After updating to version 4.2, you must complete the following steps.
{: important}

* [Delete and recreate](/docs/containers?topic=containers-vpc-block#vpc-addon-update) any custom storage classes that are using the `sizeRange` or `iopsRange` parameters.
* If you use a default storage class other than `ibmc-vpc-block-10iops-tier`, you must change the `isStorageClassDefault` setting to `false` in the `addon-vpc-block-csi-driver-configmap` configmap in the `kube-system` namespace. For more information, see [Changing the default storage class](/docs/openshift?topic=openshift-vpc-block#vpc-block-default-edit).
    



## Version 4.1
{: #041_is_block}

Review the changes in version `4.1` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

### Change log for version 4.1.3_846, released 14 February 2022
{: #413_846_is_block_relnote}

Review the changes in version `4.1.3_846` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}    

- Resolves the following CVEs. 
    - [CVE-2021-3538](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3538){: external}
    - [CVE-2020-26160](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-26160){: external}

    

### Change log for version 4.1.2_834, released 27 January 2022
{: #412_834_is_block_relnote}

- Fixes an issue where the persistent volume watcher was unable to handle non-{{site.data.keyword.cloud_notm}} VPC CSI driver PV updates which caused the controller pod to crash.



### Change log for version 4.1.1_827, released 20 January 2022
{: #0411837_is_block_relnote}

Review the changes in version `4.1.1_827` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdisc}

- Resolves the following CVEs.
    - [CVE-2021-44716](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-44716){: external}
    - [CVE-2021-44717](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-44717){: external}
- Updates Golang to version `1.16.13`.
- Updates the UBI image to version `8.5-218`.



### Change log for version 4.1.0_807, released 06 January 2022
{: #41_is_block_relnote}

Review the changes in version `4.1.0_807` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: v4.1
- Resolves [CVE-2021-3712](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-3712){: external}.
- Updates the storage-secret-sidecar image to version 1.1.4.
- Upgrades Kubernetes packages to version 1.21.
- Updates how api-key rotation is handled so that restarting the driver is no longer required.

## Version 4.0
{: #0400_is_block}

Review the changes in version `4.0` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}


### Change log for version 4.0.3_793, released 22 November 2021
{: #403793_is_block_relnote}

Review the changes in version `4.0.3_793` of the {{site.data.keyword.block_storage_is_short}} add-on. 
{: shortdesc}

- Image tags: v4.0.3
- Image tags: v4.0.2
- Resolves the following CVEs.
    - [CVE-2021-41772](https://nvd.nist.gov/vuln/detail/CVE-2021-41772){: external}
    - [CVE-2021-41771](https://nvd.nist.gov/vuln/detail/CVE-2021-41771){: external}
    - [CVE-2021-22946](https://nvd.nist.gov/vuln/detail/CVE-2021-22946){: external}
    - [CVE-2021-22947](https://nvd.nist.gov/vuln/detail/CVE-2021-22947){: external}
    - [CVE-2021-33928](https://nvd.nist.gov/vuln/detail/CVE-2021-33928){: external}
    - [CVE-2021-33929](https://nvd.nist.gov/vuln/detail/CVE-2021-33929){: external}
    - [CVE-2021-33930](https://nvd.nist.gov/vuln/detail/CVE-2021-33930){: external}
    - [CVE-2021-33938](https://nvd.nist.gov/vuln/detail/CVE-2021-33938){: external}
    - [CVE-2021-3733](https://nvd.nist.gov/vuln/detail/CVE-2021-3733){: external}
- Updates the `storage-secret-sidecar` image to `v1.1.3`.
- Updates the default class policy from `Reconcile` to `EnsureExists` for  the `ibmc-vpc-block-10iops-tier` storage class.
- Updates Golang to version `1.16.10`.
- Updates the UBI image to version `8.4-205`.
- Increases the timeout interval for receiving API keys.


### Change log for version 4.0.1_780, released 06 October 2021
{: #0400780_is_block_relnote}

Review the changes in version `4.0.1_780` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v4.0.1`
- Resolves the following CVEs.
    - [CVE-2021-22922](https://nvd.nist.gov/vuln/detail/CVE-2021-22922){: external}
    - [CVE-2021-22923](https://nvd.nist.gov/vuln/detail/CVE-2021-22923){: external}
    - [CVE-2021-22924](https://nvd.nist.gov/vuln/detail/CVE-2021-22924){: external}
    - [CVE-2021-36222](https://nvd.nist.gov/vuln/detail/CVE-2021-36222){: external}
    - [CVE-2021-37750](https://nvd.nist.gov/vuln/detail/CVE-2021-37750){: external}
- Updates the `storage-secret-sidecar` image to `v1.1.2`.
- Improves error messaging if `iks_token_exchange_endpoint_private_url` is invalid or unreachable.
- Adds [new storage classes for OpenShift Data Foundation](/docs/containers?topic=containers-vpc-block#vpc-block-reference).
- Updates to improve the volume attach/detach performance by avoiding unnecessary retries.
- Fixes an issue where mounting failed with `already mounted` error.
- Improves logging when the device path for a volume is not present on worker node.
- Adds the image label `compliance.owner="ibm-armada-storage"`. 



### Change log for version 4.0.0_769, released 16 September 2021
{: #0400769_is_block_relnote}

Review the changes in version `4.0.0_769` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v4.0.0`
- Resolves the following CVEs:
    - [CVE-2021-27218](https://nvd.nist.gov/vuln/detail/CVE-2021-27218){: external}  
    - [CVE-2021-3520](https://nvd.nist.gov/vuln/detail/CVE-2021-3520){: external}  
    - [CVE-2021-20271](https://nvd.nist.gov/vuln/detail/CVE-2021-20271){: external}  
    - [CVE-2021-3516](https://nvd.nist.gov/vuln/detail/CVE-2021-3516){: external}  
    - [CVE-2021-3517](https://nvd.nist.gov/vuln/detail/CVE-2021-3517){: external}  
    - [CVE-2021-3518](https://nvd.nist.gov/vuln/detail/CVE-2021-3518){: external}  
    - [CVE-2021-3537](https://nvd.nist.gov/vuln/detail/CVE-2021-3537){: external}  
    - [CVE-2021-3541](https://nvd.nist.gov/vuln/detail/CVE-2021-3541){: external}  
    - [CVE-2021-33910](https://nvd.nist.gov/vuln/detail/CVE-2021-33910){: external}  
- Updates the `storage-secret-sidecar` image to `v1.1.0`.



### Change log for version 4.0, released 1 September 2021
{: #0400_is_block_relnote}

Review the changes in version `4.0.0_764` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v4.0.0`
- Resolves [CVE-2021-27218](https://nvd.nist.gov/vuln/detail/CVE-2021-27218){: external}.
- Updates CSI sidecar images to fix [DLA-2542-1](https://www.debian.org/lts/security/2021/dla-2542){: external}, [DLA-2509-1](https://www.debian.org/lts/security/2020/dla-2509){: external}, and [DLA-2424-1](https://www.debian.org/lts/security/2020/dla-2424){: external}.
- Updates the sidecar images to the following versions.      
    - `csi-provisioner`: `icr.io/ext/sig-storage/csi-provisioner:v2.2.2`
    - `csi-resizer`: `icr.io/ext/sig-storage/csi-resizer:v1.2.0`
    - `csi-attacher`: `icr.io/ext/sig-storage/csi-attacher:v3.2.1`
    - `liveness-probe`: `icr.io/ext/sig-storage/livenessprobe:v2.3.0`
    - `csi-node-driver-registrar`: `icr.io/ext/sig-storage/csi-node-driver-registrar:v2.2.0`
- Updates the Golang version from `1.15.12` to `1.16.7`
- Increases the resources to the `csi-attacher`, `csi-resizer`, `csi-provisioner`, `ibm-vpc-block-csi-controller`, and `ibm-vpc-block-csi-node` plug-ins to fix containers crashing due to OOM issues.
- Improves volume attach/detach performance by increasing the worker thread count for the `csi-attacher` sidecar.
- Improves error messaging
- Fixes a bug related to unexpected IAM behavior.
- Changes the version numbering system to `X.X.Y_YYY` where `X.X` is the major version number and `.Y_YYY` is the patch version number.



## Version 3.0.1
{: #0301_is_block}

Review the changes in version `3.0.1` of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

### Change log for version 3.0.1, released 15 July 2021
{: #301_init}

Review the changelog for version `3.0.1` of the {{site.data.keyword.block_storage_is_short}} add-on.

Volume expansion in version `3.0.1` is available in beta for allowlisted accounts. Don't use this feature for production workloads.
{: beta}

- Image tags: `v3.0.7`  
- Includes beta support for volume expansion on allowlisted accounts.  
- Fixes vulnerability [CVE-2021-27219](https://nvd.nist.gov/vuln/detail/CVE-2021-27219){: external}.  
- Includes the `storage-secret-sidecar` container in the {{site.data.keyword.block_storage_is_short}} driver pods.  

## Version 3.0.0
{: #0300_is_block}

Review the changes in version 3.0.0 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

### Change log for patch update 3.0.0_521, released 01 April 2021
{: #3.0.0_521}

Review the changes in version 3.0.0_521 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v3.0.7`  
- Updates the Golang version from `1.15.5` to `1.15.9`.  


### Change log for version 3.0.0, released 26 February 2021
{: #0300_is_block_relnote}

Review the changes in version 3.0.0_521 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v.3.0.0`   
- The `vpc-block-csi-driver` is now available for both managed clusters and unmanaged clusters.   
- No functional changes in this release.  

## Archive
{: #unsupported_versions}

Find an overview of {{site.data.keyword.block_storage_is_short}} add-ons that are unsupported in IBM Cloud Kubernetes Service.

### Version 2.0.3
{: #0203_is_block}

Review the changes in version 2.0.3 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

Version 2.0.3 is unsupported.
{: important}

#### Change log for patch update 2.0.3_471, released 26 January 2021
{: #0203471_is_block}

Review the changes in version 2.0.3_471 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v.2.0.9`  
- Supported cluster versions: 4.3 - 4.6  
- Updated he `openssl`, `openssl-libs`, `gnutls` packages to fix [CVE-2020-1971](https://nvd.nist.gov/vuln/detail/CVE-2020-1971){: external} and [CVE-2020-24659](https://nvd.nist.gov/vuln/detail/CVE-2020-24659){: external}.  

#### Change log for patch update 2.0.3_464, released 10 December 2020
{: #0203464_is_block}

Review the changes in version 2.0.3_464 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v2.0.8`  
- **New!**: Metro storage classes with the `volumeBindingMode:WaitForFirstConsumer` specification.  
- Resources that are deployed by the add-on now contain a label which links the source code URL and the build URL.  
- The `v2.0.8` image is signed.  
- Updates the Go version from `1.15.2` to `1.15.5`.  

#### Change log for patch update 2.0.3_404, released 25 November 2020
{: #0203404_is_block}

Review the changes in version 2.0.3_404 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v2.0.7`   
- Fixes vulnerability scan issues.  
- Updates the base image from `alpine` to `UBI`.  
- Pods and containers now run as `non-root` except for the `node-server` pod's containers.  

#### Change log for patch update 2.0.3_375, released 17 September 2020
{: #0203375_is_block}

Review the changes in version 2.0.3_375 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v2.0.6`   
- Fixes an issue with volume attachment when replacing workers.  

#### Change log for patch update 2.0.3_374+, released 29 August 2020
{: #0203374_is_block}

Review the changes in version 2.0.3_374+ of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v2.0.5`   
- Adds the `/var/lib/kubelet` path for CSI driver calls on OCP 4.4.  

#### Change log for patch update 2.0.3_365, released 05 August 2020
{: #203365_is_block}

Review the changes in version 2.0.3_365 of the {{site.data.keyword.block_storage_is_short}} add-on.
{: shortdesc}

- Image tags: `v2.0.4`   
- Updates sidecar container images.  
- Adds liveness probe.  
- Enables parallel attachment and detachment of volumes to worker nodes. Previously, worker nodes were attached and detached sequentially.  
