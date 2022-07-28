---
title: ResolveMapiContactsAsync
second_title: Aspose.Email för .NET API-referens
description: Löser tvetydiga e-postadresser och visningsnamn Obs det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift.
type: docs
weight: 590
url: /sv/net/aspose.email.clients.exchange.webservice/iasyncewsclient/resolvemapicontactsasync/
---
## IAsyncEwsClient.ResolveMapiContactsAsync method

Löser tvetydiga e-postadresser och visningsnamn Obs: det maximala antalet returnerade kontakter är 100. Detta är en begränsning av använd EWS-drift.

```csharp
public Task<MapiContactCollection> ResolveMapiContactsAsync(string unresolvedEntry, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unresolvedEntry | String | Ett namn på kontakten att lösa |
| cancellationToken | CancellationToken | Avbokningstoken |

### Returvärde

A[`MapiContactCollection`](../../../aspose.email.mapi/mapicontactcollection) som representerar kontaktinformation

### Se även

* class [MapiContactCollection](../../../aspose.email.mapi/mapicontactcollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->