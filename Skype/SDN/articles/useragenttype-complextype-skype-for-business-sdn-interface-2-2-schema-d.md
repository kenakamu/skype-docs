---
title: UserAgentType complexType 
TOCTitle: UserAgentType complexType
ms:assetid: a863d70e-aa89-a82b-7d77-7a2e1df35a92
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171077(v=office.16)
ms:contentKeyID: 65855650
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# UserAgentType complexType 

(Skype for Business SDN Interface 2.2, Schema "D")


**In this article**  
Type information  
Definition  
Elements and attributes  

## Type information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>xs:string</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="UserAgentType">
        <xs:complexContent>
 
        <xs:extension base="xs:string">
      
         <xs:attribute name="Type" type="xs:unsignedInt" use="optional"/>
  
        </xs:extension>
 
        </xs:complexContent>
 
      </xs:complexType>
      
```

## Elements and attributes

### Child elements

None.

### Attributes

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Type</p></th>
<th><p>Required</p></th>
<th><p>Description</p></th>
<th><p>Possible values</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Type</p></td>
<td><p>xs:unsignedInt</p></td>
<td><p>optional</p></td>
<td><p>Number describing the user agent.</p></td>
<td><p>Values of the xs:unsignedInt type.</p></td>
</tr>
</tbody>
</table>

