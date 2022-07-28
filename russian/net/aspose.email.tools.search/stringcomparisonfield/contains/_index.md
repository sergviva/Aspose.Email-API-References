---
title: Contains
second_title: Справочник по Aspose.Email для .NET API
description: Указывает что поле в сообщении должно содержать указанное значение.
type: docs
weight: 10
url: /ru/net/aspose.email.tools.search/stringcomparisonfield/contains/
---
## Contains(string) {#contains}

Указывает, что поле в сообщении должно содержать указанное значение.

```csharp
public MailQuery Contains(string value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | String | Значение. |

### Возвращаемое значение

[`MailQuery`](../../mailquery), представляющий поисковый запрос (один критерий поиска).

### Смотрите также

* class [MailQuery](../../mailquery)
* class [StringComparisonField](../../stringcomparisonfield)
* пространство имен [Aspose.Email.Tools.Search](../../stringcomparisonfield)
* сборка [Aspose.Email](../../../)

---

## Contains(string, bool) {#contains_1}

Указывает, что поле в сообщении должно содержать указанное значение.

```csharp
public MailQuery Contains(string value, bool ignoreCase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | String | Значение. |
| ignoreCase | Boolean | true, чтобы игнорировать регистр при сравнении; в противном случае ложно. |

### Возвращаемое значение

[`MailQuery`](../../mailquery), представляющий поисковый запрос (один критерий поиска).

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | value;Значение поля не должно быть нулевым или пустым |

### Смотрите также

* class [MailQuery](../../mailquery)
* class [StringComparisonField](../../stringcomparisonfield)
* пространство имен [Aspose.Email.Tools.Search](../../stringcomparisonfield)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->