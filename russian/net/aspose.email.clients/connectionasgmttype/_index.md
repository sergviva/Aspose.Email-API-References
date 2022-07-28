---
title: ConnectionAsgmtType
second_title: Справочник по Aspose.Email для .NET API
description: Определяет алгоритм распределения соединений в многопоточной среде
type: docs
weight: 2910
url: /ru/net/aspose.email.clients/connectionasgmttype/
---
## ConnectionAsgmtType enumeration

Определяет алгоритм распределения соединений в многопоточной среде

```csharp
public enum ConnectionAsgmtType
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| UseMainOrDefault | `0` | Этот режим используется по умолчанию в почтовых клиентах. Почтовый клиент использует основное соединение для всех операций из нескольких потоков, если соединение по умолчанию не было создано или соединение не было явно передано как параметр метода. Основное соединение - это соединение, которое создается одновременно с почтовым клиентом. Пользователь может создавать соединения по умолчанию для потоков с помощью метода CreateConnection. Если создается подключение по умолчанию для потока, оно неявно используется для всех методов почтового клиента, которые вызываются в этом потоке. Если соединение по умолчанию для потока не создано, основное соединение используется для всех методов почтового клиента, которые вызываются в этом потоке. Пользователь также может создавать независимые соединения, не связанные с потоками (не соединения по умолчанию) с помощью метода CreateConnection. Если пользователь хочет использовать другие соединения (не основные и не по умолчанию), он должен явно передать это соединение как параметр метода, который он хочет использовать. Пользователь может дополнительно создавать любое количество подключений. Соединение по умолчанию может быть только одно на поток. Обратите внимание, что соединения по умолчанию работают правильно, если пользователь использует объекты Thread для многозадачного программирования. Если пользователь использует ConnectionPool или использует объекты Task для многозадачного программирования, этот режим может привести к неправильному поведению программы, поскольку в этом случае поток может быть повторно использован. Чтобы избежать этой проблемы, пользователь должен вручную удалить соединение по умолчанию (если он его использует) в конце кода, который выполняется в потоке. |
| UseMain | `1` | Почтовый клиент использует основное соединение для всех операций из нескольких потоков. Основное соединение - это соединение, которое создается одновременно с почтовым клиентом. Пользователь не может создавать соединения по умолчанию. Пользователь может создавать независимые соединения, не связанные с потоками (не соединения по умолчанию) с помощью метода CreateConnection. Если пользователь хочет использовать другие соединения (не основные и не по умолчанию), он должен явно передать это соединение как параметр метода, который он хочет использовать. Пользователь может дополнительно создавать любое количество подключений. |
| UseDefault | `2` | Почтовый клиент неявно использует только соединения по умолчанию для всех операций из нескольких потоков. Основное соединение в этом режиме не используется. Если для какого-то потока не было создано соединение по умолчанию (первый вызов метода почтового клиента), почтовый клиент неявно создает соединение по умолчанию для потока перед выполнением первой операции. Пользователь не может создавать подключения по умолчанию для потоков с помощью метода CreateConnection, поскольку они создаются автоматически. Когда создается соединение по умолчанию для потока, оно неявно используется для всех методов почтового клиента, которые вызываются в этом потоке. Пользователь также может создавать независимые соединения, не связанные с потоками (не соединения по умолчанию) с помощью метода CreateConnection. Если пользователь хочет использовать другие соединения (не основные и не по умолчанию), он должен явно передать это соединение как параметр метода, который он хочет использовать. Пользователь может дополнительно создавать любое количество подключений. Соединение по умолчанию может быть только одно на поток. Обратите внимание, что соединения по умолчанию работают правильно, если пользователь использует объекты Thread для многозадачного программирования. Если пользователь использует ConnectionPool или использует объекты Task для многозадачного программирования, этот режим может привести к неправильному поведению программы, поскольку в этом случае поток может быть повторно использован. Чтобы избежать этой проблемы, пользователь должен вручную удалить соединение по умолчанию в конце кода, который выполняется в потоке. |

### Смотрите также

* пространство имен [Aspose.Email.Clients](../../aspose.email.clients)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->