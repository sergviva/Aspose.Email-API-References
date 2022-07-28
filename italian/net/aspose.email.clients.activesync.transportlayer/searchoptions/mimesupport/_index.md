---
title: MIMESupport
second_title: Aspose.Email per riferimento all'API .NET
description: Abilita il supporto MIME per gli elementi e-mail che vengono inviati dal server al client. Se lelemento airsyncMIMESupport è impostato su SendForSecureMIMEonly 1 o SendForAll 2 nella richiesta di ricerca - La proprietà di lairsyncbaseBodyPreference il Tipo DOVREBBE essere incluso nella richiesta di ricerca contenente un valore di MIME 4 per informare il server che il dispositivo può leggere il MIME BLOB. - La risposta dal server DEVE includere il airsyncbaseBody che è un figlio di Properties. Il airsyncbaseBody DEVE contenere le seguenti proprietà in una risposta di ricerca S/MIME - Il airsyncbaseType con un valore di MIME 4 per informare il dispositivo che i dati sono un MIME BLOB. - Il airsyncbase EstimatedDataSize per specificare la dimensione totale approssimativa dei dati. - Airsyncbasetroncato per indicare se il MIME BLOB è troncato. - AirsyncbaseData che contiene il MIME BLOB completo.
type: docs
weight: 50
url: /it/net/aspose.email.clients.activesync.transportlayer/searchoptions/mimesupport/
---
## SearchOptions.MIMESupport property

Abilita il supporto MIME per gli elementi e-mail che vengono inviati dal server al client. Se l'elemento airsync:MIMESupport è impostato su 'SendForSecureMIMEonly' (1) o 'SendForAll' (2) nella richiesta di ricerca: - La proprietà di l'airsyncbase:BodyPreference, il Tipo, DOVREBBE essere incluso nella richiesta di ricerca, contenente un valore di 'MIME' (4) per informare il server che il dispositivo può leggere il MIME BLOB. - La risposta dal server DEVE includere il airsyncbase:Body, che è un figlio di Properties. Il airsyncbase:Body DEVE contenere le seguenti proprietà in una risposta di ricerca S/MIME: - Il airsyncbase:Type con un valore di 'MIME' (4) per informare il dispositivo che i dati sono un MIME BLOB. - Il airsyncbase :EstimatedDataSize per specificare la dimensione totale approssimativa dei dati. - Airsyncbase:troncato per indicare se il MIME BLOB è troncato. - Airsyncbase:Data che contiene il MIME BLOB completo.

```csharp
public MIMESupport? MIMESupport { get; set; }
```

### Guarda anche

* enum [MIMESupport](../../mimesupport)
* class [SearchOptions](../../searchoptions)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchoptions)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->