---
title: SaveOptions
second_title: Referencia de la API de Aspose.Email para .NET
description: Esta es una clase base abstracta para clases que permiten al usuario especificar opciones adicionales al guardar un MailMessage en un formato particular.
type: docs
weight: 19970
url: /es/net/aspose.email/saveoptions/
---
## SaveOptions class

Esta es una clase base abstracta para clases que permiten al usuario especificar opciones adicionales al guardar un MailMessage en un formato particular.

```csharp
public abstract class SaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler) { get; set; } | Representa el método que normalmente proporciona el lado de la llamada y maneja los eventos de progreso. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype) { get; set; } | Representa el tipo de guardado del mensaje de correo. Puede estar en formato eml, msg (ASCII o Unicode), mhtml o html. El valor predeterminado es Eml. |
| static [DefaultEml](../../aspose.email/saveoptions/defaulteml) { get; } | Obtiene opciones con valores predeterminados para guardar el mensaje en formato EML. |
| static [DefaultHtml](../../aspose.email/saveoptions/defaulthtml) { get; } | Obtiene opciones con valores predeterminados para guardar el mensaje en formato HTML. |
| static [DefaultMhtml](../../aspose.email/saveoptions/defaultmhtml) { get; } | Obtiene opciones con valores predeterminados para guardar el mensaje en formato Mhtml. |
| static [DefaultMsg](../../aspose.email/saveoptions/defaultmsg) { get; } | Obtiene opciones con valores predeterminados para guardar el mensaje en formato Msg(ASCII). |
| static [DefaultMsgUnicode](../../aspose.email/saveoptions/defaultmsgunicode) { get; } | Obtiene opciones con valores predeterminados para guardar el mensaje en formato Msg (Unicode). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateSaveOptions](../../aspose.email/saveoptions/createsaveoptions)(MailMessageSaveType) | Crea un objeto de opciones de guardado de una clase adecuada para el tipo de guardado especificado. |

### Ver también

* espacio de nombres [Aspose.Email](../../aspose.email)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->