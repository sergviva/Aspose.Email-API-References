---
title: CopyItemAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Copie lélément dans le dossier spécifié
type: docs
weight: 80
url: /fr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/copyitemasync/
---
## IAsyncEwsClient.CopyItemAsync method

Copie l'élément dans le dossier spécifié

```csharp
public Task<string> CopyItemAsync(string itemUri, string destinationFolderUri, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| itemUri | String | L'URI de l'élément |
| destinationFolderUri | String | L'URI du dossier de destination |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Return_Value

Un uri du message copié

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *itemUri* est`nul`ou`vide` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderUri* est`nul`ou`vide` |

### Voir également

* interface [IAsyncEwsClient](../../iasyncewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->