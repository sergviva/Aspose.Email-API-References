---
title: EWSClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Fournit un accès à MS Exchange Server à laide des services Web Exchange EWS.
type: docs
weight: 3680
url: /fr/net/aspose.email.clients.exchange.webservice/ewsclient/
---
## EWSClient class

Fournit un accès à MS Exchange Server à l'aide des services Web Exchange (EWS).

```csharp
public abstract class EWSClient : ExchangeClientBase
```

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Obtient ou définit les informations d'identification |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Obtient ou définit le nom du fichier journal |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Obtient ou définit la boîte aux lettres uri |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Obtient ou définit le proxy. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Obtient ou définit le nombre de millisecondes à attendre avant l'expiration de l'opération. La valeur par défaut est 100 000 millisecondes (100 secondes). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Obtient ou définit la valeur qui indique si la date doit être utilisée dans le nom du fichier journal. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_2)(string, ICredentials) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_3)(string, ICredentials, WebProxy) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_4)(string, string, string) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_1)(ExchangeVersion, string, ICredentials, WebProxy) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_6)(string, string, string, string) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_5)(string, string, string, WebProxy) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_7)(string, string, string, string, WebProxy) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient)(ExchangeVersion, bool, string, string, ICredentials, WebProxy) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |
| static [GetEwsClientAsync](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclientasync)(string, ICredentials, WebProxy, CancellationToken) | Initialise une nouvelle instance du[`EWSClient`](../ewsclient) classe basée |

### Voir également

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->