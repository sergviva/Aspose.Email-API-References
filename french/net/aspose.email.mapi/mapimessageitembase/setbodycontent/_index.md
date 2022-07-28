---
title: SetBodyContent
second_title: Référence de l'API Aspose.Email pour .NET
description: Définit le contenu du corps.
type: docs
weight: 230
url: /fr/net/aspose.email.mapi/mapimessageitembase/setbodycontent/
---
## SetBodyContent(string, BodyContentType) {#setbodycontent}

Définit le contenu du corps.

```csharp
public virtual void SetBodyContent(string content, BodyContentType contentType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| content | String | Le contenu. |
| contentType | BodyContentType | Type de contenu. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | lève si la chaîne de contenu spécifiée est nulle ou vide. |

### Remarques

Il est prévu pour définir le contenu du corps du message aux formats RTF, HTML ou Texte brut. Lors de la définition d'une valeur, les valeurs des propriétés PR_RTF_COMPRESSED, PR_RTF_DECOMPRESSES, PR_BODY sont également mises à jour. Remarque, une fois la valeur au format HTML définie, la propriété BodyRtf renvoie la valeur qui est encodée dans RTF.

### Voir également

* enum [BodyContentType](../../bodycontenttype)
* class [MapiMessageItemBase](../../mapimessageitembase)
* espace de noms [Aspose.Email.Mapi](../../mapimessageitembase)
* Assemblée [Aspose.Email](../../../)

---

## SetBodyContent(string, BodyContentType, bool) {#setbodycontent_1}

Définit le contenu du corps.

```csharp
public virtual void SetBodyContent(string content, BodyContentType contentType, bool compression)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| content | String | Le contenu. |
| contentType | BodyContentType | Type de contenu. |
| compression | Boolean | Spécifiez que le contenu doit être compressé. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | lève si la chaîne de contenu spécifiée est nulle ou vide. |

### Remarques

Il est prévu pour définir le contenu du corps du message aux formats RTF, HTML ou Texte brut. Lors de la définition d'une valeur, les valeurs des propriétés PR_RTF_COMPRESSED, PR_RTF_DECOMPRESSES, PR_BODY sont également mises à jour. Remarque, une fois la valeur au format HTML définie, la propriété BodyRtf renvoie la valeur qui est encodée dans RTF.

### Voir également

* enum [BodyContentType](../../bodycontenttype)
* class [MapiMessageItemBase](../../mapimessageitembase)
* espace de noms [Aspose.Email.Mapi](../../mapimessageitembase)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->