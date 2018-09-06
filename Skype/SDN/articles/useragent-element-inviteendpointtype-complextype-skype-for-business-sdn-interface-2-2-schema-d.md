---
title: UserAgent element (InviteEndPointType complexType) 
TOCTitle: UserAgent element (InviteEndPointType complexType)
ms:assetid: 7d15d5b9-2565-f68f-aaef-380e442b7aed
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171026(v=office.16)
ms:contentKeyID: 65855599
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# UserAgent element 

(InviteEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Skype for Business client and version.


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="useragenttype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">UserAgentType</a></p></td>
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

    <xs:element name="UserAgent"  type="UserAgentType" minOccurs="0">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="callee-element-invitetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Callee</a></p></td>
<td><p><a href="inviteendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">InviteEndPointType</a></p></td>
<td><p>Properties of the callee.</p></td>
</tr>
<tr class="even">
<td><p><a href="caller-element-invitetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Caller</a></p></td>
<td><p><a href="inviteendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">InviteEndPointType</a></p></td>
<td><p>Properties of the caller.</p></td>
</tr>
</tbody>
</table>


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

