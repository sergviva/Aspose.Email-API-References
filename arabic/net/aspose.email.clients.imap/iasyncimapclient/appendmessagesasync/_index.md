---
title: AppendMessagesAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تحميل رسائل البريد إلى المجلد الحالي
type: docs
weight: 30
url: /ar/net/aspose.email.clients.imap/iasyncimapclient/appendmessagesasync/
---
## IAsyncImapClient.AppendMessagesAsync method

تحميل رسائل البريد إلى المجلد الحالي

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    string folderName = null, IConnection connection = null, CancellationToken token = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | IEnumerable`1 | الاتصال بالخادم |
| folderName | String | المجلد الذي سيتلقى رسالة البريد |
| messages | IConnection | تعداد رسائل البريد الإلكتروني المراد تحميلها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->