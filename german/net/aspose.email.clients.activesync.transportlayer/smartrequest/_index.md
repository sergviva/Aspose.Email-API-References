---
title: SmartRequest
second_title: Aspose.Email für .NET-API-Referenz
description: Enthält Smart-Request-Informationen
type: docs
weight: 2090
url: /de/net/aspose.email.clients.activesync.transportlayer/smartrequest/
---
## SmartRequest class

Enthält Smart-Request-Informationen

```csharp
public class SmartRequest
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SmartRequest](smartrequest)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AccountId](../../aspose.email.clients.activesync.transportlayer/smartrequest/accountid) { get; set; } | Identifiziert das Konto, von dem eine E-Mail gesendet wird. Wenn die Konto-ID null ist, sendet der Server die E-Mail unter Verwendung des Kontos, das durch die Einstellungen identifiziert wird: Primäre SMTP-Adresse, die in der Antwort auf den Befehl "Einstellungen" zurückgegeben wird. Wenn die Konto-ID in der Anforderung enthalten ist, der Wert MUSS einem der settings:AccountId-Elementwerte entsprechen, die in der Antwort auf den Settings-Befehl enthalten sind. Der Server MUSS validieren, dass der angegebene AccountId-Elementwert zum Senden von E-Mails gültig ist. Ein Statuswert von 166 wird zurückgegeben, wenn der AccountId-Elementwert nicht gültig ist. Ein Statuselementwert von 167 wird zurückgegeben, wenn das Konto das Senden von E-Mails nicht unterstützt. Hinweis Der Server sendet die E-Mail unter Verwendung des durch AccountId angegebenen Kontos und nicht des durch From. Das AccountId-Element wird nicht unterstützt, wenn die Protokollversion ist 12.1 oder 14.0. Exchange 2007 gibt den Statuswert 103 zurück, wenn das AccountId-Element in einer SendMail-Befehlsanforderung, einer SmartForward-Befehlsanforderung oder einer SmartReply-Befehlsanforderung enthalten ist. |
| [ClientId](../../aspose.email.clients.activesync.transportlayer/smartrequest/clientid) { get; set; } | Gibt die eindeutige Nachrichten-ID (MID) des Clients an. Der ClientId-Wert kann bis zu 40 Zeichen lang sein und MUSS für jede Nachricht eindeutig sein, da der Server den ClientId-Wert verwendet, um doppelte Nachrichten zu identifizieren. Der ClientId-Wert kann ein einfacher Zähler sein, der für jede neue Nachricht erhöht wird. |
| [Mime](../../aspose.email.clients.activesync.transportlayer/smartrequest/mime) { get; set; } | Enthält die MIME-codierte Nachricht. Der Mime-Inhalt wird als undurchsichtiges BLOB innerhalb der WBXML-Tags übertragen, wie in [WBXML1.2] angegeben. Wenn die Nachricht eine Besprechungsanfrage enthält, enthält das Mime-Element die Details des Treffens iCalendar-Format [MS-OXCICAL] oder Transport Neutral Encapsulation Format (TNEF)-Format [MS-OXTNEF]. Wie in [RFC2447] Abschnitt 3.4 angegeben, haben Besprechungsanfragen in iCalendar den Inhaltstyp „Text/Kalender“, wobei der Methodenparameter auf „REQUEST“ gesetzt ist. |
| [ReplaceMime](../../aspose.email.clients.activesync.transportlayer/smartrequest/replacemime) { get; set; } | Gibt an, ob der Client die gesamte Nachricht sendet. Wenn ReplaceMime WAHR ist, DARF der Server weder den Hauptteil noch die Anhänge der weitergeleiteten Originalnachricht enthalten. Wenn ReplaceMime FALSE ist, MUSS der Client den Hauptteil der ursprünglichen Nachricht als Anhänge an die ausgehende Nachricht anhängen. Der Client kann diese Eigenschaft verwenden, um anzugeben, ob die Nachricht inline bearbeitet wurde oder ob der Nachricht ein Antwort-/Weiterleitungstext vorangestellt wurde. Wenn ReplaceMime TRUE ist, wurde die Nachricht bearbeitet. |
| [SaveInSentItems](../../aspose.email.clients.activesync.transportlayer/smartrequest/saveinsentitems) { get; set; } | Gibt an, ob eine Kopie der Nachricht im Ordner "Gesendete Objekte" gespeichert wird. |
| [Source](../../aspose.email.clients.activesync.transportlayer/smartrequest/source) { get; set; } | Enthält Informationen über die Quellnachricht. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/smartrequest/templateid) { get; set; } | Enthält eine Zeichenfolge, die die Rechterichtlinienvorlage identifiziert, die durch das übergeordnete RightsManagementLicense-Element dargestellt wird. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->