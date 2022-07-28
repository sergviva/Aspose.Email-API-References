---
title: Save
second_title: Referencia de la API de Aspose.Email para .NET
description: Guarda el objeto de mensaje actual en el archivo especificado.
type: docs
weight: 70
url: /es/net/aspose.email.mapi.msg/messageobject/save/
---
## Save(string, MessageObjectSaveFormat) {#save_1}

Guarda el objeto de mensaje actual en el archivo especificado.

```csharp
public void Save(string fileName, MessageObjectSaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileName | String | Nombre del archivo. |
| format | MessageObjectSaveFormat | El formato de los datos de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | Si*format* el valor no es válido. |

### Observaciones

Además, se podría lanzar el mismo conjunto de excepciones que para elString) llamar.

### Ver también

* enum [MessageObjectSaveFormat](../../messageobjectsaveformat)
* class [MessageObject](../../messageobject)
* espacio de nombres [Aspose.Email.Mapi.Msg](../../messageobject)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream, MessageObjectSaveFormat) {#save}

Guarda el objeto de mensaje actual en el flujo especificado.

```csharp
public void Save(Stream stream, MessageObjectSaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia en la que escribir. |
| format | MessageObjectSaveFormat | El formato de los datos de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Si*stream* es nulo. |
| ArgumentOutOfRangeException | Si*format* el valor no es válido. |

### Ver también

* enum [MessageObjectSaveFormat](../../messageobjectsaveformat)
* class [MessageObject](../../messageobject)
* espacio de nombres [Aspose.Email.Mapi.Msg](../../messageobject)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->