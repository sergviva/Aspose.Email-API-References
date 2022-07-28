---
title: MapiTaskFlags
second_title: Справочник по Aspose.Email для .NET API
description: Содержит флаги индикации объекта Задача.
type: docs
weight: 18660
url: /ru/net/aspose.email.mapi/mapitaskflags/
---
## MapiTaskFlags enumeration

Содержит флаги индикации объекта Задача.

```csharp
[Flags]
public enum MapiTaskFlags
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Complete | `1` | Указывает, выполнена ли задача. |
| Accepted | `2` | Указывает, ответил ли ответственный за задачу на запрос задачи для этого объекта Task. |
| Updates | `4` | Указывает, запрашивался ли у исполнителя задачи отправка обновления задачи при изменении назначенного объекта Task. |
| Recurring | `8` | Указывает, включает ли задача шаблон повторения. |
| StatusOnComplete | `10` | Указывает, запрашивался ли у исполнителя задачи отправка обновленного сообщения электронной почты, когда исполнитель задачи завершает назначенную задачу. |
| DeadOccurrence | `20` | Указывает, нужно ли генерировать новые вхождения . |
| ResetReminder | `40` | Указывает, нужны ли будущим экземплярам повторяющихся задач напоминания. |

### Смотрите также

* пространство имен [Aspose.Email.Mapi](../../aspose.email.mapi)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->