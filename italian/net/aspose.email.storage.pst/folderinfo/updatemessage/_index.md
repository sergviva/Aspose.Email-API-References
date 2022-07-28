---
title: UpdateMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Aggiorna il messaggio nella cartella.
type: docs
weight: 350
url: /it/net/aspose.email.storage.pst/folderinfo/updatemessage/
---
## FolderInfo.UpdateMessage method

Aggiorna il messaggio nella cartella.

```csharp
public void UpdateMessage(string entryId, MapiMessageItemBase updatedMessage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entryId | String | L'identificatore della voce del messaggio. |
| updatedMessage | MapiMessageItemBase | Il messaggio aggiornato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | La modifica della versione del file ANSI non è implementata. |
| InvalidOperationException | Il PST è aperto per la sola lettura. o L'ID voce non è corretto. |
| ArgumentNullException | ID voce; L'ID voce non può essere nullo o vuoto. or updateMessage; Il messaggio non può essere null. |

### Guarda anche

* class [MapiMessageItemBase](../../../aspose.email.mapi/mapimessageitembase)
* class [FolderInfo](../../folderinfo)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../folderinfo)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->