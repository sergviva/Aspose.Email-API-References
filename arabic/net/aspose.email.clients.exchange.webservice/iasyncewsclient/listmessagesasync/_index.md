---
title: ListMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: سرد الرسائل في المجلد المحدد .
type: docs
weight: 450
url: /ar/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesasync/
---
## ListMessagesAsync(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) {#listmessagesasync_1}

سرد الرسائل في المجلد المحدد .

```csharp
public Task<ExchangeMessageInfoCollection> ListMessagesAsync(string folder, string mailbox = null, 
    int maxNumberOfMessages = 0, MailQuery query = null, bool recursive = false, 
    IEnumerable<PropertyDescriptor> extendedProperties = null, 
    CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| mailbox | String | علبة البريد المستخدمة لتهيئة فئة معرف المجلد. |
| maxNumberOfMessages | Int32 | أقصى عدد من الرسائل. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث في الرسائل. |
| recursive | Boolean | يشير إلى ما إذا كان سرد متكرر أم لا. |
| extendedProperties | IEnumerable`1 | الخصائص الممتدة للرسائل المستردة |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync}

سرد الرسائل في المجلد المحدد .

```csharp
public Task<ExchangeMessageInfoCollection> ListMessagesAsync(IEnumerable<string> ids, 
    CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| ids | IEnumerable`1 | تعداد هويات الرسائل |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) الذي يحتوي على رسائل ذات.

### أنظر أيضا

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->