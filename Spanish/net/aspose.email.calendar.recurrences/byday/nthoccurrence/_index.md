---
title: NthOccurrence
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene o establece la enésima aparición del día de la semana.
type: docs
weight: 40
url: /es/net/aspose.email.calendar.recurrences/byday/nthoccurrence/
---
## ByDay.NthOccurrence property

Obtiene o establece la enésima aparición del día de la semana.

```csharp
public int NthOccurrence { get; set; }
```

### Observaciones

El rango válido para esta propiedad es de -53 a 53.

Los valores positivos representan la enésima ocurrencia desde el comienzo del período, por ejemplo, NthOccurrence = 1, representa la primera ocurrencia del día de la semana.

Los valores negativos representan la enésima aparición desde el final del período, por ejemplo, NthOccurrence = -1, representa la última aparición del día de la semana.

Cuando NthOccurrence es cero, representa todas las ocurrencias del día especificado de la semana. Por ejemplo, BYDAY=MO tiene NthOccurrence cero y representa todos los lunes del conjunto.

### Ver también

* class [ByDay](../../byday)
* espacio de nombres [Aspose.Email.Calendar.Recurrences](../../byday)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->