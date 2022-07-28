---
title: DeleteMessagesAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Löscht alle Nachrichten
type: docs
weight: 30
url: /de/net/aspose.email.clients.pop3/iasyncpop3client/deletemessagesasync/
---
## IAsyncPop3Client.DeleteMessagesAsync method

Löscht alle Nachrichten

```csharp
public Task DeleteMessagesAsync(IConnection connection = null, CancellationToken token = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Bemerkungen

Der POP3-Server markiert die Nachricht als gelöscht. Der POP3-Server löscht die Nachricht nicht wirklich, bis die POP3-Sitzung in den UPDATE-Zustand wechselt.

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->