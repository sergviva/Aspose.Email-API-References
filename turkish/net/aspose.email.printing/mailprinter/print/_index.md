---
title: Print
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen MSG nesnesini istenen biçimi kullanarak yazdırır.
type: docs
weight: 130
url: /tr/net/aspose.email.printing/mailprinter/print/
---
## Print(MapiMessage, string, PrintFormat) {#print_3}

Belirtilen MSG nesnesini istenen biçimi kullanarak yazdırır.

```csharp
public void Print(MapiMessage message, string outputFile, PrintFormat printingFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MapiMessage | Yazdırılacak MSG dosyası. |
| outputFile | String | Çıktı dosyası. |
| printingFormat | PrintFormat | Baskı formatı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | Eğer*printingFormat* desteklenmiyor. |
| ArgumentNullException | Argümanlardan biri boşsa. |
| InvalidOperationException | Nesne işlenemiyorsa. |

### Ayrıca bakınız

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* enum [PrintFormat](../../printformat)
* class [MailPrinter](../../mailprinter)
* ad alanı [Aspose.Email.Printing](../../mailprinter)
* toplantı [Aspose.Email](../../../)

---

## Print(MapiMessage, Stream, PrintFormat) {#print_2}

Belirtilen MSG nesnesini istenen biçimi kullanarak yazdırır.

```csharp
public void Print(MapiMessage message, Stream outputStream, PrintFormat printingFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MapiMessage | Yazdırılacak MSG dosyası. |
| outputStream | Stream | Çıkış akışı. |
| printingFormat | PrintFormat | Baskı formatı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | Eğer*printingFormat* desteklenmiyor. |
| ArgumentNullException | Argümanlardan biri boşsa. |
| InvalidOperationException | Nesne işlenemiyorsa. |

### Ayrıca bakınız

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* enum [PrintFormat](../../printformat)
* class [MailPrinter](../../mailprinter)
* ad alanı [Aspose.Email.Printing](../../mailprinter)
* toplantı [Aspose.Email](../../../)

---

## Print(MailMessage, string, PrintFormat) {#print_1}

Belirtilen mesaj nesnesini istenen biçimi kullanarak yazdırır.

```csharp
public void Print(MailMessage message, string outputFile, PrintFormat printingFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MailMessage | Yazdırılacak MSG dosyası. |
| outputFile | String | Çıktı dosyası. |
| printingFormat | PrintFormat | Baskı formatı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | Eğer*printingFormat* desteklenmiyor. |
| ArgumentNullException | Argümanlardan biri boşsa. |
| InvalidOperationException | Nesne işlenemiyorsa. |

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* enum [PrintFormat](../../printformat)
* class [MailPrinter](../../mailprinter)
* ad alanı [Aspose.Email.Printing](../../mailprinter)
* toplantı [Aspose.Email](../../../)

---

## Print(MailMessage, Stream, PrintFormat) {#print}

Belirtilen mesaj nesnesini istenen biçimi kullanarak yazdırır.

```csharp
public void Print(MailMessage message, Stream outputStream, PrintFormat printingFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MailMessage | Yazdırılacak MSG dosyası. |
| outputStream | Stream | Çıkış akışı. |
| printingFormat | PrintFormat | Baskı formatı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | Eğer*printingFormat* desteklenmiyor. |
| ArgumentNullException | Argümanlardan biri boşsa. |
| InvalidOperationException | Nesne işlenemiyorsa. |

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* enum [PrintFormat](../../printformat)
* class [MailPrinter](../../mailprinter)
* ad alanı [Aspose.Email.Printing](../../mailprinter)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->