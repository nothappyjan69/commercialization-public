---
title: BDATeam
description: BDATeam
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 63385903-c6f0-41cb-baae-db3ce62341b6
ms.mktglfcycl: deploy
ms.sitesec: msdn
ms.author: alhopper
ms.date: 05/02/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---

# BDATeam


`BDATeam` specifies details about a bidirectional affinity (BDA) team.

**Note**  
To enable this Network Load Balancing setting, the NetworkLoadBalancingFullServer package must be enabled in the Windows image you are installing. To do this, use Windows System Image Manager to add the Microsoft-Windows-Foundation-Package to your answer file, and then configure the NetworkLoadBalancingFullServer package to enable it. For more information about adding and configuring packages, see the [Windows Assessment and Deployment (Windows ADK) Technical Reference](http://go.microsoft.com/fwlink/?LinkId=206587).

 

## Child Elements


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>[Master](microsoft-windows-networkloadbalancing-core-clusters-cluster-bdateam-master.md)</p></td>
<td><p>Specifies whether the host is the master.</p></td>
</tr>
<tr class="even">
<td><p>[ReverseHash](microsoft-windows-networkloadbalancing-core-clusters-cluster-bdateam-reversehash.md)</p></td>
<td><p>Specifies whether the adapter reverses the source and destination IP addresses and ports before making load-balancing decisions.</p></td>
</tr>
<tr class="odd">
<td><p>[Team](microsoft-windows-networkloadbalancing-core-clusters-cluster-bdateam-team.md)</p></td>
<td><p>Specifies a valid Globally Unique Identifier (GUID) that identifies a BDA team.</p></td>
</tr>
</tbody>
</table>

 

## Valid Passes


specialize

## Parent Hierarchy


[microsoft-windows-networkloadbalancing-core-](microsoft-windows-networkloadbalancing-core.md) | [Clusters](microsoft-windows-networkloadbalancing-core-clusters.md) | [Cluster](microsoft-windows-networkloadbalancing-core-clusters-cluster.md) | **BDATeam**

## Applies To


For a list of the supported Windows editions and architectures that this component supports, see [microsoft-windows-networkloadbalancing-core-](microsoft-windows-networkloadbalancing-core.md).

## XML Example


The following XML output specifies details about a BDA team.

```
<BDATeam>
   <Team>{BF967924-0DE6-11D0-A285-00AA003049E2}</Team>
   <Master>true</Master>
   <ReverseHash>true</ReverseHash>
</BDATeam>
```

## Related topics


[Cluster](microsoft-windows-networkloadbalancing-core-clusters-cluster.md)

 

 







