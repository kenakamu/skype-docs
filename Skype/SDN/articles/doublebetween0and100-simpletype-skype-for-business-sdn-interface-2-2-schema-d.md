---
title: DoubleBetween0And100 simpleType 
TOCTitle: DoubleBetween0And100 simpleType
ms:assetid: 9798d530-04fe-6208-a73f-732c8ffdf5b5
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171048(v=office.16)
ms:contentKeyID: 65855617
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# DoubleBetween0And100 simpleType 

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
<td><p>xs:double</p></td>
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
    <xs:simpleType  name="DoubleBetween0And100">
    
      <xs:restriction base="xs:double">
    
      <xs:minInclusive value="0"/>
    
      <xs:maxInclusive value="100"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

