---
title: ConnectionPlatforms simpleType 
TOCTitle: ConnectionPlatforms simpleType
ms:assetid: 3ce2b946-41fb-8db7-c4c9-1b4b72799319
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171045(v=office.16)
ms:contentKeyID: 65855620
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ConnectionPlatforms simpleType 

(Skype for Business SDN Interface 2.2, Schema "D")


## Type information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Base type</strong></p></td>
<td><p>xs:string</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
    <xs:simpleType  name="ConnectionPlatforms">
    
      <xs:restriction base="xs:string">
    
      <xs:enumeration value="Wifi"/>
    
      <xs:enumeration value="wifi"/>
    
      <xs:enumeration value="Ethernet"/>
    
      <xs:enumeration value="wired"/>
    
      <xs:enumeration value="MobileBB"/>
    
      <xs:enumeration value="Tunnel"/>
    
      <xs:enumeration value="Other"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

