---
title: ImapMailboxInfo
second_title: Aspose.Email för .NET API-referens
description: Innehåller en uppsättning brevlådor för specialanvändning
type: docs
weight: 16350
url: /sv/net/aspose.email.clients.imap/imapmailboxinfo/
---
## ImapMailboxInfo class

Innehåller en uppsättning brevlådor för specialanvändning

```csharp
public class ImapMailboxInfo
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AllMessages](../../aspose.email.clients.imap/imapmailboxinfo/allmessages) { get; } | Gets mailbox presenterar alla meddelanden i användarens meddelandelager. Observera att detta värde kan vara null om servern inte stöder rfc6154 eller om mappen inte har skapats. |
| [ArchivedMessages](../../aspose.email.clients.imap/imapmailboxinfo/archivedmessages) { get; } | Gets brevlåda används för att arkivera meddelanden. Observera att detta värde kan vara null om servern inte stöder rfc6154 eller om mappen inte har skapats. |
| [DraftMessages](../../aspose.email.clients.imap/imapmailboxinfo/draftmessages) { get; } | Gets-postlåda används för att hålla utkastmeddelanden, vanligtvis meddelanden som håller på att skrivas men som ännu inte har skickats. Observera att detta värde kan vara null om servern inte stöder rfc6154 eller om mappen inte har skapats. |
| [FlaggedMessages](../../aspose.email.clients.imap/imapmailboxinfo/flaggedmessages) { get; } | Gets mailbox presenterar alla meddelanden markerade på något sätt som "viktiga". Observera att detta värde kan vara null om servern inte stöder rfc6154 eller om mappen inte har skapats. |
| [Important](../../aspose.email.clients.imap/imapmailboxinfo/important) { get; } | Gets-postlåda används för att lagra meddelanden som har markerats som viktiga. Observera att detta värde kan vara null om servern inte stöder rfc8457 eller om mappen inte har skapats. |
| [Inbox](../../aspose.email.clients.imap/imapmailboxinfo/inbox) { get; } | Gets brevlåda används för att hålla inkommande meddelanden. |
| [JunkMessages](../../aspose.email.clients.imap/imapmailboxinfo/junkmessages) { get; } | Gets mailbox är där meddelanden som anses vara skräppost lagras. Observera att detta värde kan vara null om servern inte stöder rfc6154 eller om mappen inte har skapats. |
| [SentMessages](../../aspose.email.clients.imap/imapmailboxinfo/sentmessages) { get; } | Gets brevlåda används för att hålla kopior av meddelanden som har skickats. Observera att detta värde kan vara null om servern inte stöder rfc6154 eller om mappen inte har skapats. |
| [Trash](../../aspose.email.clients.imap/imapmailboxinfo/trash) { get; } | Gets brevlåda används för att lagra meddelanden som har raderats eller markerats för radering. Observera att detta värde kan vara null om servern inte stöder rfc6154 eller om mappen inte har skapats. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ToArray](../../aspose.email.clients.imap/imapmailboxinfo/toarray)() | Hämtar en rad välkända mappar. Om den välkända mappen är null, inkluderas den inte i arrayen. |

### Se även

* namnutrymme [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->