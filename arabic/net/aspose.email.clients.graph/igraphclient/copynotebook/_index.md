---
title: CopyNotebook
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: نسخ دفتر ملاحظات إلى مجلد دفاتر الملاحظات في مكتبة المستندات الوجهة. يتم إنشاء المجلد إذا لم يكن موجودًا. بالنسبة لعمليات النسخ  يمكنك اتباع نمط استدعاء غير متزامن قم أولاً باستدعاء إجراء النسخ  ثم استقصاء نقطة نهاية العملية للنتيجة. واجهة برمجة التطبيقات هذه . تفويض حساب العمل أو المدرسة Notes.Create Notes.ReadWrite Notes.ReadWrite.All المفوض حساب Microsoft الشخصي
type: docs
weight: 100
url: /ar/net/aspose.email.clients.graph/igraphclient/copynotebook/
---
## IGraphClient.CopyNotebook method

نسخ دفتر ملاحظات إلى مجلد دفاتر الملاحظات في مكتبة المستندات الوجهة. يتم إنشاء المجلد إذا لم يكن موجودًا. بالنسبة لعمليات النسخ ، يمكنك اتباع نمط استدعاء غير متزامن: قم أولاً باستدعاء إجراء النسخ ، ثم استقصاء نقطة نهاية العملية للنتيجة. واجهة برمجة التطبيقات هذه . تفويض (حساب العمل أو المدرسة) Notes.Create، Notes.ReadWrite، Notes.ReadWrite.All المفوض (حساب Microsoft الشخصي)

```csharp
public string CopyNotebook(string itemId, string groupId, string renameAs)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| itemId | String | معرف العنصر المراد نسخه |
| groupId | String | معرّف المجموعة المراد النسخ إليها. استخدمه فقط عند النسخ إلى مجموعة Office 365. |
| renameAs | String | اسم النسخة. افتراضات على اسم العنصر الموجود. |

### قيمة الإرجاع

في حالة النجاح ، تُرجع هذه الطريقة سلسلة موقع العملية. يمكنك استخدام هذه القيمة للحصول على حالة العملية.

### أنظر أيضا

* interface [IGraphClient](../../igraphclient)
* مساحة الاسم [Aspose.Email.Clients.Graph](../../igraphclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->