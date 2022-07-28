---
title: MarkAsJunkAsync
second_title: Aspose.Email för .NET API-referens
description: MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.
type: docs
weight: 550
url: /sv/net/aspose.email.clients.exchange.webservice/iasyncewsclient/markasjunkasync/
---
## IAsyncEwsClient.MarkAsJunkAsync method

MarkAsJunk-metoden flyttar e-postmeddelanden till skräppostmappen och blockerar meddelandeavsändaren.

```csharp
public Task<IEnumerable<string>> MarkAsJunkAsync(IEnumerable<string> messageUris, 
    bool isJunk = true, bool moveItem = false, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageUris | IEnumerable`1 | Uppräkning av meddelande-uri |
| isJunk | Boolean | Indikerar om meddelanden är markerade som skräppost. Om värdet på true lägger till meddelandeavsändaren till blockeringslistan. Om värdet på false tar bort meddelandeavsändaren från blockeringslistan. |
| moveItem | Boolean | Indikerar om meddelanden har flyttats till skräppostmappen. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Uppsättningen av identifierare för flyttade objekt

### Undantag

| undantag | skick |
| --- | --- |
| [EwsMarkAsJunkException](../../../aspose.email.clients.exchange.webservice.exceptions/ewsmarkasjunkexception) | Där var misslyckade föremål. |

### Se även

* interface [IAsyncEwsClient](../../iasyncewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->