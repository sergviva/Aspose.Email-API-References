---
title: SyncCollectionResponse
second_title: Aspose.Email für .NET-API-Referenz
description: Klasse enthält Befehle und Optionen die für eine Sync-Antwort gelten.
type: docs
weight: 2200
url: /de/net/aspose.email.clients.activesync.transportlayer/synccollectionresponse/
---
## SyncCollectionResponse class

Klasse enthält Befehle und Optionen, die für eine Sync-Antwort gelten.

```csharp
public class SyncCollectionResponse
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SyncCollectionResponse](synccollectionresponse)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/synccollectionresponse/class) { get; set; } | Identifiziert die Klasse des Elements, das der Sammlung hinzugefügt wird. Wird nur verwendet, wenn die Protokollversion 12.1 ist. |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionresponse/collectionid) { get; set; } | Gibt die Server-ID des zu synchronisierenden Ordners an. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionresponse/commands) { get; set; } | Enthält Vorgänge, die für eine Sammlung gelten. Verfügbare Operationen sind Hinzufügen, Löschen, Ändern, SoftDelete. |
| [MoreAvailable](../../aspose.email.clients.activesync.transportlayer/synccollectionresponse/moreavailable) { get; set; } | Gibt an, dass mehr Änderungen vorhanden sind, als im WindowSize-Element angefordert werden. In Exchange 2007 sendet der Server Sync-Antwortnachrichten, die MoreAvailable und zwischen null (0) und WindowSize-Schemaänderungen enthalten, wenn er Elemente außerhalb des Protokolls findet. |
| [Responses](../../aspose.email.clients.activesync.transportlayer/synccollectionresponse/responses) { get; set; } | Enthält Antworten auf Operationen wie Add, Fetch, Change, die vom Server verarbeitet werden. |
| [Status](../../aspose.email.clients.activesync.transportlayer/synccollectionresponse/status) { get; set; } | Zeigt den Status der Befehlsoperation an |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionresponse/synckey) { get; set; } | Der SyncKey-Wert wird vom Server verwendet, um den Synchronisierungsstatus einer Sammlung zu markieren. Ein Synchronisierungsschlüssel mit dem Wert 0 (Null) initialisiert den Synchronisierungsstatus auf dem Server und bewirkt eine vollständige Synchronisierung der Sammlung. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->