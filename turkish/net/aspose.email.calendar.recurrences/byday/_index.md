---
title: ByDay
second_title: Aspose.Email for .NET API Referansı
description: Haftanın belirtilen gününün N. tekrarını veya tüm tekrarlarını temsil eder.
type: docs
weight: 640
url: /tr/net/aspose.email.calendar.recurrences/byday/
---
## ByDay class

Haftanın belirtilen gününün N. tekrarını (veya tüm tekrarlarını) temsil eder.

```csharp
public class ByDay
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ByDay](byday#constructor_1)(DayOfWeek) | ByDay sınıfının yeni bir örneğini başlatır. |
| [ByDay](byday#constructor)(int, DayOfWeek) | ByDay sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DayOfWeek](../../aspose.email.calendar.recurrences/byday/dayofweek) { get; set; } | Haftanın gününü alır veya ayarlar. |
| [IsAllOccurrences](../../aspose.email.calendar.recurrences/byday/isalloccurrences) { get; } | NthOccurrence sıfır olduğunda (haftanın bu gününün tüm oluşumları anlamına gelir) True döndürür. |
| [NthOccurrence](../../aspose.email.calendar.recurrences/byday/nthoccurrence) { get; set; } | Haftanın gününün n. oluşumunu alır veya ayarlar. |

### Notlar

Bir yineleme kuralının BYDAY bölümünde belirtilen haftanın bir gününe karşılık gelir.

Ay veya yıl içinde haftanın belirtilen gününün N. tekrarını (veya tüm tekrarlarını) belirtmek için aylık veya yıllık yineleme kuralında kullanılabilir.

BYDAY=MO, ayın veya yılın tüm Pazartesi günlerini temsil eder. Tüm oluşumları temsil etmek için NthOccurrence'ı 0 olarak ayarlayın.

BYDAY=2MO, bir ay veya yıldaki 2. Pazartesi gününü temsil eder.

BYDAY=-1MO, bir ayın veya yılın son Pazartesi gününü temsil eder.

### Ayrıca bakınız

* ad alanı [Aspose.Email.Calendar.Recurrences](../../aspose.email.calendar.recurrences)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->