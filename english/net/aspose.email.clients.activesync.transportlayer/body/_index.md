---
title: Body
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1030
url: /net/aspose.email.clients.activesync.transportlayer/body/
---
## Body class

Specifies a free-form, variable-length data field associated with a stored item on the server.

```csharp
public class Body
```

## Constructors

| Name | Description |
| --- | --- |
| [Body](body)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Data](../../aspose.email.clients.activesync.transportlayer/body/data) { get; set; } | The content of the Data element is a string in the format that is specified by the Type property. If the value of the Type is RTF, the value of the Data element is encoded using base64 encoding. If the Truncated property set true, the data in the Data element is truncated. The EstimatedDataSize property provides a rough estimation of the actual size of the complete content of the Data string. |
| [EstimatedDataSize](../../aspose.email.clients.activesync.transportlayer/body/estimateddatasize) { get; set; } | Specifies an informational estimate of the size of the data associated with the parent element. The EstimatedDataSize element SHOULD be presented whenever the Truncated element is set to TRUE |
| [Part](../../aspose.email.clients.activesync.transportlayer/body/part) { get; set; } | Contains an integer index into the metadata of the multipart response. This property MUST be present in multipart responses. This property MUST NOT be present in requests or non-multipart responses. |
| [Preview](../../aspose.email.clients.activesync.transportlayer/body/preview) { get; set; } | Contains the Unicode plain text message or message part preview returned to the client. |
| [Truncated](../../aspose.email.clients.activesync.transportlayer/body/truncated) { get; set; } | Specifies whether the body of the item has been truncated according to the BodyPreference element indicated by the client. If the value is TRUE, then the body of the item has been truncated. If the value is FALSE, or Truncated property is not set, then the body of the item has not been truncated. |
| [Type](../../aspose.email.clients.activesync.transportlayer/body/type) { get; set; } | Specifies the format type of the body content of the item. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->