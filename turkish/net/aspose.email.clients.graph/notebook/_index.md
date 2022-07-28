---
title: Notebook
second_title: Aspose.Email for .NET API Referansı
description: https//docs.microsoft.com/en-us/graph/api/resources/notebookviewgraph-rest-1.0 Bir OneNote not defteri.
type: docs
weight: 16010
url: /tr/net/aspose.email.clients.graph/notebook/
---
## Notebook class

https://docs.microsoft.com/en-us/graph/api/resources/notebook?view=graph-rest-1.0 Bir OneNote not defteri.

```csharp
public class Notebook
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Notebook](notebook)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CreatedBy](../../aspose.email.clients.graph/notebook/createdby) { get; } | Öğeyi oluşturan kullanıcının, cihazın ve uygulamanın kimliği. Salt okunur. |
| [CreatedDateTime](../../aspose.email.clients.graph/notebook/createddatetime) { get; } | Not defterinin oluşturulduğu tarih ve saat. Zaman damgası, ISO 8601 biçimini kullanan tarih ve saat bilgilerini temsil eder ve her zaman UTC saatindedir. Örneğin, 1 Ocak 2014'te gece yarısı UTC şöyle görünür: '2014-01 -01T00:00:00Z'. Salt okunur. |
| [DisplayName](../../aspose.email.clients.graph/notebook/displayname) { get; set; } | Not defterinin adı. |
| [Id](../../aspose.email.clients.graph/notebook/id) { get; } | Not defterinin benzersiz tanımlayıcısı. Salt okunur. |
| [IsCreatedDateTimeSpecified](../../aspose.email.clients.graph/notebook/iscreateddatetimespecified) { get; set; } | CreatedDateTime özelliğinin belirtilip belirtilmediğini gösterir. |
| [IsDefault](../../aspose.email.clients.graph/notebook/isdefault) { get; } | Bunun, kullanıcının varsayılan not defteri olup olmadığını gösterir. Salt okunur. |
| [IsDefaultSpecified](../../aspose.email.clients.graph/notebook/isdefaultspecified) { get; set; } | IsDefault özelliğinin belirtilip belirtilmediğini gösterir. |
| [IsLastModifiedDateTimeSpecified](../../aspose.email.clients.graph/notebook/islastmodifieddatetimespecified) { get; set; } | LastModifiedDateTime özelliğinin belirtilip belirtilmediğini gösterir. |
| [IsShared](../../aspose.email.clients.graph/notebook/isshared) { get; } | Not defterinin paylaşılıp paylaşılmadığını gösterir. Doğruysa, not defterinin içeriği sahibi dışındaki kişiler tarafından görülebilir. Salt okunur. |
| [IsSharedSpecified](../../aspose.email.clients.graph/notebook/issharedspecified) { get; set; } | IsShared özelliğinin belirtilip belirtilmediğini gösterir. |
| [LastModifiedBy](../../aspose.email.clients.graph/notebook/lastmodifiedby) { get; } | Öğeyi oluşturan kullanıcının, cihazın ve uygulamanın kimliği. Salt okunur. |
| [LastModifiedDateTime](../../aspose.email.clients.graph/notebook/lastmodifieddatetime) { get; } | Not defterinin en son değiştirildiği tarih ve saat. Zaman damgası, ISO 8601 biçimini kullanan tarih ve saat bilgilerini temsil eder ve her zaman UTC saatindedir. Örneğin, 1 Ocak 2014'teki gece yarısı UTC şöyle görünür: '2014-01-01T00:00:00Z'. Salt okunur. |
| [Links](../../aspose.email.clients.graph/notebook/links) { get; set; } | Not defterini açma bağlantıları. oneNoteClientURL bağlantısı, yüklüyse not defterini OneNote yerel istemcisinde açar. oneNoteWebURL bağlantısı, not defterini web üzerinde OneNote'ta açar. |
| [SectionGroupsUrl](../../aspose.email.clients.graph/notebook/sectiongroupsurl) { get; } | Not defterindeki tüm bölüm gruplarını döndüren bölümGroups gezinme özelliğinin URL'si. Salt okunur. |
| [SectionsUrl](../../aspose.email.clients.graph/notebook/sectionsurl) { get; } | Not defterindeki tüm bölümleri döndüren bölümler gezinme özelliğinin URL'si. Salt okunur. |
| [Self](../../aspose.email.clients.graph/notebook/self) { get; } | Not defteriyle ilgili ayrıntıları alabileceğiniz uç nokta. Salt okunur. |
| [UserRole](../../aspose.email.clients.graph/notebook/userrole) { get; } | Olası değerler şunlardır: Sahip, Katkıda Bulunan, Okuyucu, Yok. Sahip, not defterine sahip düzeyinde erişimi temsil eder. Katkıda bulunan, not defterine okuma/yazma erişimini temsil eder. Okuyucu, not defterine salt okunur erişimi temsil eder. Salt okunur . |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->