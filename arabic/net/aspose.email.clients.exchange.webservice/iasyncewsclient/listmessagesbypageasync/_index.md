---
title: ListMessagesByPageAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: سرد الرسائل في المجلد المحدد .
type: docs
weight: 460
url: /ar/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync/
---
## ListMessagesByPageAsync(string, int, int, MailQuery, CancellationToken) {#listmessagesbypageasync_1}

سرد الرسائل في المجلد المحدد .

```csharp
public Task<ExchangeMessagePageInfo> ListMessagesByPageAsync(string folder, int itemsPerPage, 
    int offset = 0, MailQuery query = null, CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| itemsPerPage | Int32 | عدد من العناصر في الصفحة |
| offset | Int32 | إزاحة الصفحة التالية في العرض |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) التي تمثل معايير البحث. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

---

## ListMessagesByPageAsync(string, PageInfo, CancellationToken) {#listmessagesbypageasync}

سرد الرسائل في المجلد المحدد .

```csharp
public Task<ExchangeMessagePageInfo> ListMessagesByPageAsync(string folder, PageInfo pageInfo, 
    CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| folder | String | مجلد للبحث عن الرسائل فيه. |
| pageInfo | PageInfo | معلومات الصفحة |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)يحتوي على رسائل من المجلد المحدد.

### أنظر أيضا

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->