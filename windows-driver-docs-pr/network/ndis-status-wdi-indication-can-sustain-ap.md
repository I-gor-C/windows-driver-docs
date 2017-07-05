---
title: NDIS\_STATUS\_WDI\_INDICATION\_CAN\_SUSTAIN\_AP
description: Miniport drivers use NDIS\_STATUS\_WDI\_INDICATION\_CAN\_SUSTAIN\_AP to indicate that the port is ready to receive a OID\_WDI\_TASK\_START\_AP request, after previously indicating NDIS\_STATUS\_WDI\_INDICATION\_STOP\_AP.
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 638822A9-4CED-4564-86B3-8BC9DBA05DD3
keywords: ["NDIS_STATUS_WDI_INDICATION_CAN_SUSTAIN_AP Network Drivers Starting with Windows Vista"]
topic_type:
- apiref
api_name:
- NDIS_STATUS_WDI_INDICATION_CAN_SUSTAIN_AP
api_location:
- dot11wdi.h
api_type:
- HeaderDef
---

# NDIS\_STATUS\_WDI\_INDICATION\_CAN\_SUSTAIN\_AP


Miniport drivers use NDIS\_STATUS\_WDI\_INDICATION\_CAN\_SUSTAIN\_AP to indicate that the port is ready to receive a [OID\_WDI\_TASK\_START\_AP](oid-wdi-task-start-ap.md) request, after previously indicating [NDIS\_STATUS\_WDI\_INDICATION\_STOP\_AP](ndis-status-wdi-indication-stop-ap.md).

| Object |
|--------|
| Port   |

 

## Payload data


| Type                                                                                     | Multiple TLV instances allowed | Optional | Description                                                     |
|------------------------------------------------------------------------------------------|--------------------------------|----------|-----------------------------------------------------------------|
| [**WDI\_TLV\_INDICATION\_CAN\_SUSTAIN\_AP**](https://msdn.microsoft.com/library/windows/hardware/dn926317) |                                |          | The reason the adapter can now sustain 802.11 AP functionality. |

 

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum supported client</p></td>
<td><p>Windows 10</p></td>
</tr>
<tr class="even">
<td><p>Minimum supported server</p></td>
<td><p>Windows Server 2016</p></td>
</tr>
<tr class="odd">
<td><p>Header</p></td>
<td>Dot11wdi.h</td>
</tr>
</tbody>
</table>

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bnetvista\netvista%5D:%20NDIS_STATUS_WDI_INDICATION_CAN_SUSTAIN_AP%20%20RELEASE:%20%286/30/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



