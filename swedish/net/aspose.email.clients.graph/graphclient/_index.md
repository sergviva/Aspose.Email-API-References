---
title: GraphClient
second_title: Aspose.Email för .NET API-referens
description: Ger åtkomst till MS Exchange Server Office365 genom att använda REST API.
type: docs
weight: 15920
url: /sv/net/aspose.email.clients.graph/graphclient/
---
## GraphClient class

Ger åtkomst till MS Exchange Server (Office365) genom att använda REST API.

```csharp
public abstract class GraphClient : IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [MultipleServicesTokenProvider](../../aspose.email.clients.graph/graphclient/multipleservicestokenprovider) { get; set; } | Hämtar eller ställer in ett objekt som tillåter att hämta OAuth-åtkomsttoken. |
| virtual [Proxy](../../aspose.email.clients.graph/graphclient/proxy) { get; set; } | Hämtar eller ställer in data för proxyåtkomst till Exchange-servern. |
| virtual [Resource](../../aspose.email.clients.graph/graphclient/resource) { get; set; } | Hämtar eller ställer in resurstyp. |
| virtual [ResourceId](../../aspose.email.clients.graph/graphclient/resourceid) { get; set; } | Hämtar eller ställer in resurs-id. För användare kan det till exempel vara användarnamn (UPN) eller användar-id |
| virtual [TenantId](../../aspose.email.clients.graph/graphclient/tenantid) { get; set; } | Hämtar eller ställer in klientidentifierare |
| virtual [Timeout](../../aspose.email.clients.graph/graphclient/timeout) { get; set; } | Hämtar eller ställer in antalet millisekunder som ska vänta innan åtgärden tar slut. Standardvärdet är 100 000 millisekunder (100 sekunder). |
| virtual [TokenProvider](../../aspose.email.clients.graph/graphclient/tokenprovider) { get; set; } | Hämtar eller ställer in ett objekt som tillåter att hämta OAuth-åtkomsttoken. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.graph/graphclient/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| static [GetClient](../../aspose.email.clients.graph/graphclient/getclient#getclient)(IMultipleServicesTokenProvider, string) | Initierar en ny instans av[`GraphClient`](../graphclient) baserad klass |
| static [GetClient](../../aspose.email.clients.graph/graphclient/getclient#getclient_1)(ITokenProvider, string) | Initierar en ny instans av[`GraphClient`](../graphclient) baserad klass |

### Se även

* namnutrymme [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->