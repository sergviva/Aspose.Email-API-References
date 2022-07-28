---
title: ResolveRecipientsAvailabilityRequest
second_title: Referencia de la API de Aspose.Email para .NET
description: Indica al servidor que el cliente está solicitando datos de disponibilidad e identifica la hora de inicio y finalización de los datos de disponibilidad para recuperar. La disponibilidad no es compatible cuando la versión del protocolo es 12.1.
type: docs
weight: 1820
url: /es/net/aspose.email.clients.activesync.transportlayer/resolverecipientsavailabilityrequest/
---
## ResolveRecipientsAvailabilityRequest class

Indica al servidor que el cliente está solicitando datos de disponibilidad e identifica la hora de inicio y finalización de los datos de disponibilidad para recuperar. La disponibilidad no es compatible cuando la versión del protocolo es 12.1.

```csharp
public class ResolveRecipientsAvailabilityRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ResolveRecipientsAvailabilityRequest](resolverecipientsavailabilityrequest)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EndTime](../../aspose.email.clients.activesync.transportlayer/resolverecipientsavailabilityrequest/endtime) { get; set; } | Identifica el final del período de tiempo libre/ocupado solicitado por el cliente. EndTime no es compatible cuando la versión del protocolo es 12.1. Si el cliente envía un valor de EndTime no válido, el servidor devuelve un valor de Estado de 5 en la respuesta del comando ResolveRecipients. Si no se incluye EndTime en una solicitud de disponibilidad, el servidor utiliza un valor de hora de finalización predeterminado de siete días después del valor de StartTime. Si el valor de EndTime especificado en la solicitud es menor que el valor de StartTime más 30 minutos, o si la duración abarcada por el valor de StartTime y el valor de EndTime es mayor que una cantidad específica de días, el servidor devuelve un valor de Estado de 5 en la respuesta del comando ResolveRecipients. Exchange 2010 y Exchange 2013 usan 42 días; Exchange 2007 SP1 usa 62 días. |
| [StartTime](../../aspose.email.clients.activesync.transportlayer/resolverecipientsavailabilityrequest/starttime) { get; set; } | Identifica el inicio del período de tiempo libre/ocupado solicitado por el cliente. StartTime no se admite cuando la versión del protocolo es 12.1. Si la disponibilidad está incluida en la solicitud, esta también DEBE incluir StartTime y EndTime. Si el cliente envía un valor de Hora de inicio no válido, el servidor devuelve un valor de Estado de 5 en la respuesta del comando ResolveRecipients. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->