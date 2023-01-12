---

copyright: 
  years: 2014, 2023
lastupdated: "2023-01-12"

keywords: openshift, node scaling, ca, autoscaler

subcollection: openshift


---

{{site.data.keyword.attribute-definition-list}}



# Classic flavors
{: #classic-flavors}

Review the classic worker node flavors by zone.







## ams03
{: #ams03}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 1. Worker node flavors for ams03" caption-side="bottom"}

## che01
{: #che01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 2. Worker node flavors for che01" caption-side="bottom"}

## dal10
{: #dal10}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.48x384 | 384GB | 1000Mbps | 48 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.56x448 | 448GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.64x512 | 512GB | 1000Mbps | 64 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 3. Worker node flavors for dal10" caption-side="bottom"}

## dal12
{: #dal12}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.48x384 | 384GB | 1000Mbps | 48 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.56x448 | 448GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.64x512 | 512GB | 1000Mbps | 64 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 4. Worker node flavors for dal12" caption-side="bottom"}

## dal13
{: #dal13}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.48x384 | 384GB | 1000Mbps | 48 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.56x448 | 448GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.64x512 | 512GB | 1000Mbps | 64 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 5. Worker node flavors for dal13" caption-side="bottom"}

## fra02
{: #fra02}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 6. Worker node flavors for fra02" caption-side="bottom"}

## fra04
{: #fra04}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 7. Worker node flavors for fra04" caption-side="bottom"}

## fra05
{: #fra05}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 8. Worker node flavors for fra05" caption-side="bottom"}



## lon02
{: #lon02}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 9. Worker node flavors for lon02" caption-side="bottom"}

## lon04
{: #lon04}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 10. Worker node flavors for lon04" caption-side="bottom"}

## lon05
{: #lon05}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 11. Worker node flavors for lon05" caption-side="bottom"}

## lon06
{: #lon06}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 12. Worker node flavors for lon06" caption-side="bottom"}





## mil01
{: #mil01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 13. Worker node flavors for mil01" caption-side="bottom"}

## mon01
{: #mon01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 14. Worker node flavors for mon01" caption-side="bottom"}

## osa21
{: #osa21}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.48x384 | 384GB | 1000Mbps | 48 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.56x448 | 448GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.64x512 | 512GB | 1000Mbps | 64 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 15. Worker node flavors for osa21" caption-side="bottom"}

## osa22
{: #osa22}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.48x384 | 384GB | 1000Mbps | 48 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.56x448 | 448GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.64x512 | 512GB | 1000Mbps | 64 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 16. Worker node flavors for osa22" caption-side="bottom"}

## osa23
{: #osa23}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.48x384 | 384GB | 1000Mbps | 48 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.56x448 | 448GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.64x512 | 512GB | 1000Mbps | 64 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 17. Worker node flavors for osa23" caption-side="bottom"}



## par01
{: #par01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 18. Worker node flavors for par01" caption-side="bottom"}

## sao01
{: #sao01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 19. Worker node flavors for sao01" caption-side="bottom"}



## sjc03
{: #sjc03}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 20. Worker node flavors for sjc03" caption-side="bottom"}

## sjc04
{: #sjc04}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 21. Worker node flavors for sjc04" caption-side="bottom"}

## sng01
{: #sng01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 22. Worker node flavors for sng01" caption-side="bottom"}

## syd01
{: #syd01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 23. Worker node flavors for syd01" caption-side="bottom"}

## syd04
{: #syd04}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 24. Worker node flavors for syd04" caption-side="bottom"}

## syd05
{: #syd05}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 25. Worker node flavors for syd05" caption-side="bottom"}

## tok02
{: #tok02}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 26. Worker node flavors for tok02" caption-side="bottom"}

## tok04
{: #tok04}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 27. Worker node flavors for tok04" caption-side="bottom"}

## tok05
{: #tok05}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 28. Worker node flavors for tok05" caption-side="bottom"}

## tor01
{: #tor01}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 29. Worker node flavors for tor01" caption-side="bottom"}

## wdc04
{: #wdc04}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 30. Worker node flavors for wdc04" caption-side="bottom"}

## wdc06
{: #wdc06}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 31. Worker node flavors for wdc06" caption-side="bottom"}

## wdc07
{: #wdc07}

| Name | Memory | Network speed | Cores | Server type | OS | Primary storage | Auxiliary storage | 
| -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| b3c.16x64 | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.16x64.300gb | 64GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 300, Device type: SSD, RAID configuration: none | 
| b3c.32x128 | 128GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.4x16 | 16GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.56x242 | 242GB | 1000Mbps | 56 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| b3c.8x32 | 32GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x16 | 16GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.16x32 | 32GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x32 | 32GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| c3c.32x64 | 64GB | 1000Mbps | 32 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.16x128 | 128GB | 1000Mbps | 16 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.30x240 | 240GB | 1000Mbps | 30 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.4x32 | 32GB | 1000Mbps | 4 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| m3c.8x64 | 64GB | 1000Mbps | 8 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
| mb4c.20x192 | 192GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x384 | 384GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64 | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.20x64.2x1.9tb.ssd | 64GB | 10000Mbps | 20 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x384.6x3.8tb.ssd | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 1920, Device type: SSD, RAID configuration: none | 
| mb4c.32x768.3.8tb.ssd | 768GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mb4c.48x1536 | 1536GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| me4c.4x32 | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | 
| me4c.4x32.1.9tb.ssd | 32GB | 10000Mbps | 4 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.32x384.2xp100 | 384GB | 10000Mbps | 32 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| mg4c.48x384.2xv100 | 384GB | 10000Mbps | 48 | Physical | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 2000, Device type: HDD, RAID configuration: none | Count: 1, Size: 960, Device type: SSD, RAID configuration: none | 
| u3c.2x4 | 4GB | 1000Mbps | 2 | Virtual | **REDHAT_7_64 (default)**, REDHAT_8_64| Count: 1, Size: 25, Device type: SSD, RAID configuration: none | Count: 1, Size: 100, Device type: SSD, RAID configuration: none | 
{: caption="Table 32. Worker node flavors for wdc07" caption-side="bottom"}


