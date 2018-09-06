---
title: EndpointIdPattern simpleType 
TOCTitle: EndpointIdPattern simpleType
ms:assetid: 20c01d5f-044c-24bf-f9f0-a4600db1b6ce
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171047(v=office.16)
ms:contentKeyID: 65855621
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# EndpointIdPattern simpleType 

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
    <xs:simpleType  name="EndpointIdPattern">
    
      <xs:restriction base="xs:string">
    
      <xs:pattern value="[0-9a-fA-F]{1,40}"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

