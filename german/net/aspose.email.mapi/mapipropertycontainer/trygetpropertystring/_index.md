---
title: TryGetPropertyString
second_title: Aspose.Email für .NET-API-Referenz
description: Versuchen Sie Eigenschaftsdaten als Zeichenfolge mit angegebenem Tag und Codepage abzurufen.
type: docs
weight: 170
url: /de/net/aspose.email.mapi/mapipropertycontainer/trygetpropertystring/
---
## TryGetPropertyString(long, int) {#trygetpropertystring_3}

Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit angegebenem Tag und Codepage abzurufen.

```csharp
public string TryGetPropertyString(long tag, int codepage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tag | Int64 | Der Property-Tag-Schlüssel. |
| codepage | Int32 | Die Codepage. |

### Rückgabewert

Zeichenfolge, die den Inhalt von Eigenschaftsdaten enthält.

### Siehe auch

* class [MapiPropertyContainer](../../mapipropertycontainer)
* namensraum [Aspose.Email.Mapi](../../mapipropertycontainer)
* Montage [Aspose.Email](../../../)

---

## TryGetPropertyString(long) {#trygetpropertystring_2}

Versuchen Sie, Eigenschaftsdaten als Zeichenfolge mit dem angegebenen Tag zu erhalten.

```csharp
public string TryGetPropertyString(long tag)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tag | Int64 | Der Property-Tag-Schlüssel. |

### Rückgabewert

Zeichenfolge, die den Inhalt von Eigenschaftsdaten enthält.

### Siehe auch

* class [MapiPropertyContainer](../../mapipropertycontainer)
* namensraum [Aspose.Email.Mapi](../../mapipropertycontainer)
* Montage [Aspose.Email](../../../)

---

## TryGetPropertyString(long, ref string, int) {#trygetpropertystring_1}

Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war.

```csharp
public bool TryGetPropertyString(long tag, ref string value, int codepage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tag | Int64 | Das MAPI-Eigenschaftstag. |
| value | String& | Wenn diese Methode zurückkehrt, enthält sie den Wert der angegebenen Eigenschaft, falls die Eigenschaft vorhanden ist. Dieser Parameter wird nicht initialisiert übergeben. |
| codepage | Int32 | Die angegebene Codepage, die zum Abrufen des Zeichenfolgenwerts verwendet wird. |

### Rückgabewert

wahr, wenn s erfolgreich konvertiert wurde; andernfalls falsch.

### Siehe auch

* class [MapiPropertyContainer](../../mapipropertycontainer)
* namensraum [Aspose.Email.Mapi](../../mapipropertycontainer)
* Montage [Aspose.Email](../../../)

---

## TryGetPropertyString(long, ref string) {#trygetpropertystring}

Ruft den Wert der angegebenen Eigenschaft als String-Typ ab. Ein Rückgabewert zeigt an, ob die Operation erfolgreich war.

```csharp
public bool TryGetPropertyString(long tag, ref string value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tag | Int64 | Das MAPI-Eigenschaftstag. |
| value | String& | Wenn diese Methode zurückkehrt, enthält den Wert der angegebenen Eigenschaft, sofern die Eigenschaft vorhanden ist. Dieser Parameter wird nicht initialisiert übergeben. |

### Rückgabewert

wahr, wenn s erfolgreich konvertiert wurde; andernfalls falsch.

### Siehe auch

* class [MapiPropertyContainer](../../mapipropertycontainer)
* namensraum [Aspose.Email.Mapi](../../mapipropertycontainer)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->