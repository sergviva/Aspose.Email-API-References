---
title: UndeleteMessageAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Marca un mensaje con el número de secuencia especificado como no eliminado
type: docs
weight: 400
url: /es/net/aspose.email.clients.imap/iasyncimapclient/undeletemessageasync/
---
## UndeleteMessageAsync(int, long, IConnection, CancellationToken) {#undeletemessageasync}

Marca un mensaje con el número de secuencia especificado como no eliminado

```csharp
public Task UndeleteMessageAsync(int sequenceNumber, long modificationSequence = 0, 
    IConnection connection = null, CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | Int32 | Conexión a un servidor |
| sequenceNumber | Int64 | El número de secuencia del mensaje. |
| modificationSequence | IConnection | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* asamblea [Aspose.Email](../../../)

---

## UndeleteMessageAsync(string, long, IConnection, CancellationToken) {#undeletemessageasync_1}

Marca un mensaje con el número de secuencia especificado como no eliminado.

```csharp
public Task UndeleteMessageAsync(string uniqueId, long modificationSequence = 0, 
    IConnection connection = null, CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | String | Conexión a un servidor |
| uniqueId | Int64 | La identificación única del mensaje |
| modificationSequence | IConnection | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->