---
title: IActivityClient
second_title: Справочник по Aspose.Email для .NET API
description: Представляет интерфейс для клиента Exchange REST.
type: docs
weight: 2570
url: /ru/net/aspose.email.clients.activity/iactivityclient/
---
## IActivityClient interface

Представляет интерфейс для клиента Exchange REST.

```csharp
public interface IActivityClient : IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.activity/iactivityclient/multipleservicestokenprovider) { get; set; } | Получает или задает объект, позволяющий получить маркер доступа OAuth. |
| [Proxy](../../aspose.email.clients.activity/iactivityclient/proxy) { get; set; } | Получает или устанавливает данные для прокси-доступа к серверу Exchange. |
| [ResourceId](../../aspose.email.clients.activity/iactivityclient/resourceid) { get; set; } | Получает или устанавливает идентификатор ресурса. Например, для пользователей это может быть основное имя пользователя (UPN) или идентификатор пользователя |
| [TenantId](../../aspose.email.clients.activity/iactivityclient/tenantid) { get; set; } | Получает или задает идентификатор арендатора |
| [Timeout](../../aspose.email.clients.activity/iactivityclient/timeout) { get; set; } | Получает или задает количество миллисекунд ожидания до истечения времени ожидания операции. Значение по умолчанию — 100 000 миллисекунд (100 секунд). |
| [TokenProvider](../../aspose.email.clients.activity/iactivityclient/tokenprovider) { get; set; } | Получает или задает объект, позволяющий получить маркер доступа OAuth. |

## Методы

| Имя | Описание |
| --- | --- |
| [FetchContent](../../aspose.email.clients.activity/iactivityclient/fetchcontent)(string) | Эта операция извлекает содержимое, доступное в настоящее время для извлечения для указанного идентификатора содержимого. |
| [ListContent](../../aspose.email.clients.activity/iactivityclient/listcontent#listcontent)(string) | Эта операция выводит список содержимого, доступного в настоящее время для извлечения для указанного типа содержимого. Контент представляет собой совокупность действий и событий, собранных с нескольких серверов в нескольких центрах обработки данных. Контент будет указан в том порядке, в котором агрегации становятся доступными, но последовательность событий и действий в агрегациях не гарантируется. По умолчанию, если startTime и endTime опущены, возвращается содержимое, доступное за последние 24 часа. |
| [ListContent](../../aspose.email.clients.activity/iactivityclient/listcontent#listcontent_1)(string, DateTime?, DateTime?) | Эта операция выводит список содержимого, доступного в настоящее время для извлечения для указанного типа содержимого. Контент представляет собой совокупность действий и событий, собранных с нескольких серверов в нескольких центрах обработки данных. Контент будет указан в том порядке, в котором агрегации становятся доступными, но последовательность событий и действий в агрегациях не гарантируется. |
| [ListFriendlyNames](../../aspose.email.clients.activity/iactivityclient/listfriendlynames)() | Эта операция извлекает понятные имена для объектов в потоке данных, идентифицированных с помощью идентификаторов. |
| [ListSubscriptions](../../aspose.email.clients.activity/iactivityclient/listsubscriptions)() | Эта операция возвращает набор текущих подписок вместе со связанными веб-перехватчиками. |
| [StartSubscription](../../aspose.email.clients.activity/iactivityclient/startsubscription)(string, Webhook) | Запускает подписку на указанный тип контента. Если подписка на указанный тип контента уже существует, эта операция используется для: - обновления свойств активного вебхука - включения вебхука который был отключен из-за чрезмерного количества неудачных уведомлений - повторно включить веб-перехватчик с истекшим сроком действия, указав более позднюю или нулевую дату истечения срока действия - удалить веб-перехватчик |
| [StopSubscription](../../aspose.email.clients.activity/iactivityclient/stopsubscription)(string) | Эта операция останавливает подписку на указанный тип контента. Когда подписка остановлена, вы больше не будете получать уведомления и не сможете получить доступный контент. Если позже подписка будет перезапущена, с этого момента у вас будет доступ к новому контенту. Вы не сможете получить контент, который был доступен в период между остановкой и перезапуском подписки. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->