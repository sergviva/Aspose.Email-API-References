---
title: CopyConversationItems
second_title: Referencia de la API de Aspose.Email para .NET
description: Copia los elementos de conversación en la carpeta de destino especificada
type: docs
weight: 440
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems/
---
## CopyConversationItems(string, string) {#copyconversationitems}

Copia los elementos de conversación en la carpeta de destino especificada

```csharp
public void CopyConversationItems(string conversationId, string destinationFolderId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| conversationId | String | ID de conversación para copiar |
| destinationFolderId | String | ID de la carpeta en la que se copian los elementos |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId* es`nulo`o`vacío` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId* es`nulo`o`vacío` |

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## CopyConversationItems(string, string, string) {#copyconversationitems_1}

Copia los elementos de conversación, que se encuentran en la carpeta especificada, en la carpeta de destino especificada

```csharp
public void CopyConversationItems(string conversationId, string contextFolderId, 
    string destinationFolderId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| conversationId | String | ID de conversación para copiar |
| contextFolderId | String | ID de la carpeta en la que se encuentran los elementos de conversación. Nota: si está configurado como nulo (o vacío), se copiarán todos los elementos de conversación |
| destinationFolderId | String | ID de la carpeta en la que se copian los elementos |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId* es`nulo`o`vacío` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId* es`nulo`o`vacío` |

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->