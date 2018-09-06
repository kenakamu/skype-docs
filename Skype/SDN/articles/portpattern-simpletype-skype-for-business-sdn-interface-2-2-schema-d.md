---
title: PortPattern simpleType 
TOCTitle: PortPattern simpleType
ms:assetid: 48777069-7002-0023-cc09-98381b13305f
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171051(v=office.16)
ms:contentKeyID: 65855622
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# PortPattern simpleType 

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
    <xs:simpleType  name="PortPattern">
    
      <xs:restriction base="xs:string">
    
      <xs:pattern value="[0-9]{2,5}"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

