---
title: Search
second_title: Справочник по Aspose.Email для .NET API
description: Поиск пространства имен протокола ActiveSync
type: docs
weight: 1930
url: /ru/net/aspose.email.clients.activesync.transportlayer/search/
---
## Search enumeration

Поиск пространства имен протокола ActiveSync

```csharp
public enum Search
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Search | `5` | Идентифицирует тело HTTP POST как содержащее команду поиска (раздел 2.2.2.14). Это элемент верхнего уровня в XML-потоке. |
| Store | `7` | Содержит элементы, определяющие местоположение, строку и параметры поиска. |
| Name | `8` | Указывает хранилище для поиска. |
| Query | `9` | Указывает ключевые слова, используемые для сопоставления записей в искомом хранилище. |
| Options | `10` | Содержит параметры поиска. |
| Range | `11` | Задает максимальное количество возвращаемых совпадающих записей. |
| Status | `12` | Указывает результат операции. |
| Response | `13` | Содержит результаты поиска, возвращаемые сервером. |
| Result | `14` | Служит контейнером для отдельного соответствующего элемента почтового ящика. |
| Properties | `15` | Содержит свойства, возвращаемые для элементов в ответе. |
| Total | `16` | Предоставляет оценку общего количества записей почтового ящика, соответствующих значению элемента запроса поиска (раздел 2.2.3.129). |
| EqualTo | `17` | Содержит свойство и значение, которые сравниваются на равенство во время поиска. |
| Value | `18` | Задает значение, которое будет использоваться при сравнении. |
| And | `19` | Задает элементы, над которыми выполняется операция И. |
| Or | `20` | Задает элементы, над которыми выполняется операция ИЛИ. |
| FreeText | `21` | Задает строковое значение для поиска. |
| DeepTraversal | `23` | Указывает, что клиент хочет, чтобы сервер выполнял поиск во всех подпапках папок, указанных в запросе. |
| LongId | `24` | Задает уникальный идентификатор, назначаемый сервером каждому возвращаемому набору результатов. |
| RebuildResults | `25` | Заставляет сервер перестроить папку поиска (2), соответствующую заданному запросу. |
| LessThan | `26` | Указывает свойство и значение, которые сравниваются для условия "меньше чем" во время поиска. |
| GreaterThan | `27` | Указывает свойство и значение, которые сравниваются для условия "больше чем" во время поиска. |
| UserName | `30` | Указывает учетную запись пользователя, используемую для поиска документа в библиотеке документов. |
| Password | `31` | Указывает пароль для данного имени пользователя (раздел 2.2.3.177.2). |
| ConversationId | `32` | Указывает диалог, который необходимо найти. |
| Picture | `33` | Указывает, что клиент запрашивает, чтобы фотографии контактов возвращались в ответе сервера. |
| MaxSize | `34` | Ограничивает размер фотографий контактов, возвращаемых в ответе сервера. |
| MaxPictures | `35` | Ограничивает количество фотографий контактов, возвращаемых в ответе сервера. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->