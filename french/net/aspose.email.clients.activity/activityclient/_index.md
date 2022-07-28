---
title: ActivityClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Fournit un accès à MS Exchange Server Office365 à laide de lAPI REST.
type: docs
weight: 2360
url: /fr/net/aspose.email.clients.activity/activityclient/
---
## ActivityClient class

Fournit un accès à MS Exchange Server (Office365) à l'aide de l'API REST.

```csharp
public abstract class ActivityClient : IActivityClient
```

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [MultipleServicesTokenProvider](../../aspose.email.clients.activity/activityclient/multipleservicestokenprovider) { get; set; } | Obtient ou définit qu'un objet permet de récupérer le jeton d'accès OAuth. |
| virtual [Proxy](../../aspose.email.clients.activity/activityclient/proxy) { get; set; } | Obtient ou définit des données pour accéder par proxy au serveur Exchange. |
| virtual [ResourceId](../../aspose.email.clients.activity/activityclient/resourceid) { get; set; } | Obtient ou définit l'ID de ressource. Par exemple, pour les utilisateurs, il peut s'agir du nom d'utilisateur principal (UPN) ou de l'ID d'utilisateur |
| virtual [TenantId](../../aspose.email.clients.activity/activityclient/tenantid) { get; set; } | Obtient ou définit l'identifiant du locataire |
| virtual [Timeout](../../aspose.email.clients.activity/activityclient/timeout) { get; set; } | Obtient ou définit le nombre de millisecondes à attendre avant l'expiration de l'opération. La valeur par défaut est 100 000 millisecondes (100 secondes). |
| virtual [TokenProvider](../../aspose.email.clients.activity/activityclient/tokenprovider) { get; set; } | Obtient ou définit qu'un objet permet de récupérer le jeton d'accès OAuth. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.activity/activityclient/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [FetchContent](../../aspose.email.clients.activity/activityclient/fetchcontent)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent#listcontent)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent#listcontent_1)(string, DateTime?, DateTime?) |  |
| [ListFriendlyNames](../../aspose.email.clients.activity/activityclient/listfriendlynames)() |  |
| [ListSubscriptions](../../aspose.email.clients.activity/activityclient/listsubscriptions)() |  |
| [StartSubscription](../../aspose.email.clients.activity/activityclient/startsubscription)(string, Webhook) |  |
| [StopSubscription](../../aspose.email.clients.activity/activityclient/stopsubscription)(string) |  |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient#getclient)(IMultipleServicesTokenProvider, string) | Initialise une nouvelle instance du[`ActivityClient`](../activityclient) classe basée |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient#getclient_1)(ITokenProvider, string) | Initialise une nouvelle instance du[`ActivityClient`](../activityclient) classe basée |

### Voir également

* interface [IActivityClient](../iactivityclient)
* espace de noms [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->