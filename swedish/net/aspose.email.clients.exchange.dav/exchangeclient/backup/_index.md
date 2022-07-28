---
title: Backup
second_title: Aspose.Email för .NET API-referens
description: Säkerhetskopierar innehållet i de angivna mapparna
type: docs
weight: 100
url: /sv/net/aspose.email.clients.exchange.dav/exchangeclient/backup/
---
## Backup(ExchangeFolderInfoCollection, string, BackupOptions) {#backup_1}

Säkerhetskopierar innehållet i de angivna mapparna

```csharp
public void Backup(ExchangeFolderInfoCollection folders, string fileName, BackupOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | En mappar att säkerhetskopiera |
| fileName | String | En sökväg till den personliga lagringsfilen |
| options | BackupOptions | En backup alternativ |

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | A*fileName* är`null`eller`tömma` |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders* är`null` |

### Se även

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [BackupOptions](../../../aspose.email.storage.pst/backupoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## Backup(ExchangeFolderInfoCollection, Stream, BackupOptions) {#backup}

Säkerhetskopierar innehållet i de angivna mapparna

```csharp
public void Backup(ExchangeFolderInfoCollection folders, Stream stream, BackupOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folders | ExchangeFolderInfoCollection | En mappar att säkerhetskopiera |
| stream | Stream | En ström att skriva i |
| options | BackupOptions | En backup alternativ |

### Undantag

| undantag | skick |
| --- | --- |
| NotSupportedException | Den givna strömmen stöder inte skrivning |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folders*eller*stream* är`null` |

### Se även

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* enum [BackupOptions](../../../aspose.email.storage.pst/backupoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->