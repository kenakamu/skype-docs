---
title: BSSIDPattern simpleType 
TOCTitle: BSSIDPattern simpleType
ms:assetid: 0b7aa4c4-9022-1da0-6fb3-1a9ff8581415
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171042(v=office.16)
ms:contentKeyID: 65855616
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# BSSIDPattern simpleType 

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
    <xs:simpleType  name="BSSIDPattern">
    
      <xs:restriction base="xs:string">
    
      <xs:pattern value="[0-9A-F]{2}\-[0-9A-F]{2}\-[0-9A-F]{2}\-[0-9A-F]{2}\-[0-9A-F]{2}\-[0-9A-F]{2}"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

