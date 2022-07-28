---
title: To
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحدد مستلمًا ليتم حله . يمكن أن يصل طول قيمته إلى 256 حرفًا . إذا حدد العنصر إلى اسمًا غامضًا وتم تضمين التوفر في الطلب  فلن تتضمن الاستجابة بيانات التوفر / الانشغال لهذا المستخدم . يتم تضمين التوافر فقط عندما يتضمن العنصر إلى عنوان SMTP صالحًا أو اسمًا يتحول إلى فرد فريد على الخادم . نتيجة تضمين أكثر من 1000 عنصر في الطلب غير محددة. قد يُرجع الخادم خطأ حالة البروتوكول استجابةً لطلب الأمر هذا . إذا تضمن طلب الأمر ResolveRecipients التوفر  فيمكن تضمين 100 To كحد أقصى تحتوي على عناوين SMTP في الطلب. إذا تم تضمين أكثر من 100 عنوان SMTP في الطلب  فسيتم إرجاع قيمة الحالة 160 في الاستجابة . إذا كان طلب الأمر ResolveRecipients يتضمن التوفر ويتضمن عنصر To لمستخدم غامض  فإن الاستجابة لا تتضمن عنصر MergedFreeBusy لـ هذا المستخدم. فقط المستخدمون أو قوائم التوزيع المحددة بعناوين SMTP صالحة أو سلسلة يمكن تعريفها بشكل فريد في رسالة الطلب إلى عنصر تحتوي على عناصر MergedFreeBusy مضمنة في الاستجابة. يتم إرجاع بيانات التوفر كسلسلة واحدة تدمج البيانات للأعضاء الفرديين في مجموعة التوزيع. إذا كانت مجموعة التوزيع تحتوي على أكثر من 20 عضوًا  فسيتم إرجاع قيمة عنصر الحالة 161 في الاستجابة للإشارة إلى أن معلومات حالة الانشغال الحرة المدمجة لمجموعة التوزيع الكبيرة هذه ليست مفيدة.
type: docs
weight: 50
url: /ar/net/aspose.email.clients.activesync.transportlayer/resolverecipientsresponse/to/
---
## ResolveRecipientsResponse.To property

يحدد مستلمًا ليتم حله . يمكن أن يصل طول قيمته إلى 256 حرفًا . إذا حدد العنصر "إلى" اسمًا غامضًا وتم تضمين التوفر في الطلب ، فلن تتضمن الاستجابة بيانات التوفر / الانشغال لهذا المستخدم . يتم تضمين التوافر فقط عندما يتضمن العنصر "إلى" عنوان SMTP صالحًا أو اسمًا يتحول إلى فرد فريد على الخادم . نتيجة تضمين أكثر من 1000 عنصر في الطلب غير محددة. قد يُرجع الخادم خطأ حالة البروتوكول استجابةً لطلب الأمر هذا . إذا تضمن طلب الأمر ResolveRecipients التوفر ، فيمكن تضمين 100 To كحد أقصى تحتوي على عناوين SMTP في الطلب. إذا تم تضمين أكثر من 100 عنوان SMTP في الطلب ، فسيتم إرجاع قيمة الحالة 160 في الاستجابة . إذا كان طلب الأمر ResolveRecipients يتضمن التوفر ويتضمن عنصر To لمستخدم غامض ، فإن الاستجابة لا تتضمن عنصر MergedFreeBusy لـ هذا المستخدم. فقط المستخدمون أو قوائم التوزيع المحددة بعناوين SMTP صالحة أو سلسلة يمكن تعريفها بشكل فريد في رسالة الطلب إلى عنصر تحتوي على عناصر MergedFreeBusy مضمنة في الاستجابة. يتم إرجاع بيانات التوفر كسلسلة واحدة تدمج البيانات للأعضاء الفرديين في مجموعة التوزيع. إذا كانت مجموعة التوزيع تحتوي على أكثر من 20 عضوًا ، فسيتم إرجاع قيمة عنصر الحالة 161 في الاستجابة للإشارة إلى أن معلومات حالة الانشغال الحرة المدمجة لمجموعة التوزيع الكبيرة هذه ليست مفيدة.

```csharp
public string To { get; set; }
```

### أنظر أيضا

* class [ResolveRecipientsResponse](../../resolverecipientsresponse)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../resolverecipientsresponse)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->