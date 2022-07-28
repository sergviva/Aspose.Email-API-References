---
title: DevicePasswordHistory
second_title: Aspose.Email per riferimento all'API .NET
description: Specifica il numero minimo di password utilizzate in precedenza memorizzate per impedirne il riutilizzo da parte del client. I valori validi sono elencati di seguito  0 - La memorizzazione delle password utilizzate in precedenza non è richiesta. gt 0 - Il numero minimo di password utilizzate in precedenza da stored. Se DevicePasswordHistory è nullo un client DEVE trattare questo valore come 0. Se il valore di DevicePasswordEnabled è impostato su TRUE il client impedisce allutente di utilizzare una password precedente memorizzata dopo la scadenza di una password. Se il valore di DevicePasswordEnabled è impostato su FALSE il client DOVREBBE ignorare questa proprietà.
type: docs
weight: 250
url: /it/net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordhistory/
---
## EASProvisionDoc.DevicePasswordHistory property

Specifica il numero minimo di password utilizzate in precedenza memorizzate per impedirne il riutilizzo da parte del client. I valori validi sono elencati di seguito: = 0 - La memorizzazione delle password utilizzate in precedenza non è richiesta. &gt; 0 - Il numero minimo di password utilizzate in precedenza da stored. Se DevicePasswordHistory è nullo, un client DEVE trattare questo valore come 0. Se il valore di DevicePasswordEnabled è impostato su TRUE, il client impedisce all'utente di utilizzare una password precedente memorizzata dopo la scadenza di una password. Se il valore di DevicePasswordEnabled è impostato su FALSE, il client DOVREBBE ignorare questa proprietà.

```csharp
public int? DevicePasswordHistory { get; set; }
```

### Guarda anche

* class [EASProvisionDoc](../../easprovisiondoc)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../easprovisiondoc)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->