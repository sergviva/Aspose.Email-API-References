---
title: SetQuotaAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Legt Kontingentinformationen fest
type: docs
weight: 350
url: /de/net/aspose.email.clients.imap/iasyncimapclient/setquotaasync/
---
## IAsyncImapClient.SetQuotaAsync method

Legt Kontingentinformationen fest

```csharp
public Task<ImapQuota[]> SetQuotaAsync(string quotaRootName, string resourceName, 
    int resourceLimit, IConnection connection = null, CancellationToken token = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | String | Verbindung zu einem Server |
| quotaRootName | String | Kontingentstammname |
| resourceName | Int32 | Ressourcenname |
| resourceLimit | IConnection | Ressourcenlimit |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Kontingentinformationen

### Siehe auch

* class [ImapQuota](../../imapquota)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namensraum [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->