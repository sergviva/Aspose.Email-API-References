---
title: ReadNextMessage
second_title: Aspose.Email för .NET API-referens
description: Läser nästa meddelande från underliggande lagringsström.
type: docs
weight: 70
url: /sv/net/aspose.email.storage.mbox/mboxstoragereader/readnextmessage/
---
## ReadNextMessage() {#readnextmessage}

Läser nästa meddelande från underliggande lagringsström.

```csharp
public abstract MailMessage ReadNextMessage()
```

### Returvärde

A[`MailMessage`](../../../aspose.email/mailmessage) objekt om det går att läsa eller **null** om inga fler meddelanden är tillgängliga.

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [MboxStorageReader](../../mboxstoragereader)
* namnutrymme [Aspose.Email.Storage.Mbox](../../mboxstoragereader)
* hopsättning [Aspose.Email](../../../)

---

## ReadNextMessage(out string) {#readnextmessage_1}

Läser nästa meddelande från underliggande lagringsström.

```csharp
public abstract MailMessage ReadNextMessage(out string fromMarker)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fromMarker | String& | Hämtar From Marker medan MBox Storage-filen analyseras. |

### Returvärde

A[`MailMessage`](../../../aspose.email/mailmessage) objekt om det går att läsa eller **null** om inga fler meddelanden är tillgängliga.

### Se även

* class [MailMessage](../../../aspose.email/mailmessage)
* class [MboxStorageReader](../../mboxstoragereader)
* namnutrymme [Aspose.Email.Storage.Mbox](../../mboxstoragereader)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->