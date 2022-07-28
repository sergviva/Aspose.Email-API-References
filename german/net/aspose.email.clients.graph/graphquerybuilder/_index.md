---
title: GraphQueryBuilder
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert den Generator des Suchausdrucks basierend auf Suchfiltern die vom MS Graph-Protokoll verwendet werden.
type: docs
weight: 15940
url: /de/net/aspose.email.clients.graph/graphquerybuilder/
---
## GraphQueryBuilder class

Repräsentiert den Generator des Suchausdrucks basierend auf Suchfiltern, die vom MS Graph-Protokoll verwendet werden.

```csharp
public class GraphQueryBuilder : MailQueryBuilder
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GraphQueryBuilder](graphquerybuilder)() | Initialisiert eine neue Instanz von[`GraphQueryBuilder`](../graphquerybuilder) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im BCC-Feld der Umschlagstruktur enthalten. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im Nachrichtentext enthalten. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im CC-Feld der Umschlagstruktur enthalten. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Ruft die Standardcodierung (Zeichensatz) für den Abfragegenerator ab |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im FROM-Feld der Umschlagstruktur enthalten. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Ruft das Feld ab, mit dem Nachrichten nach internem Datum gefunden werden können. |
| [IsRead](../../aspose.email.clients.graph/graphquerybuilder/isread) { get; } | Ruft das Feld ab, mit dem ungelesene Elemente gefunden werden können. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Ruft das Feld ab, mit dem Nachrichten nach Sendedatum gesucht werden können. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im Feld SUBJECT der Umschlagstruktur enthalten. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Ruft das Feld ab, mit dem die Nachrichten gefunden werden können, die die angegebene Zeichenfolge in den Kopfzeilen (Betreff, von, an, cc) und im Nachrichtentext enthalten. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im TO-Feld der Envelope-Struktur enthalten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Ruft die Abfrage ab. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Nachrichten suchen, die mit einem der Suchschlüssel übereinstimmen. Bietet Disjunktion zwischen zwei Ausdrücken (OR). |

### Siehe auch

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* namensraum [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->