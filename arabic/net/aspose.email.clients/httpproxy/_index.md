---
title: HttpProxy
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: عميل وكيل HTTP.
type: docs
weight: 16120
url: /ar/net/aspose.email.clients/httpproxy/
---
## HttpProxy class

عميل وكيل HTTP.

```csharp
public class HttpProxy : Proxy, IWebProxy
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [HttpProxy](httpproxy#constructor)(string, int) | يقوم بتهيئة مثيل جديد لملف[`HttpProxy`](../httpproxy) فئة للاتصال بالخادم الوكيل بدون مصادقة. |
| [HttpProxy](httpproxy#constructor_1)(string, int, string, string) | يقوم بتهيئة مثيل جديد لملف[`HttpProxy`](../httpproxy) فئة للاتصال بالخادم الوكيل باستخدام اسم مستخدم وكلمة مرور محددين. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Address](../../aspose.email.clients/proxy/address) { get; set; } | اسم المجال أو عنوان IP للخادم الوكيل |
| [Credentials](../../aspose.email.clients/httpproxy/credentials) { get; set; } | بيانات الاعتماد لإرسالها إلى الخادم الوكيل للمصادقة. |
| [Password](../../aspose.email.clients/proxy/password) { get; set; } | كلمة المرور لمصادقة الوكيل |
| [Port](../../aspose.email.clients/proxy/port) { get; set; } | رقم المنفذ للخادم الوكيل |
| [SupportedAuthenticationMethods](../../aspose.email.clients/httpproxy/supportedauthenticationmethods) { get; set; } | طرق المصادقة المدعومة للاتصال بـ HTTP proxy |
| [Username](../../aspose.email.clients/proxy/username) { get; set; } | اسم المستخدم لمصادقة الوكيل |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/proxy/dispose)() | التخلص من هذا المثيل وطلب إغلاق اتصال TCP الأساسي. |
| virtual [GetProxy](../../aspose.email.clients/httpproxy/getproxy)(Uri) | إرجاع URI لوكيل . |
| [GetStream](../../aspose.email.clients/proxy/getstream)(string, int) | إرجاع دفق الشبكة المكون لنقل البيانات إلى المضيف المطلوب من خلال الخادم الوكيل. |
| virtual [IsBypassed](../../aspose.email.clients/httpproxy/isbypassed)(Uri) | يشير إلى أنه لا يجب استخدام الوكيل للمضيف المحدد. |
| override [SetUpStream](../../aspose.email.clients/httpproxy/setupstream)(Stream, string, int) | تكوين الخادم الوكيل لنقل البيانات إلى المضيف الهدف. |

### أنظر أيضا

* class [Proxy](../proxy)
* مساحة الاسم [Aspose.Email.Clients](../../aspose.email.clients)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->