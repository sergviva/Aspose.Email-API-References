---
title: FetchAppointmentAsync
second_title: Référence de l'API Aspose.Email pour .NET
description: Récupérer le rendez-vous spécifié à partir du serveur.
type: docs
weight: 220
url: /fr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchappointmentasync/
---
## IAsyncEwsClient.FetchAppointmentAsync method

Récupérer le rendez-vous spécifié à partir du serveur.

```csharp
public Task<Appointment> FetchAppointmentAsync(string appointmentUri, string folderUri, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| appointmentUri | String | Un uri de rendez-vous à aller chercher. |
| folderUri | String | Un uri du dossier parent des rendez-vous. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Return_Value

Un récupéré[`Appointment`](../../../aspose.email.calendar/appointment).

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *appointmentUri* est`nul`ou`vide`. |

### Voir également

* class [Appointment](../../../aspose.email.calendar/appointment)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espace de noms [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->