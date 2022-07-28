---
title: Search
second_title: Aspose.Email for .NET API Referansı
description: ActiveSync protokolünün ad alanını arayın
type: docs
weight: 1930
url: /tr/net/aspose.email.clients.activesync.transportlayer/search/
---
## Search enumeration

ActiveSync protokolünün ad alanını arayın

```csharp
public enum Search
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Search | `5` | HTTP POST gövdesinin bir Arama komutu içerdiğini tanımlar (bölüm 2.2.2.14). XML akışındaki en üst düzey öğedir. |
| Store | `7` | Arama için konumu, dizeyi ve seçenekleri belirten öğeleri içerir. |
| Name | `8` | Aranacak mağazayı belirtir. |
| Query | `9` | Aranan mağazadaki girişleri eşleştirmek için kullanılacak anahtar sözcükleri belirtir. |
| Options | `10` | Arama seçeneklerini içerir. |
| Range | `11` | Döndürülecek maksimum eşleşen giriş sayısını belirtir. |
| Status | `12` | Bir işlemin sonucunu gösterir. |
| Response | `13` | Sunucudan döndürülen arama sonuçlarını içerir. |
| Result | `14` | Eşleşen tek bir posta kutusu öğesi için bir kapsayıcı sunar. |
| Properties | `15` | Yanıttaki öğeler için döndürülen özellikleri içerir. |
| Total | `16` | Arama Sorgusu öğesi (bölüm 2.2.3.129) değeriyle eşleşen toplam posta kutusu girişi sayısının bir tahminini sağlar. |
| EqualTo | `17` | Bir arama sırasında eşitlik açısından karşılaştırılan bir özellik ve bir değer içerir. |
| Value | `18` | Karşılaştırmada kullanılacak değeri belirtir. |
| And | `19` | Bir AND işleminin gerçekleştirileceği öğeleri belirtir. |
| Or | `20` | Bir VEYA işleminin gerçekleştirileceği öğeleri belirtir. |
| FreeText | `21` | Aranacak bir dize değeri belirtir. |
| DeepTraversal | `23` | İstemcinin, sunucunun sorguda belirtilen klasörler için tüm alt klasörleri aramasını istediğini belirtir. |
| LongId | `24` | Döndürülen her sonuç kümesine sunucu tarafından atanan benzersiz bir tanımlayıcı belirtir. |
| RebuildResults | `25` | Sunucuyu, belirli bir sorguya karşılık gelen arama klasörünü (2) yeniden oluşturmaya zorlar. |
| LessThan | `26` | Bir arama sırasında "küçüktür" koşulu için karşılaştırılan bir özelliği ve değeri belirtir. |
| GreaterThan | `27` | Bir arama sırasında "büyüktür" koşulu için karşılaştırılan bir özelliği ve değeri belirtir. |
| UserName | `30` | Belge kitaplığından belge aramak için kullanılan kullanıcı hesabını belirtir. |
| Password | `31` | Verilen KullanıcıAdı için parolayı belirtir (bölüm 2.2.3.177.2). |
| ConversationId | `32` | Aranacak konuşmayı belirtir. |
| Picture | `33` | İstemcinin, sunucu yanıtında kişi fotoğraflarının gönderilmesini istediğini belirtir. |
| MaxSize | `34` | Sunucu yanıtında döndürülen kişi fotoğraflarının boyutunu sınırlar. |
| MaxPictures | `35` | Sunucu yanıtında döndürülen kişi fotoğraflarının sayısını sınırlar. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->