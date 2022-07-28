---
title: Query
second_title: Aspose.Email für .NET-API-Referenz
description: Gibt die Schlüsselwörter an die zum Abgleichen der Einträge im zu durchsuchenden Geschäft verwendet werden sollen. Der Wert der Abfrage wird als Präfix-String-Abgleichsmuster verwendet und gibt Einträge zurück die mit dem Anfang des Strings übereinstimmen. Beispielsweise würde die Suche nach John mit John Frum oder Barry Johnson übereinstimmen aber nicht mit James Littlejohn. Alle nicht leeren Texteigenschaften in der GAL die mithilfe von ANR indiziert werden werden mit dem Abfrageelement verglichen Wert. Suchvergleiche werden unter Verwendung von Übereinstimmungen ohne Berücksichtigung der Groß-/Kleinschreibung durchgeführt. Für eine Windows SharePoint Services-Dokumentbibliothekssuche unterstützt dieses Protokoll Abfragen der folgenden Form LinkId  Wert wobei Wert die URL des Elements oder Ordners und LinkId angibt dass der Wert mit der Link-ID-Eigenschaft verglichen werden soll. Für die Postfachsuche lautet die Abfragesyntax wie folgt - Ordner können auf folgende Weise angegeben werden Angegebene ID Angegebener Ordner und Unterordner Alle E-Mail-Ordner einschließlich Entwurf Posteingang und Unterordner Postausgang und Gesendete Elemente  Die grundlegende Schlüsselwortabfrage kann aus Folgendem bestehen Der Basisoperator And Abschnitt 2.2.3.10 Ein dateTime-Filter der mithilfe von GreaterThan Abschnitt 2.2.3.78 und LessThan angegeben wird Elemente Abschnitt 2.2.3.87 FreeText-Elemente Abschnitt 2.2.3.73 die Schlüsselwörter enthalten Die grundlegende Schlüsselwortabfrage wird für alle indizierten Eigenschaften ausgeführt.
type: docs
weight: 40
url: /de/net/aspose.email.clients.activesync.transportlayer/searchrequeststore/query/
---
## SearchRequestStore.Query property

Gibt die Schlüsselwörter an, die zum Abgleichen der Einträge im zu durchsuchenden Geschäft verwendet werden sollen. Der Wert der Abfrage wird als Präfix-String-Abgleichsmuster verwendet und gibt Einträge zurück, die mit dem Anfang des Strings übereinstimmen. Beispielsweise würde die Suche nach „John“ mit „John Frum“ oder „Barry Johnson“ übereinstimmen, aber nicht mit „James Littlejohn“. Alle nicht leeren Texteigenschaften in der GAL, die mithilfe von ANR indiziert werden, werden mit dem Abfrageelement verglichen Wert. Suchvergleiche werden unter Verwendung von Übereinstimmungen ohne Berücksichtigung der Groß-/Kleinschreibung durchgeführt. Für eine Windows SharePoint Services-Dokumentbibliothekssuche unterstützt dieses Protokoll Abfragen der folgenden Form: LinkId == Wert, wobei Wert die URL des Elements oder Ordners und LinkId angibt dass der Wert mit der Link-ID-Eigenschaft verglichen werden soll. Für die Postfachsuche lautet die Abfragesyntax wie folgt: - Ordner können auf folgende Weise angegeben werden: Angegebene ID Angegebener Ordner und Unterordner Alle E-Mail-Ordner, einschließlich Entwurf, Posteingang und Unterordner, Postausgang und Gesendete Elemente – Die grundlegende Schlüsselwortabfrage kann aus Folgendem bestehen: Der Basisoperator: And (Abschnitt 2.2.3.10) Ein dateTime-Filter, der mithilfe von GreaterThan (Abschnitt 2.2.3.78) und LessThan angegeben wird Elemente (Abschnitt 2.2.3.87) FreeText-Elemente (Abschnitt 2.2.3.73), die Schlüsselwörter enthalten Die grundlegende Schlüsselwortabfrage wird für alle indizierten Eigenschaften ausgeführt.

```csharp
public SearchQuery Query { get; set; }
```

### Siehe auch

* class [SearchQuery](../../searchquery)
* class [SearchRequestStore](../../searchrequeststore)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchrequeststore)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->