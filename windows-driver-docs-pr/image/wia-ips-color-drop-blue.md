---
title: WIA\_IPS\_COLOR\_DROP\_BLUE
description: The WIA\_IPS\_COLOR\_DROP\_BLUE property is used to configure the amount of color drop-out for the Blue color channel (B in RGB), as a percentage in a range from 0 (no dropout) to 100 (full channel dropout).
ms.assetid: AA3E633C-766A-4935-B942-6938D543F801
keywords: ["WIA_IPS_COLOR_DROP_BLUE Imaging Devices"]
topic_type:
- apiref
api_name:
- WIA_IPS_COLOR_DROP_BLUE
api_location:
- Wiadef.h
api_type:
- HeaderDef
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# WIA\_IPS\_COLOR\_DROP\_BLUE


The **WIA\_IPS\_COLOR\_DROP\_BLUE** property is used to configure the amount of color drop-out for the Blue color channel (B in RGB), as a percentage in a range from 0% (no dropout) to 100% (full channel dropout). The WIA minidriver creates and maintains this property.

## <span id="ddk_wia_ipa_depth_si"></span><span id="DDK_WIA_IPA_DEPTH_SI"></span>


Property Type: VT\_I4

Valid Values: WIA\_PROP\_RANGE

Access Rights: Read/Write

Remarks
-------

When the [**WIA\_IPS\_COLOR\_DROP**](wia-ips-color-drop.md) property is supported, this property is valid for all programmable image data source items, including Flatbed (WIA\_CATEGORY\_FLATBED) and Feeder (WIA\_CATEGORY\_FEEDER) and is required. Valid values for this property are between 0 and 100, inclusive.

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
<td>Wiadef.h (include Wiadef.h)</td>
</tr>
</tbody>
</table>

 

 





