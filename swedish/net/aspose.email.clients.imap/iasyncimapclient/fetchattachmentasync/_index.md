---
title: FetchAttachmentAsync
second_title: Aspose.Email för .NET API-referens
description: Hämtar den angivna bilagan.
type: docs
weight: 140
url: /sv/net/aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync/
---
## IAsyncImapClient.FetchAttachmentAsync method

Hämtar den angivna bilagan.

```csharp
public Task<Attachment> FetchAttachmentAsync(int sequenceNumber, string attachmentName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | Int32 | Anslutning till en server. |
| sequenceNumber | String | Sekvensnumret för ett meddelande. |
| attachmentName | IConnection | Ett namn på bilagan. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

[`Attachment`](../../../aspose.email/attachment) som representerar anknytningen.

### Se även

* class [Attachment](../../../aspose.email/attachment)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->