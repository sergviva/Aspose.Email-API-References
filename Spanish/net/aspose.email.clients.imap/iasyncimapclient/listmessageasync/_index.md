---
title: ListMessageAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene información sobre un mensaje.
type: docs
weight: 230
url: /es/net/aspose.email.clients.imap/iasyncimapclient/listmessageasync/
---
## ListMessageAsync(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) {#listmessageasync}

Obtiene información sobre un mensaje.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, 
    IEnumerable<string> messageExtraFields = null, IConnection connection = null, 
    CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | Int32 | Conexión a un servidor |
| sequenceNumber | IEnumerable`1 | El número de secuencia del mensaje. |
| messageExtraFields | IConnection | Lista de parámetros extra para un mensaje que será solicitado. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* asamblea [Aspose.Email](../../../)

---

## ListMessageAsync(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) {#listmessageasync_1}

Obtiene información sobre un mensaje.

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, 
    IEnumerable<string> messageExtraFields = null, IConnection connection = null, 
    CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | String | Conexión a un servidor |
| uniqueId | IEnumerable`1 | La identificación única del mensaje |
| messageExtraFields | IConnection | Lista de parámetros extra para un mensaje que será solicitado. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->