---
title: MailPrinter
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل طابعة لرسائل البريد .
type: docs
weight: 19870
url: /ar/net/aspose.email.printing/mailprinter/
---
## MailPrinter class

يمثل طابعة لرسائل البريد .

```csharp
public sealed class MailPrinter : IPrintSettingsProvider
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MailPrinter](mailprinter#constructor)() | يقوم بتهيئة مثيل جديد لملف[`MailPrinter`](../mailprinter) فئة مع إعداد ورق A4 لحجم الصفحة وهامش 0.5 بوصة لجميع الجوانب. |
| [MailPrinter](mailprinter#constructor_1)(IPrintSettingsProvider) | يقوم بتهيئة مثيل جديد لملف[`MailPrinter`](../mailprinter) فئة باستخدام مزود إعدادات معين. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CultureName](../../aspose.email.printing/mailprinter/culturename) { get; set; } | الحصول على اسم الثقافة أو تعيينه بالتنسيق languageagecode2-country / regioncode2. |
| [DpiX](../../aspose.email.printing/mailprinter/dpix) { get; set; } | الحصول على أو تعيين DPI الأفقي. |
| [DpiY](../../aspose.email.printing/mailprinter/dpiy) { get; set; } | الحصول على أو تعيين DPI الرأسي . |
| [FormattingFlags](../../aspose.email.printing/mailprinter/formattingflags) { get; set; } | الحصول على أو تعيين خيارات الطابعة. |
| [MarginBottom](../../aspose.email.printing/mailprinter/marginbottom) { get; set; } | الحصول على الهامش السفلي أو تحديده . |
| [MarginLeft](../../aspose.email.printing/mailprinter/marginleft) { get; set; } | الحصول على أو تحديد الهامش الأيسر . |
| [MarginRight](../../aspose.email.printing/mailprinter/marginright) { get; set; } | الحصول على الهامش الصحيح أو تحديده . |
| [MarginTop](../../aspose.email.printing/mailprinter/margintop) { get; set; } | الحصول على الهامش العلوي أو تحديده . |
| [PageHeight](../../aspose.email.printing/mailprinter/pageheight) { get; set; } | الحصول على ارتفاع الصفحة أو تحديده . |
| [PageUnit](../../aspose.email.printing/mailprinter/pageunit) { get; set; } | الحصول على وحدة الصفحة أو تعيينها. |
| [PageWidth](../../aspose.email.printing/mailprinter/pagewidth) { get; set; } | الحصول على عرض الصفحة أو تحديده . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Print](../../aspose.email.printing/mailprinter/print#print)(MailMessage, Stream, PrintFormat) | يطبع كائن الرسالة المحدد باستخدام التنسيق المطلوب. |
| [Print](../../aspose.email.printing/mailprinter/print#print_1)(MailMessage, string, PrintFormat) | يطبع كائن الرسالة المحدد باستخدام التنسيق المطلوب. |
| [Print](../../aspose.email.printing/mailprinter/print#print_2)(MapiMessage, Stream, PrintFormat) | يطبع كائن MSG المحدد باستخدام التنسيق المطلوب. |
| [Print](../../aspose.email.printing/mailprinter/print#print_3)(MapiMessage, string, PrintFormat) | يطبع كائن MSG المحدد باستخدام التنسيق المطلوب. |

### أنظر أيضا

* interface [IPrintSettingsProvider](../iprintsettingsprovider)
* مساحة الاسم [Aspose.Email.Printing](../../aspose.email.printing)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->