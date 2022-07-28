---
title: MessageObject
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta un oggetto messaggio di Outlook. Limiti di valutazione vengono letti solo 1 allegato e 1 destinatario durante il caricamento del messaggio verrà aggiunta la filigrana durante il salvataggio del messaggio.
type: docs
weight: 18820
url: /it/net/aspose.email.mapi.msg/messageobject/
---
## MessageObject class

Rappresenta un oggetto messaggio di Outlook. Limiti di valutazione: vengono letti solo 1 allegato e 1 destinatario durante il caricamento del messaggio, verrà aggiunta la filigrana durante il salvataggio del messaggio.

```csharp
public sealed class MessageObject : IMessageObjectPropertyContainer
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MessageObject](messageobject#constructor)(Stream, MessageObjectLoadFormat) | Inizializza una nuova istanza di[`MessageObject`](../messageobject) classe. |
| [MessageObject](messageobject#constructor_1)(string, MessageObjectLoadFormat) | Inizializza una nuova istanza di[`MessageObject`](../messageobject) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../aspose.email.mapi.msg/messageobject/attachments) { get; } | Ottiene gli allegati di[`MessageObject`](../messageobject) . |
| [Codepage](../../aspose.email.mapi.msg/messageobject/codepage) { get; } | Ottiene la codepage utilizzata per codificare/decodificare le proprietà delle stringhe nel casoPT_STRING8 viene utilizzato il tipo per loro. |
| [Properties](../../aspose.email.mapi.msg/messageobject/properties) { get; } | Ottiene le proprietà di[`MessageObject`](../messageobject) . |
| [Recipients](../../aspose.email.mapi.msg/messageobject/recipients) { get; } | Ottiene i destinatari del[`MessageObject`](../messageobject) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetIdForNamedProperty](../../aspose.email.mapi.msg/messageobject/getidfornamedproperty)() | Ottiene l'id da utilizzare per la proprietà denominata, le proprietà con nome sono proprietà speciali e dovrebbero avere i loro ID nell'intervallo [0x8000,0xfffe] allineati a partire da 0x8000 in sequenza. Utilizzare questo metodo per trovare l'id disponibile perché potrebbe essere difficile calcolalo tu stesso. |
| [Save](../../aspose.email.mapi.msg/messageobject/save#save)(Stream, MessageObjectSaveFormat) | Salva l'oggetto messaggio corrente nel flusso specificato. |
| [Save](../../aspose.email.mapi.msg/messageobject/save#save_1)(string, MessageObjectSaveFormat) | Salva l'oggetto messaggio corrente nel file specificato. |

### Guarda anche

* interface [IMessageObjectPropertyContainer](../imessageobjectpropertycontainer)
* spazio dei nomi [Aspose.Email.Mapi.Msg](../../aspose.email.mapi.msg)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->