---
title: FetchMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: جلب الرسائل المحددة .
type: docs
weight: 270
url: /ar/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync/
---
## IAsyncEwsClient.FetchMessagesAsync method

جلب الرسائل المحددة .

```csharp
public Task<MailMessageCollection> FetchMessagesAsync(IEnumerable<string> uris, 
    IEnumerable<PropertyDescriptor> extendedProperties = null, 
    CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uris | IEnumerable`1 | أIEnumerable تحتوي على uris الرسالة ليتم استرجاعها |
| extendedProperties | IEnumerable`1 | تعداد الخصائص الممتدة |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

أ[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)تحتوي على رسائل تم جلبها

### استثناءات

| استثناء | حالة |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *uris* هو`لا شيء` |

### أنظر أيضا

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->