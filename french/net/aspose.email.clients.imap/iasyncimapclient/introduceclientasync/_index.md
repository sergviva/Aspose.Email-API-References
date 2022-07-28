---
title: IntroduceClientAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Présente les informations client à un serveur.
type: docs
weight: 210
url: /fr/net/aspose.email.clients.imap/iasyncimapclient/introduceclientasync/
---
## IAsyncImapClient.IntroduceClientAsync method

Présente les informations client à un serveur.

```csharp
public Task<ImapIdentificationInfo> IntroduceClientAsync(
    ImapIdentificationInfo clientIdentificationInfo, IConnection connection = null, 
    CancellationToken token = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | ImapIdentificationInfo | Connexion à un serveur |
| clientIdentificationInfo | IConnection | Informations d'identification du client |
| token | CancellationToken | Propage la notification indiquant que les opérations doivent être annulées. |

### Return_Value

Renvoie les informations d'identification du serveur

### Voir également

* class [ImapIdentificationInfo](../../imapidentificationinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->