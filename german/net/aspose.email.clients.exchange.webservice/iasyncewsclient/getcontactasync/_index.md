---
title: GetContactAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft Kontaktinformationen gemäß der angegebenen Kennung ab.
type: docs
weight: 320
url: /de/net/aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync/
---
## IAsyncEwsClient.GetContactAsync method

Ruft Kontaktinformationen gemäß der angegebenen Kennung ab.

```csharp
public Task<Contact> GetContactAsync(string contactId, 
    ExchangeListContactsOptions options = ExchangeListContactsOptions.FetchPhoto, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contactId | String | Kontaktkennung. |
| options | ExchangeListContactsOptions | Einstellungen zum Abrufen von Kontakten. |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Rückgabewert

Kontaktinformationen

### Siehe auch

* class [Contact](../../../aspose.email.personalinfo/contact)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->