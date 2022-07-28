---
title: SetFlagForRecipients
second_title: Aspose.Email für .NET-API-Referenz
description: Setzt das Flag für einen Nachrichtenentwurf  um Empfänger an eine Nachverfolgung zu erinnern.
type: docs
weight: 130
url: /de/net/aspose.email.mapi/followupmanager/setflagforrecipients/
---
## SetFlagForRecipients(MapiMessage, string) {#setflagforrecipients}

Setzt das Flag für einen Nachrichtenentwurf , um Empfänger an eine Nachverfolgung zu erinnern.

```csharp
public static void SetFlagForRecipients(MapiMessage message, string flagRequest)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | MapiMessage | Das[`MapiMessage`](../../mapimessage) in dem ein Flag gesetzt wird. |
| flagRequest | String | Eine Zeichenfolge, die die angeforderte Aktion für Empfänger einer E-Mail-Nachricht angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn*message* ist Null. |
| ArgumentException | Wenn*flagRequest* ist null oder leer. |
| InvalidOperationException | Wenn die Nachricht nicht auf einen Entwurfsmodus eingestellt ist. |

### Siehe auch

* class [MapiMessage](../../mapimessage)
* class [FollowUpManager](../../followupmanager)
* namensraum [Aspose.Email.Mapi](../../followupmanager)
* Montage [Aspose.Email](../../../)

---

## SetFlagForRecipients(MapiMessage, string, DateTime) {#setflagforrecipients_1}

Setzt das Flag für einen Nachrichtenentwurf , um Empfänger an eine Nachverfolgung zu erinnern.

```csharp
public static void SetFlagForRecipients(MapiMessage message, string flagRequest, 
    DateTime reminderTime)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | MapiMessage | Das[`MapiMessage`](../../mapimessage) in dem ein Flag gesetzt wird. |
| flagRequest | String | Eine Zeichenfolge, die die angeforderte Aktion für Empfänger einer E-Mail-Nachricht angibt. |
| reminderTime | DateTime | Ein Datum, das das Datum und die Uhrzeit angibt, zu der die Erinnerung erfolgen soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn*message* ist Null. |
| ArgumentException | Wenn*flagRequest* ist null oder leer. |
| InvalidOperationException | Wenn die Nachricht nicht auf einen Entwurfsmodus eingestellt ist. |

### Siehe auch

* class [MapiMessage](../../mapimessage)
* class [FollowUpManager](../../followupmanager)
* namensraum [Aspose.Email.Mapi](../../followupmanager)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->