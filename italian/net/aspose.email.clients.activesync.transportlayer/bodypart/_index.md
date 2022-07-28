---
title: BodyPart
second_title: Aspose.Email per riferimento all'API .NET
description: Specifica i dettagli sulla parte del messaggio di un messaggio di posta elettronica in una risposta. Lelemento BodyPart DEVE essere incluso in una risposta al comando quando BodyPartPreference è specificato in una richiesta.
type: docs
weight: 1040
url: /it/net/aspose.email.clients.activesync.transportlayer/bodypart/
---
## BodyPart class

Specifica i dettagli sulla parte del messaggio di un messaggio di posta elettronica in una risposta. L'elemento BodyPart DEVE essere incluso in una risposta al comando quando BodyPartPreference è specificato in una richiesta.

```csharp
public class BodyPart
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BodyPart](bodypart)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Data](../../aspose.email.clients.activesync.transportlayer/bodypart/data) { get; set; } | Il contenuto dell'elemento Data è una stringa nel formato specificato dalla proprietà Type. Se il valore di Type è RTF, il valore dell'elemento Data viene codificato utilizzando la codifica base64. Se la proprietà Truncated è impostata su true, i dati nell'elemento Data vengono troncati. La proprietà EstimatedDataSize fornisce una stima approssimativa della dimensione effettiva dell'intero contenuto della stringa di dati. |
| [EstimatedDataSize](../../aspose.email.clients.activesync.transportlayer/bodypart/estimateddatasize) { get; set; } | Specifica una stima informativa della dimensione dei dati associati all'elemento padre. L'elemento EstimatedDataSize DOVREBBE essere presentato ogni volta che l'elemento troncato è impostato su TRUE |
| [Preview](../../aspose.email.clients.activesync.transportlayer/bodypart/preview) { get; set; } | Contiene il messaggio di testo in chiaro Unicode o l'anteprima della parte del messaggio restituita al client. |
| [Status](../../aspose.email.clients.activesync.transportlayer/bodypart/status) { get; set; } | Contiene un codice e una descrizione che indicano l'esito positivo o negativo dell'operazione |
| [Truncated](../../aspose.email.clients.activesync.transportlayer/bodypart/truncated) { get; set; } | Specifica se il corpo dell'elemento è stato troncato in base all'elemento BodyPreference indicato dal client. Se il valore è TRUE, il corpo dell'elemento è stato troncato. Se il valore è FALSE o la proprietà Troncata non è impostata, il corpo dell'elemento non è stato troncato. |
| [Type](../../aspose.email.clients.activesync.transportlayer/bodypart/type) { get; set; } | Specifica il tipo di formato del contenuto del corpo dell'elemento. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->