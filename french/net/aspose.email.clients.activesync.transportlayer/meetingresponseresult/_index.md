---
title: MeetingResponseResult
second_title: Référence de l'API Aspose.Email pour .NET
description: Objet de résultat de réponse de réunion
type: docs
weight: 1530
url: /fr/net/aspose.email.clients.activesync.transportlayer/meetingresponseresult/
---
## MeetingResponseResult class

Objet de résultat de réponse de réunion

```csharp
public class MeetingResponseResult
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MeetingResponseResult](meetingresponseresult)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [CalendarId](../../aspose.email.clients.activesync.transportlayer/meetingresponseresult/calendarid) { get; set; } | Spécifie l'ID de serveur de l'élément de calendrier. La valeur de l'élément CalendarId peut comporter jusqu'à 64 caractères. L'élément CalendarId est inclus dans la réponse de la commande MeetingResponse qui est envoyée au client si la demande de réunion n'a pas été refusée. Si la réunion est acceptée ou acceptée provisoirement, le serveur ajoute un nouvel élément au calendrier et renvoie son ID de serveur dans l'élément CalendarId de la réponse. Si le client a créé un élément de calendrier de réunion provisoire, le client met à jour cet élément avec le nouvel ID de serveur. Le client modifie également l'état occupé de provisoire à occupé. Lorsqu'une réunion est acceptée, le serveur crée également un nouvel élément de calendrier avec le même ID de serveur. Cela signifie qu'il y a un conflit qui sera résolu lors de la prochaine synchronisation du calendrier. Si la réunion est refusée, la réponse ne contient pas d'élément CalendarId. |
| [RequestId](../../aspose.email.clients.activesync.transportlayer/meetingresponseresult/requestid) { get; set; } | Spécifie l'ID de serveur de l'élément de message de demande de réunion. |
| [Status](../../aspose.email.clients.activesync.transportlayer/meetingresponseresult/status) { get; set; } | Indique le succès ou l'échec de l'opération. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->