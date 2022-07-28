---
title: SetFlagForRecipients
second_title: Aspose.Email for .NET API Referansı
description: Alıcılara takip etmelerini hatırlatmak için taslak mesajının bayrağını ayarlar.
type: docs
weight: 130
url: /tr/net/aspose.email.mapi/followupmanager/setflagforrecipients/
---
## SetFlagForRecipients(MapiMessage, string) {#setflagforrecipients}

Alıcılara takip etmelerini hatırlatmak için taslak mesajının bayrağını ayarlar.

```csharp
public static void SetFlagForRecipients(MapiMessage message, string flagRequest)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MapiMessage | bu[`MapiMessage`](../../mapimessage) hangi bir bayrak kurulacak. |
| flagRequest | String | Bir e-posta iletisinin alıcıları için istenen eylem eylemini gösteren bir dize. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Eğer*message* boş. |
| ArgumentException | Eğer*flagRequest* null veya boş. |
| InvalidOperationException | Mesaj bir taslak modunda ayarlanmamışsa. |

### Ayrıca bakınız

* class [MapiMessage](../../mapimessage)
* class [FollowUpManager](../../followupmanager)
* ad alanı [Aspose.Email.Mapi](../../followupmanager)
* toplantı [Aspose.Email](../../../)

---

## SetFlagForRecipients(MapiMessage, string, DateTime) {#setflagforrecipients_1}

Alıcılara takip etmelerini hatırlatmak için taslak mesajının bayrağını ayarlar.

```csharp
public static void SetFlagForRecipients(MapiMessage message, string flagRequest, 
    DateTime reminderTime)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MapiMessage | bu[`MapiMessage`](../../mapimessage) hangi bir bayrak kurulacak. |
| flagRequest | String | Bir e-posta iletisinin alıcıları için istenen eylem eylemini gösteren bir dize. |
| reminderTime | DateTime | Hatırlatıcının gerçekleşmesi gereken tarih ve saati belirten bir tarih. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Eğer*message* boş. |
| ArgumentException | Eğer*flagRequest* null veya boş. |
| InvalidOperationException | Mesaj bir taslak modunda ayarlanmamışsa. |

### Ayrıca bakınız

* class [MapiMessage](../../mapimessage)
* class [FollowUpManager](../../followupmanager)
* ad alanı [Aspose.Email.Mapi](../../followupmanager)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->