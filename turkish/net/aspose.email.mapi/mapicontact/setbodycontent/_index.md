---
title: SetBodyContent
second_title: Aspose.Email for .NET API Referansı
description: Gövdenin içeriğini ayarlar.
type: docs
weight: 150
url: /tr/net/aspose.email.mapi/mapicontact/setbodycontent/
---
## MapiContact.SetBodyContent method

Gövdenin içeriğini ayarlar.

```csharp
public override void SetBodyContent(string content, BodyContentType contentType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| content | String | İçerik. |
| contentType | BodyContentType | İçeriğin türü. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | belirtilen içerik dizesi boşsa veya boşsa atar. |

### Notlar

Gövde mesajının içeriğinin RTF, HTML veya Düz Metin formatlarında ayarlanması için sağlanmıştır. Bir değer ayarlarken, PR_RTF_COMPRESSED, PR_RTF_DECOMPRESSES, PR_BODY özelliklerinin değerleri de güncellenir. Not, HTML biçimindeki değer ayarlandıktan sonra BodyRtf özelliği, RTF içinde kodlanan değeri döndürür.

### Ayrıca bakınız

* enum [BodyContentType](../../bodycontenttype)
* class [MapiContact](../../mapicontact)
* ad alanı [Aspose.Email.Mapi](../../mapicontact)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->