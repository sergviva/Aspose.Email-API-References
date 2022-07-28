---
title: BackupAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Sichert den Inhalt der angegebenen Ordner.
type: docs
weight: 50
url: /de/net/aspose.email.clients.exchange.webservice/iasyncewsclient/backupasync/
---
## BackupAsync(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) {#backupasync_1}

Sichert den Inhalt der angegebenen Ordner.

```csharp
public Task BackupAsync(ExchangeFolderInfoCollection folders, string fileName, 
    BackupOptions options, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | Die Sammlung der zu sichernden Ordner. |
| fileName | String | Der Pfad zur persönlichen Speicherdatei. |
| options | BackupOptions | Die Backup-Optionen. |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | EIN*fileName* ist`Null`oder`leer`. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* ist`Null`. |

### Siehe auch

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [BackupOptions](../../../aspose.email.storage.pst/backupoptions)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Montage [Aspose.Email](../../../)

---

## BackupAsync(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) {#backupasync}

Sichert den Inhalt der angegebenen Ordner.

```csharp
public Task BackupAsync(ExchangeFolderInfoCollection folders, Stream stream, BackupOptions options, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | Die Sammlung der zu sichernden Ordner. |
| stream | Stream | Der Stream, in den geschrieben werden soll. |
| options | BackupOptions | Die Backup-Optionen. |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotSupportedException | Der angegebene Stream unterstützt das Schreiben nicht. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders*oder*stream* ist`Null`. |

### Siehe auch

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [BackupOptions](../../../aspose.email.storage.pst/backupoptions)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->