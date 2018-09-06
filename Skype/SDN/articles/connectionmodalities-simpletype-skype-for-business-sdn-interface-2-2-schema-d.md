---
title: ConnectionModalities simpleType 
TOCTitle: ConnectionModalities simpleType
ms:assetid: ae0503ec-337a-b6d0-795f-274d4ddb8dc0
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171044(v=office.16)
ms:contentKeyID: 65855614
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ConnectionModalities simpleType 

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
    <xs:simpleType  name="ConnectionModalities">
    
      <xs:restriction base="xs:string">
    
      <xs:enumeration value="audio"/>
    
      <xs:enumeration value="video"/>
    
      <xs:enumeration value="data"/>
    
      <xs:enumeration value="applicationsharing"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

