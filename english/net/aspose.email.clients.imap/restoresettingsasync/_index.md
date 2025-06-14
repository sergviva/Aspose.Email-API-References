---
title: Class RestoreSettingsAsync
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.RestoreSettingsAsync class. The settings for the ImapClient.Restore async method
type: docs
weight: 16840
url: /net/aspose.email.clients.imap/restoresettingsasync/
---
## RestoreSettingsAsync class

The settings for the ImapClient.Restore async method.

```csharp
public class RestoreSettingsAsync : RestoreSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [RestoreSettingsAsync](restoresettingsasync/)() | Initializes a new instance of the RestoreSettingsAsync class. |

## Properties

| Name | Description |
| --- | --- |
| [BeforeItemCallback](../../aspose.email.clients.imap/restoresettings/beforeitemcallback/) { get; set; } | The callback called when the next item (message or folder) is processed. |
| [Callback](../../aspose.email.clients.imap/restoresettingsasync/callback/) { get; set; } | References a method to be called when a corresponding asynchronous operation completes. |
| [Connection](../../aspose.email.clients.imap/restoresettings/connection/) { get; set; } | Connection to a server. |
| [Folders](../../aspose.email.clients.imap/restoresettings/folders/) { get; set; } | A folders to be restored. |
| [NumberOfAttemptsToRrepeat](../../aspose.email.clients.imap/restoresettings/numberofattemptstorrepeat/) { get; set; } | Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again. |
| [Options](../../aspose.email.clients.imap/restoresettings/options/) { get; set; } | Restore options. |
| [Recursive](../../aspose.email.clients.imap/restoresettings/recursive/) { get; set; } | Indicates that nested folders should be also restored |
| [RemoveNonexistentFolders](../../aspose.email.clients.imap/restoresettings/removenonexistentfolders/) { get; set; } | Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed |
| [RemoveNonexistentItems](../../aspose.email.clients.imap/restoresettings/removenonexistentitems/) { get; set; } | Indicates that mail items, which do not have the equal items in the personal storage, should be removed |
| [RestoreConnection](../../aspose.email.clients.imap/restoresettings/restoreconnection/) { get; set; } | Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [State](../../aspose.email.clients.imap/restoresettingsasync/state/) { get; set; } | The state. |
| [TimeoutBetweenAttempts](../../aspose.email.clients.imap/restoresettings/timeoutbetweenattempts/) { get; set; } | Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |

### See Also

* class [RestoreSettings](../restoresettings/)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


