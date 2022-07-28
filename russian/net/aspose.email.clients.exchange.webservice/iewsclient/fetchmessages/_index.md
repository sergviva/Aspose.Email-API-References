---
title: FetchMessages
second_title: Справочник по Aspose.Email для .NET API
description: Выбирает указанные сообщения
type: docs
weight: 820
url: /ru/net/aspose.email.clients.exchange.webservice/iewsclient/fetchmessages/
---
## FetchMessages(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) {#fetchmessages_2}

Выбирает указанные сообщения

```csharp
public MailMessageCollection FetchMessages(IEnumerable<string> uris, 
    IEnumerable<PropertyDescriptor> extendedProperties)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uris | IEnumerable`1 | AStringCollectionсодержит URI сообщения, которое необходимо получить |
| extendedProperties | IEnumerable`1 | Перечисление расширенных свойств |

### Возвращаемое значение

A[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)содержащий извлеченные сообщения

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *uris*is` null` |

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessages(IEnumerable&lt;string&gt;) {#fetchmessages_1}

Выбирает указанные сообщения

```csharp
public MailMessageCollection FetchMessages(IEnumerable<string> uris)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uris | IEnumerable`1 | AStringCollectionсодержащий URI сообщения для извлечения |

### Возвращаемое значение

A[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)содержащие извлеченные сообщения

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *uris*is` null` |

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessages(IEnumerable&lt;ExchangeMessageInfo&gt;) {#fetchmessages}

Выбирает указанные сообщения

```csharp
public MailMessageCollection FetchMessages(IEnumerable<ExchangeMessageInfo> messageInfos)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfos | IEnumerable`1 | AIEnumerable&lt;ExchangeMessageInfo&gt; "/&gt; извлекаемых сообщений |

### Возвращаемое значение

A[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)содержащий извлеченные сообщения

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *messageInfos*is` null` |

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [ExchangeMessageInfo](../../../aspose.email.clients.exchange/exchangemessageinfo)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessages(StringCollection) {#fetchmessages_3}

Выбирает указанные сообщения

```csharp
public MailMessageCollection FetchMessages(StringCollection messageUris)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageUris | StringCollection | AStringCollectionсодержащий URI сообщения, который необходимо получить |

### Возвращаемое значение

A[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)содержащие извлеченные сообщения

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *messageUris*is` null` |

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->