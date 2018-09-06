---
title: Hop element (RouteType complexType) 
TOCTitle: Hop element
ms:assetid: 086a46d4-2089-311f-452f-53445f6549ef
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt404771(v=office.16)
ms:contentKeyID: 68250679
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Hop element 

(RouteType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

IP address of one hop (router, gateway, switch, etc) on the path from the source to the destination of the media stream.

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
<td><p>xs:string</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="Hop"  type="xs:string" maxOccurs="unbounded">
    
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
<td><p><a href="route-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Route</a></p></td>
<td><p><a href="routetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">RouteType</a></p></td>
<td><p>Network path of the media stream only provided in Skype for Business 2013 and when the traceRoute feature is activated in Skype for Business.</p></td>
</tr>
<tr class="even">
<td><p><a href="route-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Route</a></p></td>
<td><p><a href="routetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">RouteType</a></p></td>
<td><p>Network path of the media stream only provided in Skype for Business 2013 and when the traceRoute feature is activated in Skype for Business.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

