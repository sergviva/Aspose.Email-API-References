---
title: FetchMessagesAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft die angegebenen Nachrichten ab.
type: docs
weight: 270
url: /de/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync/
---
## IAsyncEwsClient.FetchMessagesAsync method

Ruft die angegebenen Nachrichten ab.

```csharp
public Task<MailMessageCollection> FetchMessagesAsync(IEnumerable<string> uris, 
    IEnumerable<PropertyDescriptor> extendedProperties = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uris | IEnumerable`1 | EINIEnumerable mit Nachrichten-URIS, die abgerufen werden sollen |
| extendedProperties | IEnumerable`1 | Eine Aufzählung erweiterter Eigenschaften |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Rückgabewert

EIN[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)mit abgerufenen Nachrichten

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *uris* ist`Null` |

### Siehe auch

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->