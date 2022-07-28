---
title: Attachment
second_title: Aspose.Email for .NET API Referansı
description: Bir e-posta ekini temsil eder.
type: docs
weight: 350
url: /tr/net/aspose.email/attachment/
---
## Attachment class

Bir e-posta ekini temsil eder.

```csharp
public class Attachment : AttachmentBase, IAttachment, IPreferredTextEncodingProvider
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Attachment](attachment#constructor_3)(string) | Yeni bir örneğini başlatır[`Attachment`](../attachment) sınıf. |
| [Attachment](attachment#constructor)(Stream, ContentType) | Yeni bir örneğini başlatır[`Attachment`](../attachment) sınıf. |
| [Attachment](attachment#constructor_1)(Stream, string) | Yeni bir örneğini başlatır[`Attachment`](../attachment) sınıf. |
| [Attachment](attachment#constructor_4)(string, ContentType) | Yeni bir örneğini başlatır[`Attachment`](../attachment) sınıf. |
| [Attachment](attachment#constructor_5)(string, string) | Yeni bir örneğini başlatır[`Attachment`](../attachment) sınıf. |
| [Attachment](attachment#constructor_2)(Stream, string, string) | Yeni bir örneğini başlatır[`Attachment`](../attachment) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ContentDisposition](../../aspose.email/attachment/contentdisposition) { get; } | İçerik Düzeni başlığını alır |
| [ContentId](../../aspose.email/attachmentbase/contentid) { get; set; } | İçerik kimliğini alır veya ayarlar. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream) { get; set; } | İçerik akışını alır veya ayarlar. |
| [ContentType](../../aspose.email/attachmentbase/contenttype) { get; set; } | İçeriğin türünü alır veya ayarlar. |
| virtual [Headers](../../aspose.email/attachmentbase/headers) { get; } | Ekin başlık koleksiyonunu alır. |
| [IsEmbeddedMessage](../../aspose.email/attachment/isembeddedmessage) { get; } | Ekin katıştırılmış bir mesaj olup olmadığını gösteren bir değer alır. |
| [IsUri](../../aspose.email/attachment/isuri) { get; } | Ekin URI eki olup olmadığını gösteren bir değer alır. |
| [Name](../../aspose.email/attachment/name) { get; set; } | Bir ek adı alır veya ayarlar |
| [NameEncoding](../../aspose.email/attachment/nameencoding) { get; set; } | ek adının bir kodlamasını alır veya ayarlar |
| [PreferredTextEncoding](../../aspose.email/attachment/preferredtextencoding) { get; set; } | Tercih edilen bir metin kodlamasını alır veya ayarlar |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding) { get; set; } | Aktarım kodlamasını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring)(string, ContentType) | Dizeden eki oluşturur. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring_1)(string, string) | Dizeden eki oluşturur. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring_2)(string, string, Encoding, string) | Dizeden eki oluşturur. |
| [Dispose](../../aspose.email/attachmentbase/dispose)() | Serbest bırakma, serbest bırakma veya yönetilmeyen kaynakları sıfırlama ile ilgili uygulama tanımlı görevleri gerçekleştirir. |
| virtual [Save](../../aspose.email/attachmentbase/save)(Stream) | Belirtilen akışı kaydeder. |
| virtual [Save](../../aspose.email/attachmentbase/save)(string) | Belirtilen dosya adını kaydeder. |

### Ayrıca bakınız

* class [AttachmentBase](../attachmentbase)
* interface [IAttachment](../iattachment)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* ad alanı [Aspose.Email](../../aspose.email)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->