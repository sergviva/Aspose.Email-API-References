---
title: BodyPart
second_title: Referencia de la API de Aspose.Email para .NET
description: Especifica detalles sobre la parte del mensaje de un correo electrónico en una respuesta. El elemento BodyPart DEBE incluirse en una respuesta de comando cuando se especifica BodyPartPreference en una solicitud.
type: docs
weight: 1040
url: /es/net/aspose.email.clients.activesync.transportlayer/bodypart/
---
## BodyPart class

Especifica detalles sobre la parte del mensaje de un correo electrónico en una respuesta. El elemento BodyPart DEBE incluirse en una respuesta de comando cuando se especifica BodyPartPreference en una solicitud.

```csharp
public class BodyPart
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BodyPart](bodypart)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Data](../../aspose.email.clients.activesync.transportlayer/bodypart/data) { get; set; } | El contenido del elemento de datos es una cadena en el formato especificado por la propiedad Tipo. Si el valor del Tipo es RTF, el valor del elemento Datos se codifica utilizando la codificación base64. Si la propiedad Truncado se establece en verdadero, los datos del elemento Datos se truncan. La propiedad EstimatedDataSize proporciona una estimación aproximada del tamaño real del contenido completo de la cadena de datos. |
| [EstimatedDataSize](../../aspose.email.clients.activesync.transportlayer/bodypart/estimateddatasize) { get; set; } | Especifica una estimación informativa del tamaño de los datos asociados con el elemento principal. El elemento de tamaño de datos estimado DEBE presentarse siempre que el elemento truncado se establezca en TRUE |
| [Preview](../../aspose.email.clients.activesync.transportlayer/bodypart/preview) { get; set; } | Contiene el mensaje de texto sin formato Unicode o la vista previa parcial del mensaje devuelta al cliente. |
| [Status](../../aspose.email.clients.activesync.transportlayer/bodypart/status) { get; set; } | Contiene un código y descripción que indica el éxito o fracaso de la operación |
| [Truncated](../../aspose.email.clients.activesync.transportlayer/bodypart/truncated) { get; set; } | Especifica si el cuerpo del elemento se ha truncado de acuerdo con el elemento BodyPreference indicado por el cliente. Si el valor es TRUE, entonces el cuerpo del elemento se ha truncado. Si el valor es FALSO o la propiedad Truncado no está configurada, entonces el cuerpo del elemento no se ha truncado. |
| [Type](../../aspose.email.clients.activesync.transportlayer/bodypart/type) { get; set; } | Especifica el tipo de formato del contenido del cuerpo del elemento. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->