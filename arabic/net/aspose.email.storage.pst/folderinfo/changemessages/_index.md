---
title: ChangeMessages
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يغير الرسائل الموجودة في المجلد .
type: docs
weight: 200
url: /ar/net/aspose.email.storage.pst/folderinfo/changemessages/
---
## ChangeMessages(IEnumerable&lt;string&gt;, MapiPropertyCollection) {#changemessages_1}

يغير الرسائل الموجودة في المجلد .

```csharp
public void ChangeMessages(IEnumerable<string> entryIdCollection, 
    MapiPropertyCollection updatedProperties)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| entryIdCollection | IEnumerable`1 | مجموعة معرف الإدخال. |
| updatedProperties | MapiPropertyCollection | الخصائص المحدثة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | لم يتم تنفيذ تحرير إصدار ملف ANSI. |
| InvalidOperationException | PST مفتوح للقراءة فقط. or معرف الإدخال غير صحيح . |
| ArgumentNullException | entryIdCollection ؛ لا يمكن أن تكون مجموعة معرفات الإدخال خالية . or updatedProperties ؛ لا يمكن أن تكون مجموعة الخصائص خالية. |

### أنظر أيضا

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection)
* class [FolderInfo](../../folderinfo)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../folderinfo)
* المجسم [Aspose.Email](../../../)

---

## ChangeMessages(MapiPropertyCollection) {#changemessages}

يغير كل الرسائل في المجلد .

```csharp
public void ChangeMessages(MapiPropertyCollection updatedProperties)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| updatedProperties | MapiPropertyCollection | الخصائص المحدثة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | لم يتم تنفيذ تحرير إصدار ملف ANSI. |
| InvalidOperationException | PST مفتوح للقراءة فقط. or معرف الإدخال غير صحيح . |
| ArgumentNullException | entryIdCollection ؛ لا يمكن أن تكون مجموعة معرفات الإدخال خالية . or updatedProperties ؛ لا يمكن أن تكون مجموعة الخصائص خالية. |

### أنظر أيضا

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection)
* class [FolderInfo](../../folderinfo)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../folderinfo)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->