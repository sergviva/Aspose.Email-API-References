---
title: Subject
second_title: Aspose.Email för .NET API-referens
description: Hämtar eller ställer in ämnet för meddelandet.
type: docs
weight: 170
url: /sv/net/aspose.email.mapi/mapimessageitembase/subject/
---
## MapiMessageItemBase.Subject property

Hämtar eller ställer in ämnet för meddelandet.

```csharp
public string Subject { get; set; }
```

### Fastighetsvärde

Strängen som representerar meddelandets ämne.

### Anmärkningar

När du ställer in ett värde uppdateras även värdena för SubjectPrefix(PR_SUBJECT_PREFIX) och NormalizedSubject(PR_NORMALIZED_SUBJECT) egenskaper. Om Subject inte har något prefix sätts värdet på SubjectPrefix-egenskapen null. När du ställer in ett nullvärde eller en tom sträng, sätts värdena av Subject, SubjectPrefix, NormalizedSubject-egenskaper null.

### Se även

* class [MapiMessageItemBase](../../mapimessageitembase)
* namnutrymme [Aspose.Email.Mapi](../../mapimessageitembase)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->