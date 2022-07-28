---
title: AutodiscoverServiceBase
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل ارتباطًا مجردًا لخدمة الاكتشاف التلقائي.
type: docs
weight: 3100
url: /ar/net/aspose.email.clients.exchange/autodiscoverservicebase/
---
## AutodiscoverServiceBase class

يمثل ارتباطًا مجردًا لخدمة الاكتشاف التلقائي.

```csharp
public abstract class AutodiscoverServiceBase
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | الحصول على أو تعيين قيمة تشير إلى وجوب قبول تشفير ضغط GZip . |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | الحصول على معرف الطلب للطلب أو تعيينه. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | الحصول على أو تحديد اسم مجموعة الاتصال للطلب. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | الحصول على أو تعيين حاوية ملفات تعريف الارتباط. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | الحصول على أو تعيين بيانات الاعتماد المستخدمة للمصادقة مع خدمات Exchange عبر الويب. يؤدي تعيين بيانات الاعتماد property إلى تعيين UseDefaultCredentials تلقائيًا إلى false. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | الحصول على مجموعة من رؤوس HTTP التي سيتم إرسالها مع كل طلب إلى EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | الحصول على مجموعة من رؤوس HTTP من الاستجابة الأخيرة. |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | يحصل أو يحدد ما إذا كان يجب أن يحتوي الطلب إلى مورد الإنترنت على رأس اتصال HTTP بالقيمة Keep-life |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | الحصول على أو تعيين اسم ملف السجل |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب إجراء المصادقة المسبقة لـ HTTP . |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | يحصل على إصدار الخادم المطلوب. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | الحصول على علامة أو تعيينها للإشارة إلى ما إذا كان العميل يتطلب من جانب الخادم إعادة معرف الطلب. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت معلومات وقت استجابة العميل تدفع إلى الخادم. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | الحصول على المعلومات المرتبطة بالخادم الذي قام بمعالجة الطلب الأخير. سيكون فارغًا إذا لم تتم معالجة أي طلبات . |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | الحصول على أو تعيين المهلة المستخدمة عند إرسال طلبات HTTP وعند تلقي استجابات HTTP ، بالمللي ثانية. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | الحصول على القيمة أو تعيينها والتي تشير إلى ما إذا كان يجب استخدام التاريخ في اسم ملف السجل. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب استخدام بيانات اعتماد المستخدم الذي قام بتسجيل الدخول حاليًا إلى Windows للمصادقة مع خدمات Exchange عبر الويب. يؤدي تعيين UseDefaultCredentials إلى true تلقائيًا إلى تعيين الخاصية Credentials إلى قيمة خالية. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | الحصول على وكيل المستخدم أو تعيينه. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | الحصول على أو تعيين وكيل الويب الذي يجب استخدامه عند إرسال الطلبات إلى EWS . اضبط هذه الخاصية على قيمة خالية لاستخدام وكيل الويب الافتراضي. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->