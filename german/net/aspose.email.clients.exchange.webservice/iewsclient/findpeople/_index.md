---
title: FindPeople
second_title: Aspose.Email für .NET-API-Referenz
description: Kontakte finden die sich in der globalen Adressliste GAL auf dem Server befinden.
type: docs
weight: 860
url: /de/net/aspose.email.clients.exchange.webservice/iewsclient/findpeople/
---
## FindPeople(string, int) {#findpeople_1}

Kontakte finden, die sich in der globalen Adressliste (GAL) auf dem Server befinden.

```csharp
public Contact[] FindPeople(string queryString, int maxNumberOfItems)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| queryString | String | Repräsentiert Suchkriterien für Kontakte. |
| maxNumberOfItems | Int32 | Maximale Anzahl von Artikeln. |

### Rückgabewert

Eine Reihe von[`Contact`](../../../aspose.email.personalinfo/contact) die Kontaktinformationen darstellt

### Siehe auch

* class [Contact](../../../aspose.email.personalinfo/contact)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

---

## FindPeople(string, MailQuery, int) {#findpeople}

Kontakte suchen, die sich im persönlichen Postfach des angegebenen Benutzers auf dem Server befinden.

```csharp
public Contact[] FindPeople(string folderUri, MailQuery query, int maxNumberOfItems)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folderUri | String | Der URI des Ordners. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) die Suchkriterien für Kontakte darstellt. |
| maxNumberOfItems | Int32 | Maximale Anzahl von Artikeln. |

### Rückgabewert

Eine Reihe von[`Contact`](../../../aspose.email.personalinfo/contact) die Kontaktinformationen darstellt

### Siehe auch

* class [Contact](../../../aspose.email.personalinfo/contact)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->