---
title: OID_802_3_MAC_OPTIONS
author: windows-driver-content
description: OID_802_3_MAC_OPTIONS
ms.assetid: 9c1f29ad-6a2c-4cb4-b402-bd86e851dc2d
ms.author: windowsdriverdev
ms.date: 08/08/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
keywords: 
 -OID_802_3_MAC_OPTIONS Network Drivers Starting with Windows Vista
---

# OID\_802\_3\_MAC\_OPTIONS


## <a href="" id="ddk-oid-802-3-mac-options-nr"></a>


A protocol can use this OID to determine features supported by the underlying driver, which could be emulating Ethernet.

The underlying driver returns zero, indicating that it supports no options.

**Note**  This OID is obsolete for NDIS 6 drivers.

 

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ntddndis.h (include Ndis.h)</td>
</tr>
</tbody>
</table>

 

 




