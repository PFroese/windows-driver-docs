---
title: NdisMRegisterIoPortRange rule (ndis)
description: A miniport driver calls NdisMRegisterIoPortRange from its MiniportInitializeEx or MINIPORT\_ADD\_DEVICE functions. MiniportInitializeEx or MINIPORT\_ADD\_DEVICE must call NdisMSetMiniportAttributes before calling NdisMRegisterIoPortRange.
ms.assetid: 74CFCBDB-3044-4447-ABEF-A60BA31C0BE0
keywords: ["NdisMRegisterIoPortRange rule (ndis)"]
topic_type:
- apiref
api_name:
- NdisMRegisterIoPortRange
api_type:
- NA
---

# NdisMRegisterIoPortRange rule (ndis)


A miniport driver calls [**NdisMRegisterIoPortRange**](https://msdn.microsoft.com/library/windows/hardware/ff563651) from its [*MiniportInitializeEx*](https://msdn.microsoft.com/library/windows/hardware/ff559389) or MINIPORT\_ADD\_DEVICE functions. *MiniportInitializeEx* or MINIPORT\_ADD\_DEVICE must call [**NdisMSetMiniportAttributes**](https://msdn.microsoft.com/library/windows/hardware/ff563672) before calling **NdisMRegisterIoPortRange**.

|              |      |
|--------------|------|
| Driver model | NDIS |

How to test
-----------

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">At compile time</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Run [Static Driver Verifier](https://msdn.microsoft.com/library/windows/hardware/ff552808) and specify the <strong>NdisMRegisterIoPortRange</strong> rule.</p>
Use the following steps to run an analysis of your code:
<ol>
<li>[Prepare your code (use role type declarations).](https://msdn.microsoft.com/library/windows/hardware/hh454281#preparing-your-source-code)</li>
<li>[Run Static Driver Verifier.](https://msdn.microsoft.com/library/windows/hardware/hh454281#running-static-driver-verifier)</li>
<li>[View and analyze the results.](https://msdn.microsoft.com/library/windows/hardware/hh454281#viewing-and-analyzing-the-results)</li>
</ol>
<p>For more information, see [Using Static Driver Verifier to Find Defects in Drivers](https://msdn.microsoft.com/library/windows/hardware/hh454281).</p></td>
</tr>
</tbody>
</table>

Applies to
----------

[**NdisMRegisterIoPortRange**](https://msdn.microsoft.com/library/windows/hardware/ff563651)
[**NdisMSetMiniportAttributes**](https://msdn.microsoft.com/library/windows/hardware/ff563672)
 

 





