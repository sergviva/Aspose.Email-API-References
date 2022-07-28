---
title: ListMessagesAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Liste les messages dans le dossier spécifié.
type: docs
weight: 450
url: /fr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync/
---
## ListMessagesAsync(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) {#listmessagesasync_1}

Liste les messages dans le dossier spécifié.

```csharp
public Task<ExchangeMessageInfoCollection> ListMessagesAsync(string folder, string mailbox = null, 
    int maxNumberOfMessages = 0, MailQuery query = null, bool recursive = false, 
    IEnumerable<PropertyDescriptor> extendedProperties = null, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| folder | String | Un dossier dans lequel rechercher des messages. |
| mailbox | String | Boîte aux lettres utilisée pour initialiser la classe d'ID de dossier. |
| maxNumberOfMessages | Int32 | Nombre maximal de messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) qui représente les critères de recherche de message. |
| recursive | Boolean | Indique s'il s'agit d'une liste récursive ou non. |
| extendedProperties | IEnumerable`1 | Propriétés étendues des messages récupérés |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)qui contient des messages du dossier spécifié.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Assemblée [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync}

Liste les messages dans le dossier spécifié.

```csharp
public Task<ExchangeMessageInfoCollection> ListMessagesAsync(IEnumerable<string> ids, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| ids | IEnumerable`1 | Énumération des identifiants de message |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Return_Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) qui contient des messages avec.

### Voir également

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->