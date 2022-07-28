---
title: ItemOperationsFetchRequest
second_title: Aspose.Email for .NET API Referansı
description: Sunucudan bir öğenin alınmasıyla ilgili isteği içerir.
type: docs
weight: 1420
url: /tr/net/aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/
---
## ItemOperationsFetchRequest class

Sunucudan bir öğenin alınmasıyla ilgili isteği içerir.

```csharp
public class ItemOperationsFetchRequest
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ItemOperationsFetchRequest](itemoperationsfetchrequest)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/collectionid) { get; set; } | Alınan klasörü tanımlar. |
| [FileReference](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/filereference) { get; set; } | Sunucu tarafından her eke atanan benzersiz bir tanımlayıcı belirtir. Bir ItemOperations isteğinde, Getirme başına yalnızca bir FileReference tanımlayıcısı bulunabilir. Bu kısıtlamanın ihlali, sunucudan 2 Durum öğesi değerinin döndürülmesine neden olur. Ancak istemci, ek başına bir Getirme düğümü kullanarak birden çok ek alabilir. |
| [LinkId](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/linkid) { get; set; } | Sunucu tarafından Windows SharePoint Services veya UNC belgeleri gibi belirli kaynaklara atanan bir Tekdüzen Kaynak Tanımlayıcısı (URI) belirtir. LinkId, bir öğenin konumuna başvurmak için kullanılabilir. |
| [LongId](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/longid) { get; set; } | Bir önceki Arama yanıtı tarafından döndürülen her sonuca sunucu tarafından atanan benzersiz bir tanımlayıcı belirtir. Uzun Kimlik değeri en fazla 256 karakter uzunluğunda olabilir. |
| [Options](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/options) { get; set; } | ItemOperations.Fetch işlemi için seçenekleri içerir. |
| [RemoveRightsManagementProtection](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/removerightsmanagementprotection) { get; set; } | Varsa veya doğruysa, istemcinin e-postadan IRM korumasını kaldırdığını gösterir. IRM koruması yalnızca ExportAllowed öğesi TRUE olarak ayarlandığında e-posta iletilerinden kaldırılabilir. |
| [ServerId](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/serverid) { get; set; } | Sunucu tarafından kendisine bir öğe işlemi uygulanan her nesneye atanan benzersiz bir tanımlayıcı belirtir. |
| [Store](../../aspose.email.clients.activesync.transportlayer/itemoperationsfetchrequest/store) { get; set; } | Üst işlemin uygulanacağı mağazanın adını belirtir. Aşağıdaki değerler Mağaza öğesi için geçerlidir: - Belge Kitaplığı (Microsoft SharePoint Server ve UNC bağlantıları) - Posta kutusu (öğeler ve ekler) |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->