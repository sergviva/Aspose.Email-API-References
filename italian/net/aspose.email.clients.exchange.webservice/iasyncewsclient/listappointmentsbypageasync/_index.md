---
title: ListAppointmentsByPageAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Recupera la pagina con gli appuntamenti per la cartella del calendario specificata
type: docs
weight: 410
url: /it/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsbypageasync/
---
## IAsyncEwsClient.ListAppointmentsByPageAsync method

Recupera la pagina con gli appuntamenti per la cartella del calendario specificata

```csharp
public Task<AppointmentPageInfo> ListAppointmentsByPageAsync(string folderUri, MailQuery query, 
    int itemsPerPage, int itemOffset, CancellationToken cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderUri | String | Una cartella in cui cercare gli appuntamenti. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta i criteri di ricerca degli appuntamenti. |
| itemsPerPage | Int32 | Una serie di elementi nella pagina |
| itemOffset | Int32 | Un offset dell'elemento successivo in vista |
| cancellationToken | CancellationToken | Il token di annullamento. |

### Valore di ritorno

Pagina Resi con appuntamenti

### Guarda anche

* class [AppointmentPageInfo](../../../aspose.email.clients.exchange/appointmentpageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->