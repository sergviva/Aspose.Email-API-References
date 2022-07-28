---
title: SaveMessage
second_title: Referencia de la API de Aspose.Email para .NET
description: Guarda el mensaje de correo especificado por el uri en el sistema de archivos local. El archivo de mensajes de correo tiene un formato compatible con RFC 822 EML.  si desea analizar los archivos de mensajes de correo utiliceMailMessageaspose.email/mailmessage.
type: docs
weight: 360
url: /es/net/aspose.email.clients.exchange.dav/exchangeclient/savemessage/
---
## SaveMessage(string, string) {#savemessage_1}

Guarda el mensaje de correo especificado por el uri en el sistema de archivos local. El archivo de mensajes de correo tiene un formato compatible con RFC 822 (EML).  si desea analizar los archivos de mensajes de correo, utilice[`MailMessage`](../../../aspose.email/mailmessage).

```csharp
public void SaveMessage(string messageUri, string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageUri | String | El Uri del mensaje de correo |
| path | String | La ruta de destino para guardar el mensaje. |

### Ver también

* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## SaveMessage(string, Stream) {#savemessage}

Guarda el mensaje.

```csharp
public void SaveMessage(string messageUri, Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageUri | String | URI del mensaje. |
| stream | Stream | La corriente. |

### Ver también

* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->