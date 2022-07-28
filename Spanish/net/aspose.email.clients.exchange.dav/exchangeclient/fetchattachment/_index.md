---
title: FetchAttachment
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene el archivo adjunto
type: docs
weight: 160
url: /es/net/aspose.email.clients.exchange.dav/exchangeclient/fetchattachment/
---
## ExchangeClient.FetchAttachment method

Obtiene el archivo adjunto

```csharp
public Attachment FetchAttachment(string attachmentUri)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| attachmentUri | String | El URI del archivo adjunto. (El URI del archivo adjunto se puede recuperar usando el método ListMessages(folder, ExchangeListMessagesOptions.FetchAttachmentInformation)) |

### Valor_devuelto

[`Attachment`](../../../aspose.email/attachment) que representa un archivo adjunto obtenido

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *attachmentUri* es nulo o vacío |

### Ver también

* class [Attachment](../../../aspose.email/attachment)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->