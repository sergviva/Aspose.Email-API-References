---
title: ConvertPersonalStorageToMbox
second_title: Aspose.Email för .NET API-referens
description: KonverterarPersonalStorageaspose.email.storage.pst/personalstoragetill mbox-format med hjälp av angiven sökväg.
type: docs
weight: 10
url: /sv/net/aspose.email.storage/mailboxconverter/convertpersonalstoragetombox/
---
## ConvertPersonalStorageToMbox(PersonalStorage, string, MessageAcceptanceCallback) {#convertpersonalstoragetombox_1}

Konverterar[`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage)till mbox-format med hjälp av angiven sökväg.

```csharp
public static void ConvertPersonalStorageToMbox(PersonalStorage personalStorage, 
    string storagePath, MessageAcceptanceCallback acceptanceCallback)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| personalStorage | PersonalStorage | Den personliga förvaringen. |
| storagePath | String | Vägen att spara*personalStorage* struktur till. |
| acceptanceCallback | MessageAcceptanceCallback | Acceptansåteruppringningen kan vara null. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Om*personalStorage* är inget. |
| ArgumentNullException | Om*storagePath* är inget. |

### Anmärkningar

Den resulterande mappen kommer att innehålla en exakt kopia av*personalStorage* t.ex. kommer katalogträdet att återskapas på disk.

### Se även

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MessageAcceptanceCallback](../../../aspose.email/messageacceptancecallback)
* class [MailboxConverter](../../mailboxconverter)
* namnutrymme [Aspose.Email.Storage](../../mailboxconverter)
* hopsättning [Aspose.Email](../../../)

---

## ConvertPersonalStorageToMbox(PersonalStorage, MboxStorageWriter, MessageAcceptanceCallback) {#convertpersonalstoragetombox}

Konverterar[`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) till mbox-format med given[`MboxStorageWriter`](../../../aspose.email.storage.mbox/mboxstoragewriter) .

```csharp
public static void ConvertPersonalStorageToMbox(PersonalStorage personalStorage, 
    MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| personalStorage | PersonalStorage | Den personliga förvaringen. |
| mboxStorageWriter | MboxStorageWriter | Mbox-lagringsskrivaren. |
| acceptanceCallback | MessageAcceptanceCallback | Acceptansåteruppringningen kan vara null. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Om*personalStorage* är inget. |
| ArgumentNullException | Om*mboxStorageWriter* är inget. |

### Anmärkningar

Resulterande mbox-lagring kommer bara att innehålla en vanlig inkorgsmapp med alla meddelanden, om du måste bevara den ursprungliga strukturen för lagringen, använd istället XXX_method.

### Se även

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [MboxStorageWriter](../../../aspose.email.storage.mbox/mboxstoragewriter)
* delegate [MessageAcceptanceCallback](../../../aspose.email/messageacceptancecallback)
* class [MailboxConverter](../../mailboxconverter)
* namnutrymme [Aspose.Email.Storage](../../mailboxconverter)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->