---
title: ThisVersion simpleType 
TOCTitle: ThisVersion simpleType
ms:assetid: 571a287c-8368-f496-6adb-e2d9714d413e
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171052(v=office.16)
ms:contentKeyID: 65855625
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ThisVersion simpleType 

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
    <xs:simpleType  name="ThisVersion">
    
      <xs:restriction base="xs:string">
    
      <xs:enumeration value="D"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

