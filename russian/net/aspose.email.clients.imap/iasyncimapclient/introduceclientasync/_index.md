---
title: IntroduceClientAsync
second_title: Справочник по Aspose.Email для .NET API
description: Вводит информацию о клиенте на сервер.
type: docs
weight: 210
url: /ru/net/aspose.email.clients.imap/iasyncimapclient/introduceclientasync/
---
## IAsyncImapClient.IntroduceClientAsync method

Вводит информацию о клиенте на сервер.

```csharp
public Task<ImapIdentificationInfo> IntroduceClientAsync(
    ImapIdentificationInfo clientIdentificationInfo, IConnection connection = null, 
    CancellationToken token = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | ImapIdentificationInfo | Соединение с сервером |
| clientIdentificationInfo | IConnection | Идентификационная информация клиента |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Возвращает идентификационную информацию сервера

### Смотрите также

* class [ImapIdentificationInfo](../../imapidentificationinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->