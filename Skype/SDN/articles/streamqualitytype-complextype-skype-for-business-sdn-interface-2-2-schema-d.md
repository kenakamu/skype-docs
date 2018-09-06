---
title: StreamQualityType complexType 
TOCTitle: StreamQualityType complexType
ms:assetid: 236f8a1c-9dad-1d72-8861-26f2837522f3
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171076(v=office.16)
ms:contentKeyID: 65855649
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# StreamQualityType complexType 

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
      <xs:complexType name="StreamQualityType">
        <xs:complexContent>
 
        <xs:extension base="xs:string">
      
         <xs:attribute name="Source" type="xs:string" use="optional"/>
  
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
<td><p>Source</p></td>
<td><p>xs:string</p></td>
<td><p>optional</p></td>
<td><p>Source that cause the stream's quality determination.</p></td>
<td><p>Values of the xs:string type.</p></td>
</tr>
</tbody>
</table>

