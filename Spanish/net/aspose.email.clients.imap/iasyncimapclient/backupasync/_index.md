---
title: BackupAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Realiza copias de seguridad del contenido de las carpetas especificadas
type: docs
weight: 40
url: /es/net/aspose.email.clients.imap/iasyncimapclient/backupasync/
---
## BackupAsync(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) {#backupasync}

Realiza copias de seguridad del contenido de las carpetas especificadas

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, Stream stream, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Conexión a un servidor |
| folders | Stream | Una carpeta para respaldar |
| stream | BackupSettings | Un flujo para escribir |
| options | IConnection | Opciones de copia de seguridad |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [BackupSettings](../../backupsettings)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* asamblea [Aspose.Email](../../../)

---

## BackupAsync(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) {#backupasync_1}

Realiza copias de seguridad del contenido de las carpetas especificadas

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, string fileName, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Conexión a un servidor |
| folders | String | Una carpeta para respaldar |
| fileName | BackupSettings | Una ruta al archivo de almacenamiento personal |
| options | IConnection | Opciones de copia de seguridad |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [BackupSettings](../../backupsettings)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->