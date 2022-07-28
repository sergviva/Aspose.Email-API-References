---
title: MapiCalendarClientIntent
second_title: Aspose.Email for .NET API Referansı
description: Kullanıcının Toplantı nesnesi üzerinde gerçekleştirebileceği eylemleri numaralandırır
type: docs
weight: 17940
url: /tr/net/aspose.email.mapi/mapicalendarclientintent/
---
## MapiCalendarClientIntent enumeration

Kullanıcının Toplantı nesnesi üzerinde gerçekleştirebileceği eylemleri numaralandırır

```csharp
[Flags]
public enum MapiCalendarClientIntent
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Manager | `1` | Kullanıcı, toplantı nesnesinin sahibidir. |
| Delegate | `2` | Kullanıcı, bir temsilcinin takvim klasöründeki bir toplantı nesnesi üzerinde hareket eden bir temsilcidir. |
| DeletedWithNoResponse | `4` | Kullanıcı, düzenleyiciye yanıt gönderilmeden toplantı nesnesini sildi. |
| DeletedExceptionWithNoResponse | `8` | Kullanıcı, düzenleyiciye yanıt gönderilmeden yinelenen bir diziye ilişkin bir istisnayı sildi. |
| RespondedTentative | `10` | Kullanıcı toplantı isteğini geçici olarak kabul etti. |
| RespondedAccept | `20` | Kullanıcı toplantı isteğini kabul etti. |
| RespondedDecline | `40` | Kullanıcı toplantı isteğini reddetti. |
| ModifiedStartTime | `80` | Kullanıcı başlangıç saatini değiştirdi. |
| ModifiedEndTime | `100` | Kullanıcı bitiş zamanını değiştirdi. |
| ModifiedLocation | `200` | Kullanıcı, toplantının yerini değiştirdi. |
| RespondedExceptionDecline | `400` | Kullanıcı, yinelenen bir diziye yönelik bir istisnayı reddetti. |
| Canceled | `800` | Kullanıcı bir toplantı isteğini iptal etti. |
| ExceptionCanceled | `1000` | Kullanıcı, yinelenen bir serinin istisnasını iptal etti. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Mapi](../../aspose.email.mapi)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->