---
title: ActivityClient
second_title: Aspose.Email för .NET API-referens
description: Ger åtkomst till MS Exchange Server Office365 genom att använda REST API.
type: docs
weight: 2360
url: /sv/net/aspose.email.clients.activity/activityclient/
---
## ActivityClient class

Ger åtkomst till MS Exchange Server (Office365) genom att använda REST API.

```csharp
public abstract class ActivityClient : IActivityClient
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [MultipleServicesTokenProvider](../../aspose.email.clients.activity/activityclient/multipleservicestokenprovider) { get; set; } | Hämtar eller ställer in ett objekt som tillåter att hämta OAuth-åtkomsttoken. |
| virtual [Proxy](../../aspose.email.clients.activity/activityclient/proxy) { get; set; } | Hämtar eller ställer in data för proxyåtkomst till Exchange-servern. |
| virtual [ResourceId](../../aspose.email.clients.activity/activityclient/resourceid) { get; set; } | Hämtar eller ställer in resurs-id. För användare kan det till exempel vara användarnamn (UPN) eller användar-id |
| virtual [TenantId](../../aspose.email.clients.activity/activityclient/tenantid) { get; set; } | Hämtar eller ställer in klientidentifierare |
| virtual [Timeout](../../aspose.email.clients.activity/activityclient/timeout) { get; set; } | Hämtar eller ställer in antalet millisekunder som ska vänta innan åtgärden tar slut. Standardvärdet är 100 000 millisekunder (100 sekunder). |
| virtual [TokenProvider](../../aspose.email.clients.activity/activityclient/tokenprovider) { get; set; } | Hämtar eller ställer in ett objekt som tillåter att hämta OAuth-åtkomsttoken. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.activity/activityclient/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [FetchContent](../../aspose.email.clients.activity/activityclient/fetchcontent)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent#listcontent)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent#listcontent_1)(string, DateTime?, DateTime?) |  |
| [ListFriendlyNames](../../aspose.email.clients.activity/activityclient/listfriendlynames)() |  |
| [ListSubscriptions](../../aspose.email.clients.activity/activityclient/listsubscriptions)() |  |
| [StartSubscription](../../aspose.email.clients.activity/activityclient/startsubscription)(string, Webhook) |  |
| [StopSubscription](../../aspose.email.clients.activity/activityclient/stopsubscription)(string) |  |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient#getclient)(IMultipleServicesTokenProvider, string) | Initierar en ny instans av[`ActivityClient`](../activityclient) baserad klass |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient#getclient_1)(ITokenProvider, string) | Initierar en ny instans av[`ActivityClient`](../activityclient) baserad klass |

### Se även

* interface [IActivityClient](../iactivityclient)
* namnutrymme [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->