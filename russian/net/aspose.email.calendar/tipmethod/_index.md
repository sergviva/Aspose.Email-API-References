---
title: TIPMethod
second_title: Справочник по Aspose.Email для .NET API
description: Определяет методы iTIP iCalendar Transport-Independent Interoperability Protocol связанные с объектом.
type: docs
weight: 890
url: /ru/net/aspose.email.calendar/tipmethod/
---
## TIPMethod enumeration

Определяет методы iTIP (iCalendar Transport-Independent Interoperability Protocol), связанные с объектом.

```csharp
public enum TIPMethod
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| None | `0` | Метод не определен. |
| Publish | `1` | Сообщение об объекте. Используется в основном как метод объявления о существовании объекта. |
| Request | `2` | Назначить объект. Это явное назначение одному или нескольким пользователям календаря. Метод REQUEST также используется для обновления или изменения существующего объекта. Клиенты, которые не могут обрабатывать REQUEST, МОГУТ ухудшить метод, чтобы рассматривать его как PUBLISH. |
| Reply | `3` | Ответ на запрос объекта. |
| Add | `4` | Добавить один или несколько экземпляров к существующему объекту. |
| Cancel | `5` | Отменить один или несколько экземпляров существующего объекта. |
| Refresh | `6` | Запрос, отправленный организатору объектов с просьбой предоставить последнюю версию объекта. |
| Counter | `7` | Противодействовать ЗАПРОСУ альтернативным предложением. |
| DeclineCounter | `8` | Отклонить встречное предложение Участника. |

### Смотрите также

* пространство имен [Aspose.Email.Calendar](../../aspose.email.calendar)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->