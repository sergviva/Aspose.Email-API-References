---
title: Availability
second_title: Aspose.Email für .NET-API-Referenz
description: Zeigt dem Server an dass Frei/Gebucht-Daten vom Client angefordert werden und identifiziert die Start- und Endzeit der abzurufenden Frei/Gebucht-Daten. Wenn die Verfügbarkeit in einer ResolveRecipients-Anforderung enthalten ist ruft der Server Frei/Gebucht-Daten ab Informationen für die Benutzer die in den in der Anforderung enthaltenen To-Elementen angegeben sind und gibt die Frei/Gebucht-Informationen in MergedFreeBusy in der Antwort zurück. Wenn das Availability-Element in der ResolveRecipients-Anfrage enthalten ist MUSS die Anfrage auch einen gültigen StartTime-Wert und EndTime-Wert enthalten. Wenn der Server die Anfrage parst löst der Server zuerst die durch die To-Elemente identifizierten Empfänger auf und bestimmt dann die Frei/Gebucht-Informationen des Benutzers für die angegebene Zeitspanne bevor er die Frei/Gebucht-Daten in MergedFreeBusy zurückgibt.
type: docs
weight: 20
url: /de/net/aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/availability/
---
## ResolveRecipientsOptions.Availability property

Zeigt dem Server an, dass Frei/Gebucht-Daten vom Client angefordert werden, und identifiziert die Start- und Endzeit der abzurufenden Frei/Gebucht-Daten. Wenn die Verfügbarkeit in einer ResolveRecipients-Anforderung enthalten ist, ruft der Server Frei/Gebucht-Daten ab Informationen für die Benutzer, die in den in der Anforderung enthaltenen To-Elementen angegeben sind, und gibt die Frei/Gebucht-Informationen in MergedFreeBusy in der Antwort zurück. Wenn das Availability-Element in der ResolveRecipients-Anfrage enthalten ist, MUSS die Anfrage auch einen gültigen StartTime-Wert und EndTime-Wert enthalten. Wenn der Server die Anfrage parst, löst der Server zuerst die durch die To-Elemente identifizierten Empfänger auf und bestimmt dann die Frei/Gebucht-Informationen des Benutzers für die angegebene Zeitspanne, bevor er die Frei/Gebucht-Daten in MergedFreeBusy zurückgibt.

```csharp
public ResolveRecipientsAvailabilityRequest Availability { get; set; }
```

### Siehe auch

* class [ResolveRecipientsAvailabilityRequest](../../resolverecipientsavailabilityrequest)
* class [ResolveRecipientsOptions](../../resolverecipientsoptions)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../resolverecipientsoptions)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->