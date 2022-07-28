---
title: AppendMessageAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تحميل رسالة البريد إلى المجلد المحدد
type: docs
weight: 20
url: /ar/net/aspose.email.clients.imap/iasyncimapclient/appendmessageasync/
---
## IAsyncImapClient.AppendMessageAsync method

تحميل رسالة البريد إلى المجلد المحدد

```csharp
public Task<string> AppendMessageAsync(MailMessage message, string folderName = null, 
    IConnection connection = null, CancellationToken token = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| connection | MailMessage | الاتصال بالخادم |
| folderName | String | المجلد الذي سيتلقى رسالة البريد |
| message | IConnection | رسالة البريد المراد تحميلها |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن المهمة ، مع المفوض لهذه العملية

### أنظر أيضا

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->