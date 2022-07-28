---
title: Insert
second_title: Aspose.Email för .NET API-referens
description: Infogar ett element iCollection vid angivet index.
type: docs
weight: 30
url: /sv/net/aspose.email.mapi/mapiattachmentcollection/insert/
---
## Insert(int, MapiAttachment) {#insert}

Infogar ett element iCollection vid angivet index.

```csharp
public void Insert(int index, MapiAttachment item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Det nollbaserade indexet vid vilket*item* bör sättas in. |
| item | MapiAttachment | Objektet som ska infogas. Värdet kan vara null för referenstyper. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *index* är mindre än noll. |

### Se även

* class [MapiAttachment](../../mapiattachment)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* namnutrymme [Aspose.Email.Mapi](../../mapiattachmentcollection)
* hopsättning [Aspose.Email](../../../)

---

## Insert(int, string, MapiMessage) {#insert_2}

Infogar ett meddelande som bilaga i[`MapiAttachmentCollection`](../../mapiattachmentcollection) vid angivet index.

```csharp
public void Insert(int index, string name, MapiMessage msg)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Det nollbaserade index som ska infogas. |
| name | String | Bilagans namn. |
| msg | MapiMessage | De[`MapiMessage`](../../mapimessage)som representerar det bifogade meddelandet. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | kastar om meddelandet är null. |

### Se även

* class [MapiMessage](../../mapimessage)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* namnutrymme [Aspose.Email.Mapi](../../mapiattachmentcollection)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->