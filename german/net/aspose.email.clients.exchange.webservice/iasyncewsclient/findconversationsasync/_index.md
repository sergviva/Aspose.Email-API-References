---
title: FindConversationsAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Findet Konversationen im angegebenen Ordner
type: docs
weight: 290
url: /de/net/aspose.email.clients.exchange.webservice/iasyncewsclient/findconversationsasync/
---
## IAsyncEwsClient.FindConversationsAsync method

Findet Konversationen im angegebenen Ordner

```csharp
public Task<ExchangeConversation[]> FindConversationsAsync(string folderId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderId | String | Eine ID des Ordners, in dem gesucht wird |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Rückgabewert

Ein Array von gefundenen[`ExchangeConversation`](../../exchangeconversation)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folderId* ist`Null`oder`leer` |

### Siehe auch

* class [ExchangeConversation](../../exchangeconversation)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->