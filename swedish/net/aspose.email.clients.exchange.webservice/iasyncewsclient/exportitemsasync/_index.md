---
title: ExportItemsAsync
second_title: Aspose.Email för .NET API-referens
description: Exporterar de angivna objekten från mailbox
type: docs
weight: 210
url: /sv/net/aspose.email.clients.exchange.webservice/iasyncewsclient/exportitemsasync/
---
## IAsyncEwsClient.ExportItemsAsync method

Exporterar de angivna objekten från mailbox

```csharp
public Task<IEnumerable<ExchangeStreamedItem>> ExportItemsAsync(IEnumerable<string> itemIds, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| itemIds | IEnumerable`1 | Id för artiklar som ska exporteras |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

En uppställning av[`ExchangeStreamedItem`](../../exchangestreameditem)

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *itemIds* är`null` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *itemIds* är`tömma` |

### Se även

* class [ExchangeStreamedItem](../../exchangestreameditem)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->