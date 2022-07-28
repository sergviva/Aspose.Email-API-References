---
title: Save
second_title: Справочник по Aspose.Email для .NET API
description: Сохраняет текущий объект сообщения в указанный файл.
type: docs
weight: 70
url: /ru/net/aspose.email.mapi.msg/messageobject/save/
---
## Save(string, MessageObjectSaveFormat) {#save_1}

Сохраняет текущий объект сообщения в указанный файл.

```csharp
public void Save(string fileName, MessageObjectSaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| format | MessageObjectSaveFormat | Формат выходных данных. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Если значение*format*недопустимо. |

### Примечания

Кроме того, может быть выброшен тот же набор исключений, что и дляString)вызов.

### Смотрите также

* enum [MessageObjectSaveFormat](../../messageobjectsaveformat)
* class [MessageObject](../../messageobject)
* пространство имен [Aspose.Email.Mapi.Msg](../../messageobject)
* сборка [Aspose.Email](../../../)

---

## Save(Stream, MessageObjectSaveFormat) {#save}

Сохраняет текущий объект сообщения в указанный поток.

```csharp
public void Save(Stream stream, MessageObjectSaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для записи. |
| format | MessageObjectSaveFormat | Формат выходных данных. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Если*stream*равно null. |
| ArgumentOutOfRangeException | Если значение*format*недопустимо. |

### Смотрите также

* enum [MessageObjectSaveFormat](../../messageobjectsaveformat)
* class [MessageObject](../../messageobject)
* пространство имен [Aspose.Email.Mapi.Msg](../../messageobject)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->