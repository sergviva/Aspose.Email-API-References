---
title: ReadNextMessage
second_title: Referencia de la API de Aspose.Email para .NET
description: Lee el siguiente mensaje del flujo de almacenamiento subyacente.
type: docs
weight: 70
url: /es/net/aspose.email.storage.mbox/mboxstoragereader/readnextmessage/
---
## ReadNextMessage() {#readnextmessage}

Lee el siguiente mensaje del flujo de almacenamiento subyacente.

```csharp
public abstract MailMessage ReadNextMessage()
```

### Valor_devuelto

A[`MailMessage`](../../../aspose.email/mailmessage) objeto si se puede leer o **nulo** si no hay más mensajes disponibles.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [MboxStorageReader](../../mboxstoragereader)
* espacio de nombres [Aspose.Email.Storage.Mbox](../../mboxstoragereader)
* asamblea [Aspose.Email](../../../)

---

## ReadNextMessage(out string) {#readnextmessage_1}

Lee el siguiente mensaje del flujo de almacenamiento subyacente.

```csharp
public abstract MailMessage ReadNextMessage(out string fromMarker)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fromMarker | String& | Obtiene el marcador From mientras analiza el archivo de almacenamiento MBox. |

### Valor_devuelto

A[`MailMessage`](../../../aspose.email/mailmessage) objeto si se puede leer o **nulo** si no hay más mensajes disponibles.

### Ver también

* class [MailMessage](../../../aspose.email/mailmessage)
* class [MboxStorageReader](../../mboxstoragereader)
* espacio de nombres [Aspose.Email.Storage.Mbox](../../mboxstoragereader)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->