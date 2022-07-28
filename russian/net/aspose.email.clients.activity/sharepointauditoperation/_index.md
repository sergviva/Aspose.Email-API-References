---
title: SharePointAuditOperation
second_title: Справочник по Aspose.Email для .NET API
description: Операции аудита SharePoint
type: docs
weight: 2760
url: /ru/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

Операции аудита SharePoint

```csharp
public enum SharePointAuditOperation
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | Эта операция находится в режиме предварительного просмотра. Получатель приглашения на просмотр или редактирование общего файла (или папки) получил доступ к общему файлу, щелкнув ссылку в приглашении. |
| AccessInvitationCreated | `1` | Эта операция находится в режиме предварительного просмотра. Пользователь отправляет приглашение другому лицу (внутри или за пределами своей организации) для просмотра или редактирования общего файла или папки на сайте SharePoint или OneDrive для бизнеса. Сведения о записи события определяют имя файла, к которому был предоставлен общий доступ, пользователя, которому было отправлено приглашение, и тип разрешения на общий доступ, выбранный лицом, которое отправил приглашение. |
| AccessInvitationExpired | `2` | Эта операция находится в режиме предварительного просмотра. Приглашение, отправленное внешнему пользователю, истекает. По умолчанию срок действия приглашения, отправленного пользователю за пределами вашей организации, истекает через 7 дней, если приглашение не принято. |
| AccessInvitationRevoked | `3` | Эта операция находится в режиме предварительного просмотра. Администратор сайта или владелец сайта или документа в SharePoint или OneDrive для бизнеса отзывает приглашение, отправленное пользователю за пределами вашей организации. Приглашение можно отозвать только до того, как оно будет принято. |
| AccessInvitationUpdated | `4` | Эта операция находится в режиме предварительного просмотра. Пользователь, создавший и отправивший приглашение другому лицу для просмотра или редактирования общего файла (или папки) на сайте SharePoint или OneDrive для бизнеса, повторно отправляет приглашение. |
| AccessRequestApproved | `5` | Администратор сайта или владелец сайта или документа в SharePoint или OneDrive для бизнеса утверждает запрос пользователя на доступ к сайту или документу. |
| AccessRequestCreated | `6` | Пользователь запрашивает доступ к сайту или документу в SharePoint или OneDrive для бизнеса, на доступ к которым у него нет разрешения. |
| AccessRequestRejected | `7` | Эта операция находится в режиме предварительного просмотра. Администратор сайта или владелец сайта или документа в SharePoint отклоняет запрос пользователя на доступ к сайту или документу. |
| ActivationEnabled | `8` | Эта операция находится в режиме предварительного просмотра. Пользователи могут включать в браузере шаблоны форм, которые не содержат кода формы, требуют полного доверия, включают отображение на мобильном устройстве или используют подключение для передачи данных, управляемое администратором сервера. |
| AdministratorAddedToTermStore | `9` | Эта операция находится в режиме предварительного просмотра. Добавлен администратор хранилища терминов. |
| AdministratorDeletedFromTermStore | `10` | Эта операция находится в режиме предварительного просмотра. Администратор хранилища терминов удален. |
| AllowGroupCreationSet | `11` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта добавляет уровень разрешений на сайт SharePoint или OneDrive для бизнеса, который позволяет пользователю, которому назначено это разрешение, создавать группу для этого сайта. |
| AppCatalogCreated | `12` | Эта операция находится в режиме предварительного просмотра. Каталог приложений, созданный для того, чтобы сделать пользовательские бизнес-приложения доступными для вашей среды SharePoint. |
| AuditPolicyRemoved | `13` | Эта операция находится в режиме предварительного просмотра. Политика жизненного цикла документов удалена для семейства веб-сайтов. |
| AuditPolicyUpdate | `14` | Эта операция находится в режиме предварительного просмотра. Политика жизненного цикла документов обновлена для семейства веб-сайтов. |
| AzureStreamingEnabledSet | `15` | Эта операция находится в режиме предварительного просмотра. Владелец видеопортала разрешил потоковую передачу видео из Azure. |
| CollaborationTypeModified | `16` | Эта операция находится в режиме предварительного просмотра. Тип совместной работы, разрешенный на сайтах (например, интранет, экстранет или публичный), был изменен. |
| ConnectedSiteSettingModified | `17` | Пользователь либо создал, изменил или удалил ссылку между проектом и сайтом проекта, либо пользователь изменил параметр синхронизации для ссылки в Project Web App. |
| CreateSSOApplication | `18` | Эта операция находится в режиме предварительного просмотра. Целевое приложение, созданное в службе безопасного хранения. |
| CustomFieldOrLookupTableCreated | `19` | Пользователь создал пользовательское поле или таблицу поиска/элемент в Project Web App. |
| CustomFieldOrLookupTableDeleted | `20` | Пользователь удалил настраиваемое поле или таблицу поиска/элемент в Project Web App. |
| CustomFieldOrLookupTableModified | `21` | Пользователь изменил настраиваемое поле или таблицу поиска/элемент в Project Web App. |
| CustomizeExemptUsers | `22` | Эта операция находится в режиме предварительного просмотра. Глобальный администратор настроил список исключенных пользовательских агентов в центре администрирования SharePoint. Вы можете указать, какие пользовательские агенты должны быть освобождены от получения всей веб-страницы для индексации. Это означает, что когда пользовательский агент, указанный вами как освобожденный, встречает форму InfoPath, эта форма будет возвращена в виде XML-файла, а не целой веб-страницы. Это ускоряет индексирование форм InfoPath. |
| DefaultLanguageChangedInTermStore | `23` | Эта операция находится в режиме предварительного просмотра. Изменена настройка языка в хранилище терминов. |
| DelegateModified | `24` | Пользователь создал или изменил делегата безопасности в Project Web App. |
| DelegateRemoved | `25` | Пользователь удалил делегата безопасности в Project Web App. |
| DeleteSSOApplication | `26` | Эта операция находится в режиме предварительного просмотра. Приложение SSO было удалено. |
| eDiscoveryHoldApplied | `27` | Эта операция находится в режиме предварительного просмотра. К источнику контента было применено удержание на месте. Удержание на месте управляется с помощью семейства веб-сайтов обнаружения электронных данных (например, центра обнаружения электронных данных) в SharePoint. |
| eDiscoveryHoldRemoved | `28` | Эта операция находится в режиме предварительного просмотра. Удержание на месте удалено из источника контента. Удержание на месте управляется с помощью семейства веб-сайтов обнаружения электронных данных (например, центра обнаружения электронных данных) в SharePoint. |
| eDiscoverySearchPerformed | `29` | Эта операция находится в режиме предварительного просмотра. Поиск обнаружения электронных данных был выполнен с использованием семейства веб-сайтов обнаружения электронных данных в SharePoint. |
| EngagementAccepted | `30` | Пользователь принимает участие в ресурсах в Project Web App. |
| EngagementModified | `31` | Пользователь изменяет задействование ресурсов в Project Web App. |
| EngagementRejected | `32` | Пользователь отклоняет использование ресурсов в Project Web App. |
| EnterpriseCalendarModified | `33` | Пользователь копирует, изменяет или удаляет корпоративный календарь в Project Web App. |
| EntityDeleted | `34` | Пользователь удаляет расписание в Project Web App. |
| EntityForceCheckedIn | `35` | Пользователь принудительно выполняет возврат в календаре, настраиваемое поле или таблицу поиска в Project Web App. |
| ExemptUserAgentSet | `36` | Эта операция находится в режиме предварительного просмотра. Глобальный администратор добавляет пользовательский агент в список исключенных пользовательских агентов в центре администрирования SharePoint. |
| FileAccessed | `37` | Учетная запись пользователя или системы получает доступ к файлу на сайте SharePoint или OneDrive для бизнеса. Системные учетные записи также могут генерировать события FileAccessed. |
| FileCheckOutDiscarded | `38` | Эта операция находится в режиме предварительного просмотра. Пользователь отбрасывает (или отменяет) извлеченный файл. Это означает, что любые изменения, внесенные в файл при извлечении, отбрасываются и не сохраняются в версии документа в библиотеке документов. |
| FileCheckedIn | `39` | Эта операция находится в режиме предварительного просмотра. Пользователь возвращает документ, извлеченный из библиотеки документов SharePoint или OneDrive для бизнеса. |
| FileCheckedOut | `40` | Эта операция находится в режиме предварительного просмотра. Пользователь извлекает документ, расположенный в библиотеке документов SharePoint или OneDrive для бизнеса. Пользователи могут извлекать и вносить изменения в документы, к которым им предоставлен доступ. |
| FileCopied | `41` | Пользователь копирует документ с сайта SharePoint или OneDrive для бизнеса. Скопированный файл можно сохранить в другую папку на сайте. |
| FileDeleted | `42` | Пользователь удаляет документ с сайта SharePoint или OneDrive для бизнеса. |
| FileDeletedFirstStageRecycleBin | `43` | Пользователь удаляет файл из корзины на сайте SharePoint или OneDrive для бизнеса. |
| FileDeletedSecondStageRecycleBin | `44` | Пользователь удаляет файл из корзины второго уровня на сайте SharePoint или OneDrive для бизнеса. |
| FileDownloaded | `45` | Пользователь загружает документ с сайта SharePoint или OneDrive для бизнеса. |
| FileFetched | `46` | Это событие было заменено событием FileAccessed и объявлено устаревшим. |
| FileModified | `47` | Учетная запись пользователя или системы изменяет содержимое или свойства документа, расположенного на сайте SharePoint или OneDrive для бизнеса. |
| FileMoved | `48` | Пользователь перемещает документ из его текущего местоположения на сайте SharePoint или OneDrive для бизнеса в новое место. |
| FilePreviewed | `49` | Пользователь просматривает документ на сайте SharePoint или OneDrive для бизнеса. |
| FileRenamed | `50` | Пользователь переименовывает документ на сайте SharePoint или OneDrive для бизнеса. |
| FileRestored | `51` | Пользователь восстанавливает документ из корзины сайта SharePoint или OneDrive для бизнеса. |
| FileSyncDownloadedFull | `52` | Пользователь устанавливает отношение синхронизации и успешно загружает файлы на свой компьютер в первый раз из библиотеки документов SharePoint или OneDrive для бизнеса. |
| FileSyncDownloadedPartial | `53` | Пользователь успешно загружает любые изменения в файлы из библиотеки документов SharePoint или OneDrive для бизнеса. Это событие указывает на то, что любые изменения, внесенные в файлы в библиотеке документов, были загружены на компьютер пользователя. Были загружены только изменения, так как библиотека документов была ранее загружена пользователем (на что указывает событие FileSyncDownloadedFull). |
| FileSyncUploadedFull | `54` | Эта операция находится в режиме предварительного просмотра. Пользователь устанавливает отношение синхронизации и успешно загружает файлы со своего компьютера в библиотеку документов SharePoint или OneDrive для бизнеса в первый раз. |
| FileSyncUploadedPartial | `55` | Эта операция находится в режиме предварительного просмотра. Пользователь успешно отправляет изменения в файлы в библиотеке документов SharePoint или OneDrive для бизнеса. Это событие означает, что любые изменения, внесенные в локальную версию файла из библиотеки документов, успешно загружены в библиотеку документов. Выгружаются только изменения, поскольку эти файлы были ранее загружены пользователем (как указано в событии FileSyncUploadedFull). |
| FileUploaded | `56` | Пользователь загружает документ в папку на сайте SharePoint или OneDrive для бизнеса. |
| FileViewed | `57` | Это событие было заменено событием FileAccessed и объявлено устаревшим. |
| FolderCopied | `58` | Пользователь копирует папку с сайта SharePoint или OneDrive для бизнеса в другое место в SharePoint или OneDrive для бизнеса. |
| FolderCreated | `59` | Пользователь создает папку на сайте SharePoint или OneDrive для бизнеса. |
| FolderDeleted | `60` | Пользователь удаляет папку с сайта SharePoint или OneDrive для бизнеса. |
| FolderDeletedFirstStageRecycleBin | `61` | Пользователь удаляет папку из корзины на сайте SharePoint или OneDrive для бизнеса. |
| FolderDeletedSecondStageRecycleBin | `62` | Пользователь удаляет папку из корзины второго уровня на сайте SharePoint или OneDrive для бизнеса. |
| FolderModified | `63` | Пользователь изменяет папку на сайте SharePoint или OneDrive для бизнеса. Это событие включает изменения метаданных папки, таких как теги и свойства. |
| FolderMoved | `64` | Пользователь перемещает папку с сайта SharePoint или OneDrive для бизнеса. |
| FolderRenamed | `65` | Пользователь переименовывает папку на сайте SharePoint или OneDrive для бизнеса. |
| FolderRestored | `66` | Пользователь восстанавливает папку из корзины на сайте SharePoint или OneDrive для бизнеса. |
| GroupAdded | `67` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта создает группу для сайта SharePoint или OneDrive для бизнеса или выполняет задачу, в результате которой создается группа. Например, когда пользователь впервые создает ссылку для совместного использования файла, на его сайт OneDrive для бизнеса добавляется системная группа. Это событие также может быть результатом создания пользователем ссылки с разрешениями на редактирование общего файла. |
| GroupRemoved | `68` | Эта операция находится в режиме предварительного просмотра. Пользователь удаляет группу с сайта SharePoint или OneDrive для бизнеса. |
| GroupUpdated | `69` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта изменяет параметры группы для сайта SharePoint или OneDrive для бизнеса. Сюда может входить изменение имени группы, кто может просматривать или редактировать членство в группе и как обрабатываются запросы на членство. |
| LanguageAddedToTermStore | `70` | Эта операция находится в режиме предварительного просмотра. Язык добавлен в хранилище терминов. |
| LanguageRemovedFromTermStore | `71` | Эта операция находится в режиме предварительного просмотра. Язык удален из хранилища терминологии. |
| LegacyWorkflowEnabledSet | `72` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта добавляет на сайт тип контента Задача рабочего процесса SharePoint. Глобальные администраторы также могут включить рабочие процессы для всей организации в центре администрирования SharePoint. |
| LookAndFeelModified | `73` | Пользователь изменяет форматы быстрого запуска, диаграммы Ганта или групповые форматы. Или пользователь создает, изменяет или удаляет представление в Project Web App. |
| ManagedSyncClientAllowed | `74` | Пользователь успешно устанавливает связь синхронизации с сайтом SharePoint или OneDrive для бизнеса. Связь синхронизации выполнена успешно, поскольку компьютер пользователя является членом домена , который был добавлен в список доменов (называемый списком безопасных получателей), которые могут получать доступ к библиотекам документов в ваша организация. Дополнительные сведения об этой функции см. в статье Использование командлетов Windows PowerShell для включения синхронизации OneDrive для доменов, которые находятся в списке надежных получателей. |
| MaxQuotaModified | `75` | Эта операция находится в режиме предварительного просмотра. Изменена максимальная квота для сайта. |
| MaxResourceUsageModified | `76` | Эта операция находится в режиме предварительного просмотра. Максимально допустимое использование ресурсов для сайта было изменено. |
| MySitePublicEnabledSet | `77` | Эта операция находится в режиме предварительного просмотра. Флаг, позволяющий пользователям иметь общедоступные личные сайты, был установлен администратором SharePoint. |
| NewsFeedEnabledSet | `78` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта включает RSS-каналы для сайта SharePoint или OneDrive для бизнеса. Глобальные администраторы могут включить RSS-каналы для всей организации в центре администрирования SharePoint. |
| ODBNextUXSettings | `79` | Эта операция находится в режиме предварительного просмотра. Включен новый пользовательский интерфейс для OneDrive для бизнеса. |
| OfficeOnDemandSet | `80` | Эта операция находится в режиме предварительного просмотра. Администратор сайта включает Office on Demand, что позволяет пользователям получать доступ к последним версиям настольных приложений Office. Office on Demand включается в центре администрирования SharePoint и требует подписки на Office 365, которая включает полные установленные приложения Office. |
| PageViewed | `81` | Пользователь просматривает страницу на сайте SharePoint или сайте OneDrive для бизнеса. Сюда не входит просмотр файлов библиотеки документов с сайта SharePoint или сайта One Drive for Business в браузере. |
| PeopleResultsScopeSet | `82` | Эта операция находится в режиме предварительного просмотра. Администратор сайта создает или изменяет источник результатов поиска людей для сайта SharePoint. |
| PermissionSyncSettingModified | `83` | Пользователь изменяет параметры синхронизации разрешений проекта в Project Web App. |
| PermissionTemplateModified | `84` | Пользователь создает, изменяет или удаляет шаблон разрешений в Project Web App. |
| PortfolioDataAccessed | `85` | Пользователь получает доступ к содержимому портфолио (библиотека драйверов, приоритезация драйверов, анализ портфолио) в Project Web App. |
| PortfolioDataModified | `86` | Пользователь создает, изменяет или удаляет данные портфеля (библиотеку драйверов, приоритезацию драйверов, анализ портфеля) в Project Web App. |
| PreviewModeEnabledSet | `87` | Эта операция находится в режиме предварительного просмотра. Администратор сайта включает предварительный просмотр документов для сайта SharePoint. |
| ProjectAccessed | `88` | Пользователь получает доступ к содержимому проекта в Project Web App. |
| ProjectCheckedIn | `89` | Пользователь возвращает проект, извлеченный из Project Web App. |
| ProjectCheckedOut | `90` | Пользователь извлекает проект, расположенный в Project Web App. Пользователи могут извлекать и вносить изменения в проекты, на открытие которых у них есть разрешение. |
| ProjectCreated | `91` | Пользователь создает проект в Project Web App. |
| ProjectDeleted | `92` | Пользователь удаляет проект в Project Web App. |
| ProjectForceCheckedIn | `93` | Пользователь принудительно возвращает проект в Project Web App. |
| ProjectModified | `94` | Пользователь изменяет проект в Project Web App. |
| ProjectPublished | `95` | Пользователь публикует проект в Project Web App. |
| ProjectWorkflowRestarted | `96` | Пользователь перезапускает рабочий процесс в Project Web App. |
| PWASettingsAccessed | `97` | Пользователь получает доступ к параметрам Project Web App через CSOM. |
| PWASettingsModified | `98` | Пользователь изменяет конфигурацию Project Web App. |
| QueueJobStateModified | `99` | Пользователь отменяет или перезапускает задание очереди в Project Web App. |
| QuotaWarningEnabledModified | `100` | Эта операция находится в режиме предварительного просмотра. Предупреждение о квоте хранилища изменено. |
| RenderingEnabled | `101` | Эта операция находится в режиме предварительного просмотра. Шаблоны форм с поддержкой браузера будут отображаться службами форм InfoPath. |
| ReportingAccessed | `102` | Пользователь получил доступ к конечной точке отчетов в Project Web App. |
| ReportingSettingModified | `103` | Пользователь изменяет конфигурацию отчетов в Project Web App. |
| ResourceAccessed | `104` | Пользователь обращается к содержимому корпоративного ресурса в Project Web App. |
| ResourceCheckedIn | `105` | Пользователь возвращает корпоративный ресурс, извлеченный из Project Web App. |
| ResourceCheckedOut | `106` | Пользователь извлекает корпоративный ресурс, расположенный в Project Web App. |
| ResourceCreated | `107` | Пользователь создает корпоративный ресурс в Project Web App. |
| ResourceDeleted | `108` | Пользователь удаляет корпоративный ресурс в Project Web App. |
| ResourceForceCheckedIn | `109` | Пользователь принудительно возвращает корпоративный ресурс в Project Web App. |
| ResourceModified | `110` | Пользователь изменяет корпоративный ресурс в Project Web App. |
| ResourcePlanCheckedInOrOut | `111` | Пользователь возвращает или возвращает план ресурсов в Project Web App. |
| ResourcePlanModified | `112` | Пользователь изменяет план ресурсов в Project Web App. |
| ResourcePlanPublished | `113` | Пользователь публикует план ресурсов в Project Web App. |
| ResourceRedacted | `114` | Пользователь редактирует корпоративный ресурс, удаляя всю личную информацию в Project Web App. |
| ResourceWarningEnabledModified | `115` | Эта операция находится в режиме предварительного просмотра. Изменено предупреждение о квоте ресурсов. |
| SSOGroupCredentialsSet | `116` | Эта операция находится в режиме предварительного просмотра. Групповые учетные данные, установленные в службе безопасного хранения. |
| SSOUserCredentialsSet | `117` | Эта операция находится в режиме предварительного просмотра. Учетные данные пользователя, установленные в службе безопасного хранения. |
| SearchCenterUrlSet | `118` | Эта операция находится в режиме предварительного просмотра. URL-адрес центра поиска задан. |
| SecondaryMySiteOwnerSet | `119` | Эта операция находится в режиме предварительного просмотра. Пользователь добавил второго владельца на свой личный сайт. |
| SecurityCategoryModified | `120` | Пользователь создает, изменяет или удаляет категорию безопасности в Project Web App. |
| SecurityGroupModified | `121` | Пользователь создает, изменяет или удаляет группу безопасности в Project Web App. |
| SendToConnectionAdded | `122` | Эта операция находится в режиме предварительного просмотра. Глобальный администратор создает новое подключение для отправки на странице управления записями в центре администрирования SharePoint. Соединение "Отправить" задает параметры для репозитория документов или центра записей. Когда вы создаете соединение для отправки, организатор содержимого может отправлять документы в указанное место. |
| SendToConnectionRemoved | `123` | Эта операция находится в режиме предварительного просмотра. Глобальный администратор удаляет соединение "Отправить" на странице управления записями в центре администрирования SharePoint. |
| SharedLinkCreated | `124` | Пользователь создает ссылку на общий файл в SharePoint или OneDrive для бизнеса. Эту ссылку можно отправить другим людям, чтобы предоставить им доступ к файлу. Пользователь может создавать два типа ссылок:ссылку, которая позволяет пользователю просматривать и редактировать общий файл, или ссылку, которая позволяет пользователю просто просматривать файл. |
| SharedLinkDisabled | `125` | Эта операция находится в режиме предварительного просмотра. Пользователь отключает (навсегда) ссылку, созданную для обмена файлом. |
| SharingInvitationAccepted | `126` | Эта операция находится в режиме предварительного просмотра. Пользователь принимает приглашение поделиться файлом или папкой. Это событие регистрируется, когда пользователь делится файлом с другими пользователями. |
| SharingRevoked | `127` | Эта операция находится в режиме предварительного просмотра. Пользователь отменяет общий доступ к файлу или папке, которые ранее были доступны другим пользователям. Это событие регистрируется, когда пользователь перестает делиться файлом с другими пользователями. |
| SharingSet | `128` | Пользователь предоставляет доступ к файлу или папке, расположенным в SharePoint или OneDrive для бизнеса, другому пользователю в своей организации. |
| SiteAdminChangeRequest | `129` | Эта операция находится в режиме предварительного просмотра. Пользователь запрашивает добавление в качестве администратора семейства веб-сайтов для семейства веб-сайтов SharePoint. Администраторы семейства веб-сайтов имеют разрешения на полный доступ к семейству веб-сайтов и всем дочерним сайтам. |
| SiteCollectionAdminAdded | `130` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец семейства веб-сайтов добавляет человека в качестве администратора семейства веб-сайтов для сайта SharePoint или OneDrive для бизнеса. Администраторы семейства веб-сайтов имеют разрешения на полный доступ к семейству веб-сайтов и всем дочерним сайтам. |
| SiteCollectionCreated | `131` | Эта операция находится в режиме предварительного просмотра. Глобальный администратор создает новое семейство сайтов в вашей организации SharePoint. |
| SiteRenamed | `132` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта переименовывает сайт SharePoint или OneDrive для бизнеса |
| StatusReportModified | `133` | Пользователь создает, изменяет или удаляет отчет о состоянии в Project Web App. |
| SyncGetChanges | `134` | Эта операция находится в режиме предварительного просмотра. Пользователь щелкает Синхронизировать на панели действий в SharePoint или OneDrive для бизнеса, чтобы синхронизировать любые изменения файла в библиотеке документов со своим компьютером. |
| TaskStatusAccessed | `135` | Пользователь получает доступ к состоянию одной или нескольких задач в Project Web App. |
| TaskStatusApproved | `136` | Пользователь утверждает обновление состояния одной или нескольких задач в Project Web App. |
| TaskStatusRejected | `137` | Пользователь отклоняет обновление состояния одной или нескольких задач в Project Web App. |
| TaskStatusSaved | `138` | Пользователь сохраняет обновление состояния одной или нескольких задач в Project Web App. |
| TaskStatusSubmitted | `139` | Пользователь отправляет обновление состояния одной или нескольких задач в Project Web App. |
| TimesheetAccessed | `140` | Пользователь получает доступ к расписанию в Project Web App. |
| TimesheetApproved | `141` | Пользователь утверждает расписание в Project Web App. |
| TimesheetRejected | `142` | Пользователь отклоняет расписание в Project Web App. |
| TimesheetSaved | `143` | Пользователь сохраняет расписание в Project Web App. |
| TimesheetSubmitted | `144` | Пользователь отправляет расписание состояния в Project Web App. |
| UnmanagedSyncClientBlocked | `145` | Пользователь пытается установить связь синхронизации с сайтом SharePoint или OneDrive для бизнеса с компьютера, который не является членом домена вашей организации или является членом домена , который не был добавлен в список доменов (называемый списком безопасных получателей), которые могут получить доступ к библиотекам документов в вашей организации. Отношения синхронизации не разрешены, и компьютер пользователя заблокирован от синхронизации, загрузки или отправки файлов в библиотеке документов. Сведения об этой функции см. в статье Использование командлетов Windows PowerShell для включения синхронизации OneDrive для доменов, которые находятся в списке надежных получателей. |
| UpdateSSOApplication | `146` | Эта операция находится в режиме предварительного просмотра. Целевое приложение обновлено в службе безопасного хранения. |
| UserAddedToGroup | `147` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта добавляет человека в группу на сайте SharePoint или OneDrive для бизнеса. Добавление человека в группу предоставляет пользователю права, которые были назначены группе. |
| UserRemovedFromGroup | `148` | Эта операция находится в режиме предварительного просмотра. Администратор или владелец сайта удаляет пользователя из группы на сайте SharePoint или OneDrive для бизнеса. После удаления человека ему больше не предоставляются разрешения, которые были назначены группе. |
| WorkflowModified | `149` | Пользователь создает, изменяет или удаляет тип корпоративного проекта или этапы или этапы рабочего процесса в Project Web App. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->