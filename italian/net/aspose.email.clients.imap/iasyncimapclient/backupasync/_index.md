---
title: BackupAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Esegue il backup del contenuto delle cartelle specificate
type: docs
weight: 40
url: /it/net/aspose.email.clients.imap/iasyncimapclient/backupasync/
---
## BackupAsync(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) {#backupasync}

Esegue il backup del contenuto delle cartelle specificate

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, Stream stream, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Connessione a un server |
| folders | Stream | Cartelle di cui eseguire il backup |
| stream | BackupSettings | Un flusso in cui scrivere |
| options | IConnection | Opzioni di backup |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [BackupSettings](../../backupsettings)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* assemblea [Aspose.Email](../../../)

---

## BackupAsync(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) {#backupasync_1}

Esegue il backup del contenuto delle cartelle specificate

```csharp
public Task BackupAsync(ImapFolderInfoCollection folders, string fileName, BackupSettings options, 
    IConnection connection = null, CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | ImapFolderInfoCollection | Connessione a un server |
| folders | String | Cartelle di cui eseguire il backup |
| fileName | BackupSettings | Un percorso al file di archiviazione personale |
| options | IConnection | Opzioni di backup |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [BackupSettings](../../backupsettings)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->