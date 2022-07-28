---
title: Add
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: إضافة المرفق الجديد كرسالة مضمنة.
type: docs
weight: 20
url: /ar/net/aspose.email.mapi/mapiattachmentcollection/add/
---
## Add(string, MapiMessage) {#add_2}

إضافة المرفق الجديد كرسالة مضمنة.

```csharp
public void Add(string name, MapiMessage msg)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم المرفق. |
| msg | MapiMessage | ال[`MapiMessage`](../../mapimessage)التي تمثل الرسالة المرفقة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | رميات إذا كانت الرسالة فارغة. |

### أنظر أيضا

* class [MapiMessage](../../mapimessage)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* مساحة الاسم [Aspose.Email.Mapi](../../mapiattachmentcollection)
* المجسم [Aspose.Email](../../../)

---

## Add(string, byte[]) {#add_3}

إضافة المرفق الجديد .

```csharp
public void Add(string name, byte[] data)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم المرفق. |
| data | Byte[] | بيانات المرفقات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | رميات إذا كان اسم المرفق فارغًا أو فارغًا. |
| ArgumentNullException | رميات إذا كانت بيانات المرفقات فارغة. |

### أنظر أيضا

* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* مساحة الاسم [Aspose.Email.Mapi](../../mapiattachmentcollection)
* المجسم [Aspose.Email](../../../)

---

## Add(MapiAttachment) {#add}

إضافة كائن إلى نهاية ملفCollection .

```csharp
public void Add(MapiAttachment item)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| item | MapiAttachment | الكائن المراد إضافته إلى نهاية ملفCollection. يمكن أن تكون القيمة خالية لأنواع المراجع. |

### أنظر أيضا

* class [MapiAttachment](../../mapiattachment)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* مساحة الاسم [Aspose.Email.Mapi](../../mapiattachmentcollection)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->