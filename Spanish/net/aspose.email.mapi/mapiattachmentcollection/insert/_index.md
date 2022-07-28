---
title: Insert
second_title: Referencia de la API de Aspose.Email para .NET
description: Inserta un elemento en elCollection en el índice especificado.
type: docs
weight: 30
url: /es/net/aspose.email.mapi/mapiattachmentcollection/insert/
---
## Insert(int, MapiAttachment) {#insert}

Inserta un elemento en elCollection en el índice especificado.

```csharp
public void Insert(int index, MapiAttachment item)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero en el que*item* debe insertarse. |
| item | MapiAttachment | El objeto a insertar. El valor puede ser nulo para los tipos de referencia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *index* es menor que cero. |

### Ver también

* class [MapiAttachment](../../mapiattachment)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* espacio de nombres [Aspose.Email.Mapi](../../mapiattachmentcollection)
* asamblea [Aspose.Email](../../../)

---

## Insert(int, string, MapiMessage) {#insert_2}

Inserta un mensaje como archivo adjunto en el[`MapiAttachmentCollection`](../../mapiattachmentcollection) en el índice especificado.

```csharp
public void Insert(int index, string name, MapiMessage msg)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero en el que se debe insertar. |
| name | String | El nombre del archivo adjunto. |
| msg | MapiMessage | los[`MapiMessage`](../../mapimessage)que representa el mensaje adjunto. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | lanza si el mensaje es nulo. |

### Ver también

* class [MapiMessage](../../mapimessage)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* espacio de nombres [Aspose.Email.Mapi](../../mapiattachmentcollection)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->