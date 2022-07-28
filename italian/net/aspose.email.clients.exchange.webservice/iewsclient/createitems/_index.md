---
title: CreateItems
second_title: Aspose.Email per riferimento all'API .NET
description: Crea gli elementi specificati nella cartella specificata
type: docs
weight: 530
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/createitems/
---
## IEWSClient.CreateItems method

Crea gli elementi specificati nella cartella specificata

```csharp
public ExchangeUploadItemResult[] CreateItems(ExchangeStreamedItem[] items, string parentFolderUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| items | ExchangeStreamedItem[] | Un elemento da caricare |
| parentFolderUri | String | Specifica la cartella in cui posizionare gli elementi |

### Valore di ritorno

Una matrice di[`ExchangeUploadItemResult`](../../exchangeuploaditemresult)

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *items* è`nullo` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *items* è`vuoto` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri* è`nullo`o`vuoto` |

### Guarda anche

* class [ExchangeUploadItemResult](../../exchangeuploaditemresult)
* class [ExchangeStreamedItem](../../exchangestreameditem)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->