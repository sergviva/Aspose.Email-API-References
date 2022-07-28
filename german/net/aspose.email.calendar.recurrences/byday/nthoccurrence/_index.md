---
title: NthOccurrence
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft das n-te Vorkommen des Wochentags ab oder legt es fest.
type: docs
weight: 40
url: /de/net/aspose.email.calendar.recurrences/byday/nthoccurrence/
---
## ByDay.NthOccurrence property

Ruft das n-te Vorkommen des Wochentags ab oder legt es fest.

```csharp
public int NthOccurrence { get; set; }
```

### Bemerkungen

Der gültige Bereich für diese Eigenschaft liegt zwischen -53 und 53.

Positive Werte stellen das N-te Vorkommen seit Beginn des Zeitraums dar, z. B. steht NthOccurrence = 1, für das erste Vorkommen des Wochentags.

Negative Werte stellen das N-te Vorkommen seit dem Ende des Zeitraums dar, beispielsweise stellt NthOccurrence = -1, das letzte Vorkommen des Wochentags dar.

Wenn NthOccurrence null ist, stellt es alle Vorkommen des angegebenen Wochentags dar. Beispiel: BYDAY=MO hat NthOccurrence null und repräsentiert alle Montage im Satz.

### Siehe auch

* class [ByDay](../../byday)
* namensraum [Aspose.Email.Calendar.Recurrences](../../byday)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->