---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Справочник по Aspose.Email для .NET API
description: 
type: docs
weight: 80
url: /ru/net/aspose.email.clients.activesync.transportlayer/
---


## Классы

| Учебный класс | Описание |
| --- | --- |
| [AccountInformation](./accountinformation) | Содержит информацию об учетной записи пользователя. |
| [ActiveSyncTLClient](./activesynctlclient) | Базовый класс для клиентских реализаций ActiveSync |
| [AutodiscoverResult](./autodiscoverresult) | Результат операции автообнаружения |
| [Body](./body) | Задает поле данных произвольной формы переменной длины, связанное с элементом, хранящимся на сервере. |
| [BodyPart](./bodypart) | Указывает сведения о части сообщения электронной почты в ответе. Элемент BodyPart ДОЛЖЕН быть включен в ответ на команду, когда BodyPartPreference указан в запросе. |
| [BodyPreference](./bodypreference) | Содержит информацию о предпочтениях, связанную с типом и размером информации, возвращаемой при поиске, синхронизации или выборке. |
| [CertificateStatuses](./certificatestatuses) | Указывает, успешно ли прошел проверку сертификат. |
| [DataContainer](./datacontainer) | Содержит данные для определенного объекта, такого как контакт, сообщение электронной почты, встреча в календаре или элемент задачи. Контейнер данных можно использовать для изменения элементов, добавления элементов или получения элементов на клиентском устройстве или сервере. |
| [DeviceInformation](./deviceinformation) | Запрос, который используется для отправки свойств клиентского устройства на сервер. |
| [DevicePasswordRequest](./devicepasswordrequest) | Указывает запрос на установку сервером пароля восстановления клиентского устройства. Чтобы очистить существующий пароль восстановления, клиент ДОЛЖЕН отправить пустой пароль. |
| [EASProvisionDoc](./easprovisiondoc) | Задает набор параметров безопасности для подготовки устройства. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Содержит запрос на удаление содержимого папки. EmptyFolderContents поддерживает единственный дочерний элемент элемента Options, DeleteSubFolders, который определяет, удаляются ли вложенные папки, содержащиеся в папке. Если параметр DeleteSubFolders не включен в запрос, вложенные папки указанного CollectionId не удаляются. |
| [FolderInfo](./folderinfo) | Класс FolderInfo содержит информацию о папке |
| [FolderSyncResult](./foldersyncresult) | Содержит изменения в иерархии папок. |
| [ItemEstimate](./itemestimate) | Содержит оценку запрошенной папки |
| [ItemEstimateOptions](./itemestimateoptions) | Содержит элементы, фильтрующие результаты операции GetItemEstimate. |
| [ItemEstimateRequest](./itemestimaterequest) | Содержит параметры запроса ItemEstimate |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Идентифицирует тело ответа как содержащее операцию, удаляющую содержимое папки. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Содержит свойства, возвращаемые для элементов в ответе. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Содержит запрос на получение элемента с сервера. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Содержит ответ о получении элементов с сервера. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Содержит запрос на перемещение беседы в определенную папку. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Идентифицирует тело ответа как содержащее операцию, перемещающую данный диалог. |
| [ItemOperationsRequest](./itemoperationsrequest) | Содержит запрос ItemOperations. |
| [ItemOperationsResponse](./itemoperationsresponse) | Содержит ответ ItemOperations. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | Содержит параметры операции ItemOperations.EmptyFolderContents |
| [ItOpFetchOptions](./itopfetchoptions) | Содержит параметры операции ItemOperations.Fetch. |
| [ItOpMoveOptions](./itopmoveoptions) | Содержит параметры операции ItemOperations.Move. |
| [MeetingResponseRequest](./meetingresponserequest) | Указывает приглашение на собрание, на которое выполняется ответ, ответ на это приглашение и папку на сервере, в которой находится приглашение на собрание. |
| [MeetingResponseResult](./meetingresponseresult) | Объект результата ответа на встречу |
| [MoveItemData](./moveitemdata) | Содержит информацию о перемещении предметов |
| [MoveItemResponse](./moveitemresponse) | Содержит информацию, описывающую перемещенные элементы. |
| [OOFMessage](./oofmessage) | Определяет сообщение OOF для определенной аудитории. Exchange 2007, Exchange 2010 и Exchange 2013 требуют, чтобы ответное сообщение для неизвестной внешней и известной внешней аудитории было одинаковым. Свойство поддерживает следующие три аудитории для сообщения OOF: Внутренний — пользователь, который находится в той же организации, что и отправляющий пользователь. Известный внешний — пользователь, который не входит в организацию отправляющего пользователя, но представлен в контактах отправляющего пользователя. Неизвестный внешний — пользователь, который не входит в организацию отправляющего пользователя и не представлен в контактах отправляющего пользователя. |
| [OOFReqParametrs](./oofreqparametrs) | Получает настройки информации OOF с сервера. |
| [OOFRequest](./oofrequest) | Указывает класс для получения и установки информации об отсутствии на работе (OOF). |
| [OOFResponse](./oofresponse) | Указывает класс для получения и установки информации об отсутствии на работе (OOF). |
| [OOFSettings](./oofsettings) | Настройки информации OOF. |
| [PictureRequest](./picturerequest) | Указывает, что клиент запрашивает возврат фотографий в ответе сервера. Изображение не поддерживается при версии протокола 12.1 или 14.0. Содержит данные, связанные с запросом фотографий. |
| [PictureRespose](./picturerespose) | Содержит данные, относящиеся к фотографиям контактов. Изображение не поддерживается при версии протокола 12.1 или 14.0. |
| [PingParameter](./pingparameter) | Содержит параметры команды ping |
| [ProvisionPolicy](./provisionpolicy) | Задает политику безопасности. |
| [ProvisionPolicyData](./provisionpolicydata) | Указывает параметры политики. |
| [ProvisionRequest](./provisionrequest) | Содержит информацию запроса для команды предоставления |
| [ProvisionResponse](./provisionresponse) | Содержит ответную информацию для команды предоставления |
| [QueryType](./querytype) | Указывает ключевые слова, используемые для сопоставления записей в искомом хранилище. Значение запроса используется в качестве шаблона сопоставления строки префикса и возвращает записи, соответствующие началу строки. Например, при поиске "Джон" будет найдено "Джон Фрум" или "Барри Джонсон", но не будет найдено "Джеймс Литтлджон". Все непустые текстовые свойства в глобальном списке адресов, индексированные с помощью ANR, сравниваются со значением элемента Query. Поисковые сравнения выполняются с использованием сопоставления без учета регистра. Для поиска в библиотеке документов Windows SharePoint Services этот протокол поддерживает запросы следующей формы: LinkId == значение, где значение указывает URL-адрес элемента или папки, а LinkId указывает что значение должно сравниваться со свойством идентификатора ссылки. Для поиска в почтовом ящике синтаксис запроса следующий: - Папки могут быть указаны следующими способами: Указанный ID Указанная папка и подпапки Все папки электронной почты, включая черновики, входящие и подпапки, исходящие и отправленные - Базовый запрос по ключевым словам может состоять из следующих элементов: Базовый оператор:And (раздел 2.2.3.10) Фильтр dateTime, указанный с использованием элементов GreaterThan (раздел 2.2.3.78) и LessThan (раздел 2.2.3.87) Элементы FreeText (раздел 2.2.3.73), содержащие ключевые слова Базовый запрос по ключевым словам выполняется для всех проиндексированных свойств. |
| [Recipient](./recipient) | Представляет одного получателя, который был разрешен. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Указывает серверу, что данные о занятости запрашиваются клиентом, и определяет время начала и окончания получения данных о занятости. Доступность не поддерживается, если используется версия протокола 12.1. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | Идентифицирует статус и данные о занятости пользователей или списков рассылки, указанных в запросе, для времени, указанного StartTime и EndTime. Когда доступность включена в запрос ResolveRecipients, сервер извлекает информацию о занятости для пользователей, указанных в элементах To, включенных в запрос, и возвращает информацию о занятости в MergedFreeBusy в ответе. . Когда сервер анализирует запрос, сервер сначала разрешает получателей, идентифицированных элементами To, а затем определяет информацию о занятости пользователей за указанный промежуток времени, прежде чем возвращать данные о занятости в СлияниеFreeBusy. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Содержит информацию о сертификатах получателя. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Содержит опции для разрешения списка получателей. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Содержит информацию для разрешения получателей. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Содержит информацию о том, был ли разрешен получатель. Если получатель был разрешен, он также содержит тип получателя, адрес электронной почты, на который получатель разрешил, и, необязательно, сертификат S/MIME для получателя. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Содержит настройки информации об управлении правами, полученные с сервера. |
| [RightsManagementLicense](./rightsmanagementlicense) | Содержит параметры шаблона политики прав для шаблона, примененного к синхронизируемому сообщению электронной почты. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | Содержит идентификатор шаблона, имя и описание шаблона политики прав, доступного на клиенте. |
| [SearchCondition](./searchcondition) | Задает условие для поисковых запросов |
| [SearchOptions](./searchoptions) | Содержит параметры поиска. Имя пользователя и пароль могут быть отправлены в запросе только после получения значения состояния 14. Серверу требуются эти учетные данные для доступа к запрошенным ресурсам. Клиент ДОЛЖЕН отправлять их только через безопасное или доверенное соединение и только в ответ на значение состояния 14. Поддерживаемые параметры зависят от хранилища, в котором выполняется поиск. . В следующей таблице перечислены допустимые параметры для каждого хранилища. GAL:диапазон, имя пользователя, пароль, изображение Почтовый ящик:диапазон, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary:диапазон, имя пользователя, пароль BodyPartPreference действителен только в запросах команд поиска, которые включают ConversationId. |
| [SearchQuery](./searchquery) | Указывает ключевые слова, используемые для сопоставления записей в искомом хранилище. Значение запроса используется в качестве шаблона сопоставления строки префикса и возвращает записи, соответствующие началу строки. Например, при поиске "Джон" будет найдено "Джон Фрум" или "Барри Джонсон", но не будет найдено "Джеймс Литтлджон". Все непустые текстовые свойства в глобальном списке адресов, индексированные с помощью ANR, сравниваются со значением элемента Query. Поисковые сравнения выполняются с использованием сопоставления без учета регистра. Для поиска в библиотеке документов Windows SharePoint Services этот протокол поддерживает запросы в следующей форме:LinkId == значение, где значение указывает URL-адрес элемента или папки, а LinkId указывает что значение должно сравниваться со свойством идентификатора ссылки. Для поиска в почтовом ящике синтаксис запроса следующий: - Папки могут быть указаны следующими способами: Указанный ID Указанная папка и подпапки Все папки электронной почты, включая черновики, входящие и подпапки, исходящие и отправленные - Базовый запрос по ключевым словам может состоять из следующих элементов: Базовый оператор:And (раздел 2.2.3.10) Фильтр dateTime, указанный с использованием элементов GreaterThan (раздел 2.2.3.78) и LessThan (раздел 2.2.3.87) Элементы FreeText (раздел 2.2.3.73), содержащие ключевые слова Базовый запрос по ключевым словам выполняется для всех проиндексированных свойств. |
| [SearchRequest](./searchrequest) | Содержит информацию поискового запроса |
| [SearchRequestStore](./searchrequeststore) | Укажите имя, запрос и параметры поиска. |
| [SearchResponse](./searchresponse) | Содержит информацию ответа на поиск |
| [SearchResponseStore](./searchresponsestore) | Содержит элементы Status, Result, Range и Total для возвращенных записей почтового ящика. |
| [SearchResult](./searchresult) | Контейнер для отдельного соответствующего элемента почтового ящика. Когда искомым хранилищем является почтовый ящик: - Существует один элемент Result для каждого совпадения, найденного в почтовом ящике. Если совпадений не найдено, пустой элемент Result присутствует в элементе контейнера Store XML-файла ответа. - Внутри элемента Result элемент Properties содержит список запрошенных свойств для элемента почтового ящика. Когда искомое хранилище является библиотекой документов: - Первый результат, возвращаемый в ответе поиска, — это метаданные для корневой папки или элемента, к которому относится LinkId. значение указывает. Клиент может игнорировать эту запись, если она ему не требуется. - Если значение элемента documentlibrary:LinkId в запросе указывает на папку, свойства метаданных папки возвращаются в качестве первого элемента, а содержимое папки возвращается в качестве последующих результатов. Диапазон применяется к этим результатам без разницы; например, индекс 0 всегда будет для корневого элемента, на который указывает ссылка. - Если значение элемента documentlibrary:LinkId в запросе указывает на элемент, возвращается только один результат:метаданные для элемента. - Внутри элемента Result элемент Properties содержит список запрошенных свойств для элемента почтового ящика. |
| [SearchResultProperties](./searchresultproperties) | Свойства ответа на команду поиска представляют собой контейнер для свойств, которые применяются к отдельной записи, соответствующей строке поиска элемента запроса. Например, элемент Properties содержит элемент для каждого непустого свойства GAL с текстовым значением, присоединенного к соответствующей записи GAL. Возвращаются только те свойства, которые присоединены к определенной записи глобального списка адресов. поэтому в XML-ответе могут быть возвращены разные наборы свойств для разных совпадающих записей глобального списка адресов. Каждый элемент в контейнере Properties ограничен соответствующим пространством имен, указанным в элементе Search верхнего уровня. |
| [ServerInfo](./serverinfo) | Настройки сервера в операции автообнаружения |
| [SettingsRequest](./settingsrequest) | Команда "Параметры" поддерживает операции получения и установки глобальных свойств и параметров "Нет на месте" (OOF) для пользователя. Команда Settings также отправляет информацию об устройстве на сервер, осуществляет восстановление пароля/личного идентификационного номера (PIN) устройства и извлекает список адресов электронной почты пользователя. |
| [SettingsResponse](./settingsresponse) | Задает ответ с параметрами "Нет на месте" (OOF) и списком учетных записей пользователя. |
| [SmartRequest](./smartrequest) | Содержит информацию об интеллектуальном запросе |
| [SmartRequestSource](./smartrequestsource) | Содержит информацию об исходном сообщении. |
| [Status](./status) | Указывает результат операции. |
| [SyncAddClientOperation](./syncaddclientoperation) | Создает новый объект в коллекции на клиенте. |
| [SyncAddResponse](./syncaddresponse) | Служит для указания того, что в коллекции должен быть создан новый объект. |
| [SyncAddServerOperation](./syncaddserveroperation) | Создает новый объект в коллекции на сервере. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | Содержит измененные свойства существующего объекта на клиентском устройстве. Измененный объект идентифицируется его элементом ServerId. |
| [SyncChangeResponse](./syncchangeresponse) | Служит для индикации того, что объект был изменен. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Содержит свойства существующего объекта на сервере, которые были изменены. Измененный объект идентифицируется его элементом ServerId. |
| [SyncCollectionRequest](./synccollectionrequest) | Класс содержит команды и параметры, применимые к конкретной коллекции. |
| [SyncCollectionResponse](./synccollectionresponse) | Класс содержит команды и параметры, которые применяются к ответу синхронизации. |
| [SyncCommandsRequest](./synccommandsrequest) | Содержит операции, которые применяются к коллекции. Доступные операции:«Добавить», «Удалить», «Изменить», «Выбрать» и «Мягкое удаление». |
| [SyncCommandsResponse](./synccommandsresponse) | Содержит операции, которые применяются к коллекции. Доступные операции:«Добавить», «Удалить», «Изменить», «Выбрать» и «Мягкое удаление». |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | Удаляет объект на клиентском устройстве или сервере. Объект идентифицируется по его ServerId. |
| [SyncFetchResponse](./syncfetchresponse) | Запрашивает прикладные данные элемента, который был усечен в ответе синхронизации с сервера. |
| [SyncOperationResponse](./syncoperationresponse) | Базовый абстрактный класс для ответов операции синхронизации |
| [SyncOperationsResponse](./syncoperationsresponse) | Содержит ответы на такие операции, как Add, Fetch, Change, которые обрабатываются сервером. Ответ содержит код состояния и другую информацию, в зависимости от операции. |
| [SyncOptions](./syncoptions) | Указывает параметры, управляющие определенными аспектами выполнения синхронизации. |
| [SyncRequest](./syncrequest) | Содержит параметры запроса синхронизации |
| [UserInformationResponse](./userinformationresponse) | Содержит статус запроса и список информации об учетной записи пользователя (адреса электронной почты). |
| [ValueConverter](./valueconverter) | Класс преобразует версию протокола ActiveSync из строкового представления в перечисление и обратно. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | Клиентский интерфейс ActiveSync |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Базовый клиентский интерфейс ActiveSync |
## перечисление

