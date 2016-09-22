
# participantApplicationSharing 


 _**Applies to:** Skype for Business 2015_


Represents whether a participant is using the application sharing modality in a conversation. 

## Web Link
<a name="sectionSection0"> </a>

For more on web links, see [Web links](WebLinks.md).



|**Name**|**Description**|
|:-----|:-----|
|rel|The resource that this link points to. In JSON, this is the outer container.|
|href|The location of this resource on the server, and the target of an HTTP operation.|
|title|The source id for the application sharing media of this participant, if available. This is useful for configuring the media stack.|

## Resource description
<a name="sectionSection1"> </a>

This resource helps the application track when a participant joins or leaves this modality. 


### Properties

None


### Links

This resource can have the following relationships.



|**Link**|**Description**|
|:-----|:-----|
|self|The link to the current resource.|
|participant|Represents a remote participant in a [conversation](conversation_ref.md).|

## Events
<a name="sectionSection2"> </a>




### added





|**Resource**|**Priority**|**Sender**|**Reason**|
|:-----|:-----|:-----|:-----|
|participantApplicationSharing|High|conversation|Indicates that a participant is now using the application sharing modality.|
|participantApplicationSharing|High|conversation|Indicates that the user is now using the application sharing modality.|
Sample of returned event data.

This sample is given only as an illustration of event syntax. The semantic content is not guaranteed to correspond to a valid scenario.




```

{
 "_links" : {
 "self" : {
 "href" : "http://sample:80/ucwa/v1/applications/appId/events?ack=1"
 },
 "next" : {
 "href" : "http://sample:80/ucwa/v1/applications/appId/events?ack=2"
 }
 },
 "sender" : [
 {
 "rel" : "conversation",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802",
 "events" : [
 {
 "link" : {
 "rel" : "participantApplicationSharing",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575/participantApplicationSharing"
 },
 "in" : {
 "rel" : "participant",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575"
 },
 "type" : "added"
 }
 ]
 }
 ]
}
					
```


### updated





|**Resource**|**Priority**|**Sender**|**Reason**|
|:-----|:-----|:-----|:-----|
|participantApplicationSharing|High|conversation|Indicates that a participant's application sharing modality has changed.|
|participantApplicationSharing|High|conversation|Indicates that the user's application sharing modality has changed.|
Sample of returned event data.

This sample is given only as an illustration of event syntax. The semantic content is not guaranteed to correspond to a valid scenario.




```

{
 "_links" : {
 "self" : {
 "href" : "http://sample:80/ucwa/v1/applications/appId/events?ack=1"
 },
 "next" : {
 "href" : "http://sample:80/ucwa/v1/applications/appId/events?ack=2"
 }
 },
 "sender" : [
 {
 "rel" : "conversation",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802",
 "events" : [
 {
 "link" : {
 "rel" : "participantApplicationSharing",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575/participantApplicationSharing"
 },
 "in" : {
 "rel" : "participant",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575"
 },
 "type" : "updated"
 }
 ]
 }
 ]
}
					
```


### deleted





|**Resource**|**Priority**|**Sender**|**Reason**|
|:-----|:-----|:-----|:-----|
|participantApplicationSharing|High|conversation|Indicates that a participant is no longer using the application sharing modality.|
|participantApplicationSharing|High|conversation|Indicates that the user is no longer using the application sharing modality.|
Sample of returned event data.




```

{
 "_links" : {
 "self" : {
 "href" : "http://sample:80/ucwa/v1/applications/appId/events?ack=1"
 },
 "next" : {
 "href" : "http://sample:80/ucwa/v1/applications/appId/events?ack=2"
 }
 },
 "sender" : [
 {
 "rel" : "conversation",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802",
 "events" : [
 {
 "link" : {
 "rel" : "participantApplicationSharing",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575/participantApplicationSharing"
 },
 "in" : {
 "rel" : "participant",
 "href" : "https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575"
 },
 "type" : "deleted"
 }
 ]
 }
 ]
}
					
```


## Operations
<a name="sectionSection3"> </a>




### GET

Returns a representation of the application sharing modality for a participant.


#### Request body

None


#### Response body

The response from a GET request contains the properties and links shown in the Properties and Links sections at the top of this page.


#### Synchronous errors

The errors below (if any) are specific to this resource. Generic errors that can apply to any resource are covered in [Generic synchronous errors](GenericSynchronousErrors.md).



|**Error**|**Code**|**Subcode**|**Description**|
|:-----|:-----|:-----|:-----|
|ServiceFailure|500|InvalidExchangeServerVersion|Invalid exchange server version.The exchange mailbox of the server might have moved to an unsupported version for the required feature.|
|Conflict|409|AlreadyExists|The already exists error.|
|Conflict|409|TooManyGroups|The too many groups error.|
|Conflict|409|None|Un-supported Service/Resource/API error.|

#### Examples




#### JSON Request


```

 Get https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575/participantApplicationSharing HTTP/1.1
 Authorization: Bearer cwt=PHNhbWw6QXNzZXJ0aW9uIHhtbG5...uZm8
 Host: fe1.contoso.com
 Accept: application/json
 
									
```


#### JSON Response

This sample is given only as an illustration of response syntax. The semantic content is not guaranteed to correspond to a valid scenario.


```

 HTTP/1.1 200 OK
 Content-Type: application/json
 Content-Length: 265
 {
 "rel" : "participantApplicationSharing",
 "_links" : {
 "self" : {
 "href" : "//v1/applications/833/communication/conversations/802/participants/575/participantApplicationSharing"
 },
 "participant" : {
 "href" : "//v1/applications/833/communication/conversations/802/participants/575"
 }
 }
}
									
```


#### XML Request


```

 Get https://fe1.contoso.com:443//v1/applications/833/communication/conversations/802/participants/575/participantApplicationSharing HTTP/1.1
 Authorization: Bearer cwt=PHNhbWw6QXNzZXJ0aW9uIHhtbG5...uZm8
 Host: fe1.contoso.com
 Accept: application/xml
 
									
```


#### XML Response

This sample is given only as an illustration of response syntax. The semantic content is not guaranteed to correspond to a valid scenario.


```

 HTTP/1.1 200 OK
 Content-Type: application/xml
 Content-Length: 422
 <?xml version="1.0" encoding="utf-8"?>
<resource rel="participantApplicationSharing" href="//v1/applications/833/communication/conversations/802/participants/575/participantApplicationSharing" xmlns="http://schemas.microsoft.com/rtc/2012/03/ucwa">
 <link rel="participant" href="//v1/applications/833/communication/conversations/802/participants/575" />
 <property name="rel">participantApplicationSharing</property>
</resource>
									
```

