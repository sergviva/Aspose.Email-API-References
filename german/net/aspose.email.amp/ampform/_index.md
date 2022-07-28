---
title: AmpForm
second_title: Aspose.Email für .NET-API-Referenz
description: Mit der AMP-Formularerweiterung können Sie Formulare erstellen um Eingabefelder in einem AMP-Dokument zu übermitteln.
type: docs
weight: 120
url: /de/net/aspose.email.amp/ampform/
---
## AmpForm class

Mit der AMP-Formularerweiterung können Sie Formulare erstellen, um Eingabefelder in einem AMP-Dokument zu übermitteln.

```csharp
public class AmpForm : AmpComponent
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [AmpForm](ampform)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Action](../../aspose.email.amp/ampform/action) { get; set; } | Gibt einen Serverendpunkt für die Verarbeitung der Formulareingabe an. Der Wert muss eine https-URL (absolut oder relativ) sein und darf kein Link zu einem CDN sein. |
| [ActionXhr](../../aspose.email.amp/ampform/actionxhr) { get; set; } | Gibt einen Serverendpunkt an, um die Formulareingabe zu verarbeiten und das Formular über XMLHttpRequest (XHR) zu senden. |
| [Attributes](../../aspose.email.amp/ampcomponent/attributes) { get; } | AMP bietet eine Reihe gemeinsamer Attribute, die auf viele AMP-Komponenten erweitert werden. |
| [Fallback](../../aspose.email.amp/ampcomponent/fallback) { get; set; } | Ein Fallback ist eine Konvention, die es dem Element ermöglicht, dem Leser mitzuteilen, dass der Browser das Element nicht unterstützt. |
| [Fieldset](../../aspose.email.amp/ampform/fieldset) { get; } | Liste der Felder. |
| [Method](../../aspose.email.amp/ampform/method) { get; set; } | Das Methodenattribut teilt dem Server die Anfragemethode mit. |
| [Placeholder](../../aspose.email.amp/ampcomponent/placeholder) { get; set; } | Das mit dem placeholder-Attribut gekennzeichnete Element fungiert als Platzhalter für das übergeordnete AMP-Element. Falls angegeben, muss ein Platzhalterelement ein direktes untergeordnetes Element des AMP-Elements sein. |
| override [RequiredScript](../../aspose.email.amp/ampform/requiredscript) { get; } | Erforderliches Skript, das dem Head-Abschnitt hinzugefügt werden muss. |
| [Target](../../aspose.email.amp/ampform/target) { get; set; } | Gibt an, wo die Formularantwort nach dem Absenden des Formulars angezeigt werden soll. Der Wert muss _blank oder _top sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToAmpHtml](../../aspose.email.amp/ampform/toamphtml)() | Repräsentiert die HTML-Version der Komponente. |
| override [ToHtml](../../aspose.email.amp/ampform/tohtml)() | Repräsentiert die HTML-Version der Komponente. |

### Siehe auch

* class [AmpComponent](../ampcomponent)
* namensraum [Aspose.Email.Amp](../../aspose.email.amp)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->