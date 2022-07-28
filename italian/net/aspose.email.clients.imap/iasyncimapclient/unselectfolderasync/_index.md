---
title: UnselectFolderAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Deseleziona la cartella attualmente selezionata. se la proprietà doNotExpunge è vera tutti i messaggi sono contrassegnati come eliminati vengono rimossi altrimenti leliminazione viene annullata. Nota questa operazione funziona solo nel caso in cui il server supporti RFC3691 Vedi altro https//tools. ietf.org/html/rfc3691
type: docs
weight: 410
url: /it/net/aspose.email.clients.imap/iasyncimapclient/unselectfolderasync/
---
## IAsyncImapClient.UnselectFolderAsync method

Deseleziona la cartella attualmente selezionata. se la proprietà doNotExpunge è vera, tutti i messaggi sono contrassegnati come eliminati vengono rimossi, altrimenti l'eliminazione viene annullata. Nota, questa operazione funziona solo nel caso in cui il server supporti RFC3691 Vedi altro https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge = false, IConnection connection = null, 
    CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | Boolean | Connessione a un server |
| doNotExpunge | IConnection | Specifica se i messaggi contrassegnati come eliminati devono essere rimossi. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->