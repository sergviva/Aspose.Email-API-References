---
title: ClientCapabilities
second_title: Référence de l'API Aspose.Email pour .NET
description: Informe le serveur des extensions prises en charge par le client. Veuillez noter que cette opération ne fonctionne que si le serveur prend en charge RFC5161 Voir plus https//tools.ietf.org/html/rfc5161
type: docs
weight: 440
url: /fr/net/aspose.email.clients.imap/imapclient/clientcapabilities/
---
## ClientCapabilities(params string[]) {#clientcapabilities_1}

Informe le serveur des extensions prises en charge par le client. Veuillez noter que cette opération ne fonctionne que si le serveur prend en charge RFC5161 Voir plus https://tools.ietf.org/html/rfc5161

```csharp
public string[] ClientCapabilities(params string[] capabilityNames)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| capabilityNames | String[] | Gamme de fonctionnalités prises en charge par le client |

### Return_Value

Renvoie un tableau avec des fonctionnalités prises en charge par un serveur.

### Voir également

* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

---

## ClientCapabilities(IConnection, params string[]) {#clientcapabilities}

Informe le serveur des extensions prises en charge par le client. Veuillez noter que cette opération ne fonctionne que si le serveur prend en charge RFC5161 Voir plus https://tools.ietf.org/html/rfc5161

```csharp
public string[] ClientCapabilities(IConnection connection, params string[] capabilityNames)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| connection | IConnection | Connexion à un serveur |
| capabilityNames | String[] | Gamme de fonctionnalités prises en charge par le client |

### Return_Value

Renvoie un tableau avec des fonctionnalités prises en charge par un serveur.

### Voir également

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espace de noms [Aspose.Email.Clients.Imap](../../imapclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->