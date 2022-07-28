---
title: FetchAttachmentAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Recupera lallegato specificato.
type: docs
weight: 140
url: /it/net/aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync/
---
## IAsyncImapClient.FetchAttachmentAsync method

Recupera l'allegato specificato.

```csharp
public Task<Attachment> FetchAttachmentAsync(int sequenceNumber, string attachmentName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | Int32 | Connessione a un server. |
| sequenceNumber | String | Il numero di sequenza di un messaggio. |
| attachmentName | IConnection | Un nome di allegato. |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

[`Attachment`](../../../aspose.email/attachment) che rappresenta l'attaccamento.

### Guarda anche

* class [Attachment](../../../aspose.email/attachment)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->