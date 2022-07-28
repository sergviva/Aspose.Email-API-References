---
title: AccountId
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحدد الحساب الذي يتم إرسال بريد إلكتروني منه . إذا كان AccountId فارغًا  يرسل الخادم البريد الإلكتروني باستخدام الحساب المحدد بواسطة الإعدادات PrimarySmtpAddress الذي تم إرجاعه في استجابة أمر الإعدادات . إذا تم تضمين AccountId في الطلب  فإن القيمة يجب أن يساوي أحد الإعدادات قيم عنصر AccountId المضمنة في استجابة أمر الإعدادات . يجب أن يتحقق الخادم من أن قيمة عنصر AccountId المقدمة صالحة لإرسال البريد الإلكتروني. يتم إرجاع قيمة الحالة 166 إذا كانت قيمة عنصر AccountId غير صالحة. يتم إرجاع قيمة عنصر الحالة 167 إذا كان الحساب لا يدعم إرسال البريد الإلكتروني . ملاحظة يرسل الخادم البريد الإلكتروني باستخدام الحساب المحدد بواسطة AccountId  وليس الحساب المحدد بواسطة From . لا يتم دعم عنصر AccountId عند إصدار البروتوكول هو 12.1 أو 14.0. يقوم Exchange 2007 بإرجاع قيمة الحالة 103 إذا تم تضمين عنصر AccountId في طلب أمر SendMail أو طلب أمر SmartForward أو طلب أمر SmartReply.
type: docs
weight: 20
url: /ar/net/aspose.email.clients.activesync.transportlayer/smartrequest/accountid/
---
## SmartRequest.AccountId property

يحدد الحساب الذي يتم إرسال بريد إلكتروني منه . إذا كان AccountId فارغًا ، يرسل الخادم البريد الإلكتروني باستخدام الحساب المحدد بواسطة الإعدادات: PrimarySmtpAddress الذي تم إرجاعه في استجابة أمر الإعدادات . إذا تم تضمين AccountId في الطلب ، فإن القيمة يجب أن يساوي أحد الإعدادات: قيم عنصر AccountId المضمنة في استجابة أمر الإعدادات . يجب أن يتحقق الخادم من أن قيمة عنصر AccountId المقدمة صالحة لإرسال البريد الإلكتروني. يتم إرجاع قيمة الحالة 166 إذا كانت قيمة عنصر AccountId غير صالحة. يتم إرجاع قيمة عنصر الحالة 167 إذا كان الحساب لا يدعم إرسال البريد الإلكتروني . ملاحظة يرسل الخادم البريد الإلكتروني باستخدام الحساب المحدد بواسطة AccountId ، وليس الحساب المحدد بواسطة From . لا يتم دعم عنصر AccountId عند إصدار البروتوكول هو 12.1 أو 14.0. يقوم Exchange 2007 بإرجاع قيمة الحالة 103 إذا تم تضمين عنصر AccountId في طلب أمر SendMail أو طلب أمر SmartForward أو طلب أمر SmartReply.

```csharp
public string AccountId { get; set; }
```

### أنظر أيضا

* class [SmartRequest](../../smartrequest)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../smartrequest)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->