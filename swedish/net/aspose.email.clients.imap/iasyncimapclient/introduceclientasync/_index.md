---
title: IntroduceClientAsync
second_title: Aspose.Email för .NET API-referens
description: Introducerar klientinformation till en server.
type: docs
weight: 210
url: /sv/net/aspose.email.clients.imap/iasyncimapclient/introduceclientasync/
---
## IAsyncImapClient.IntroduceClientAsync method

Introducerar klientinformation till en server.

```csharp
public Task<ImapIdentificationInfo> IntroduceClientAsync(
    ImapIdentificationInfo clientIdentificationInfo, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | ImapIdentificationInfo | Anslutning till en server |
| clientIdentificationInfo | IConnection | Kundidentifikationsinformation |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Returnerar serveridentifieringsinformation

### Se även

* class [ImapIdentificationInfo](../../imapidentificationinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->