| перечисление | Описание |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Enum определяет тип аутентификации |
| [AirSync](./airsync) | Пространство имен AirSync протокола ActiveSync |
| [AirSyncBase](./airsyncbase) | Пространство имен AirSyncBase протокола ActiveSync |
| [AirsyncClass](./airsyncclass) | Идентифицирует класс предмета. Следующие классы поддерживаются для поиска в почтовых ящиках при версии протокола 12.1: - Электронная почта - Календарь - Контакты - Задачи Классы SMS и Notes доступны только при версии протокола 14.0 или 14.1. |
| [AirsyncFilterType](./airsyncfiltertype) | Задает дополнительное временное окно для объектов |
| [AllowBluetooth](./allowbluetooth) | Указывает использование Bluetooth на устройстве. |
| [ASProtocolVersions](./asprotocolversions) | ASProtocolVersions указывает версии протокола ActiveSync. |
| [BehaviorReplacement](./behaviorreplacement) | Указывает, как разрешать конфликт, возникающий при изменении объекта как на клиенте, так и на сервере. Значение указывает, какой объект — объект клиента или объект сервера — следует сохранить в случае конфликта. |
| [BodyType](./bodytype) | Указывает тип формата основного содержимого элемента. |
| [Calendar](./calendar) | Пространство имен календаря протокола ActiveSync |
| [CertificateRetrieval](./certificateretrieval) | Указывает, ДОЛЖЕН ли сервер возвращать сертификаты S/MIME для каждого разрешенного получателя. |
| [CommandCodes](./commandcodes) | В следующей таблице представлены числовые коды, соответствующие командам ActiveSync. Числовой код используется в поле кода команды URI в кодировке base64 для указания команды. |
| [CommandParameters](./commandparameters) | Параметры команды. |
| [ComposeMail](./composemail) | Пространство имен ComposeMail протокола ActiveSync |
| [Contacts](./contacts) | Пространство имен контактов протокола ActiveSync |
| [Contacts2](./contacts2) | Пространство имен Contacts2 протокола ActiveSync |
| [DocumentLibrary](./documentlibrary) | Пространство имен DocumentLibrary протокола ActiveSync |
| [Email](./email) | Пространство имен электронной почты протокола ActiveSync |
| [Email2](./email2) | Пространство имен Email2 протокола ActiveSync |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | Указывает алгоритм, используемый при шифровании сообщений S/MIME. |
| [FolderClass](./folderclass) | Указывает класс содержимого папки для мониторинга. |
| [FolderHierarchy](./folderhierarchy) | Пространство имен FolderHierarchy протокола ActiveSync |
| [FolderTypes](./foldertypes) | Указывает тип папки, которая была обновлена (переименована или перемещена) или добавлена на сервер. |
| [GAL](./gal) | Пространство имен GAL протокола ActiveSync |
| [GetItemEstimate](./getitemestimate) | Пространство имен GetItemEstimate протокола ActiveSync |
| [ItemOperations](./itemoperations) | Пространство имен ItemOperations протокола ActiveSync |
| [MaxAgeFilter](./maxagefilter) | Задает максимальное количество календарных дней, которые можно синхронизировать. |
| [MeetingResponse](./meetingresponse) | Пространство имен MeetingResponse протокола ActiveSync |
| [MergedFreeBusy](./mergedfreebusy) | Указывает информацию о занятости для пользователей или списка рассылки. |
| [MIMESupport](./mimesupport) | Включает поддержку MIME для элементов электронной почты, отправляемых с сервера клиенту. |
| [MIMETruncation](./mimetruncation) | Указывает, ДОЛЖНЫ ли быть усечены MIME-данные элемента электронной почты при его отправке с сервера клиенту. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | Задает требуемый уровень сложности пароля клиента. Например: Если значение MinDevicePasswordComplexCharacters равно 2, будет достаточно пароля, состоящего как из букв верхнего, так и из нижнего регистра, как и пароль с буквами нижнего регистра и цифрами. |
| [Move](./move) | Переместить пространство имен протокола ActiveSync |
| [Namespace](./namespace) | Кодовые страницы ActiveSync |
| [Notes](./notes) | Notes пространство имен протокола ActiveSync |
| [OofState](./oofstate) | Указывает доступность свойства Oof. |
| [Ping](./ping) | Ping пространство имен протокола ActiveSync |
| [Provision](./provision) | Provision namespace протокола ActiveSync |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | Значение указывает на успешное или неудачное применение клиентом параметров политики, полученных с сервера. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | Значение указывает на успех или неудачу операции удаленной очистки на клиенте. |
| [RecipientType](./recipienttype) | Указывает тип получателя. |
| [ResolveRecipients](./resolverecipients) | Пространство имен ResolveRecipients протокола ActiveSync |
| [RightsManagement](./rightsmanagement) | Пространство имен RightsManagement протокола ActiveSync |
| [Search](./search) | Поиск пространства имен протокола ActiveSync |
| [ServerType](./servertype) | Указывает тип сервера |
| [Settings](./settings) | Пространство имен настроек протокола ActiveSync |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | Указывает алгоритм, используемый при подписании сообщений S/MIME. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Управляет согласованием алгоритма шифрования. |
| [StoreType](./storetype) | Содержит информацию, определяющую местоположение операций. |
| [Tasks](./tasks) | Пространство имен задач протокола ActiveSync |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Указывает тип создаваемой папки. |
| [UserResponse](./userresponse) | Указывает, принимается ли собрание, предварительно принимается или отклоняется. |
| [ValidateCert](./validatecert) | Пространство имен ValidateCert протокола ActiveSync |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->