---
title: UpdateOverride
second_title: Aspose.Email per riferimento all'API .NET
description: Modifica il campo classifyAs di un override come specificato. Non è possibile utilizzare questo metodo per modificare altri campi in unistanza ClassificationOverride. Se esiste un override per un mittente e il mittente modifica il proprio nome visualizzato è possibile utilizzare CreateOrUpdateOverride per forzare un aggiornamento al campo del nome nelloverride esistente. Se esiste un override per un mittente e il mittente modifica il proprio indirizzo SMTP eliminare loverride esistente e crearne uno nuovo con il nuovo indirizzo SMTP è lunico modo per aggiorna loverride per questo mittente. Autorizzazioni Per chiamare questa API è richiesta una delle seguenti autorizzazioni. account Microsoft personale Mail.ReadWrite Applicazione Mail.ReadWrite
type: docs
weight: 410
url: /it/net/aspose.email.clients.graph/igraphclient/updateoverride/
---
## IGraphClient.UpdateOverride method

Modifica il campo classifyAs di un override come specificato. Non è possibile utilizzare questo metodo per modificare altri campi in un'istanza ClassificationOverride. Se esiste un override per un mittente e il mittente modifica il proprio nome visualizzato, è possibile utilizzare CreateOrUpdateOverride per forzare un aggiornamento al campo del nome nell'override esistente. Se esiste un override per un mittente e il mittente modifica il proprio indirizzo SMTP, eliminare l'override esistente e crearne uno nuovo con il nuovo indirizzo SMTP è l'unico modo per "aggiorna" l'override per questo mittente. Autorizzazioni: Per chiamare questa API è richiesta una delle seguenti autorizzazioni. (account Microsoft personale) Mail.ReadWrite Applicazione Mail.ReadWrite

```csharp
public ClassificationOverride UpdateOverride(ClassificationOverride classificationOverride)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classificationOverride | ClassificationOverride | Sostituzione della classificazione da aggiornare |

### Guarda anche

* class [ClassificationOverride](../../classificationoverride)
* interface [IGraphClient](../../igraphclient)
* spazio dei nomi [Aspose.Email.Clients.Graph](../../igraphclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->