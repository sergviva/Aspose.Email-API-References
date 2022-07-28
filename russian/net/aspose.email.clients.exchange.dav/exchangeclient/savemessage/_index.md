---
title: SaveMessage
second_title: Справочник по Aspose.Email для .NET API
description: Сохраняет почтовое сообщение указанное uri в локальной файловой системе. Файл почтового сообщения имеет формат совместимый с RFC 822 EML.  если вы хотите проанализировать файлы почтовых сообщений используйтеMailMessageaspose.email/mailmessage.
type: docs
weight: 360
url: /ru/net/aspose.email.clients.exchange.dav/exchangeclient/savemessage/
---
## SaveMessage(string, string) {#savemessage_1}

Сохраняет почтовое сообщение, указанное uri, в локальной файловой системе. Файл почтового сообщения имеет формат, совместимый с RFC 822 (EML).  если вы хотите проанализировать файлы почтовых сообщений, используйте[`MailMessage`](../../../aspose.email/mailmessage).

```csharp
public void SaveMessage(string messageUri, string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageUri | String | Uri почтового сообщения |
| path | String | Целевой путь для сохранения сообщения |

### Смотрите также

* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessage(string, Stream) {#savemessage}

Сохраняет сообщение.

```csharp
public void SaveMessage(string messageUri, Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageUri | String | URI сообщения. |
| stream | Stream | Поток. |

### Смотрите также

* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->