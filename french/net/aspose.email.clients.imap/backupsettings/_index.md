---
title: BackupSettings
second_title: Référence de l'API Aspose.Email pour .NET
description: La classe contient des options pour lopération de sauvegarde
type: docs
weight: 16200
url: /fr/net/aspose.email.clients.imap/backupsettings/
---
## BackupSettings class

La classe contient des options pour l'opération de sauvegarde

```csharp
public class BackupSettings
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BackupSettings](backupsettings#constructor)() | Initialise une nouvelle instance du[`BackupSettings`](../backupsettings) classe |
| [BackupSettings](backupsettings#constructor_1)(BackupOptions) | Initialise une nouvelle instance du[`BackupSettings`](../backupsettings) classe |
| [BackupSettings](backupsettings#constructor_2)(bool, bool, int, int) | Initialise une nouvelle instance du[`BackupSettings`](../backupsettings) classe |

## Propriétés

| Nom | La description |
| --- | --- |
| static [Default](../../aspose.email.clients.imap/backupsettings/default) { get; } | Obtient[`BackupSettings`](../backupsettings) classe avec les paramètres par défaut |
| [ExecuteRecursively](../../aspose.email.clients.imap/backupsettings/executerecursively) { get; set; } | Obtient ou définit la valeur qui définit si la sauvegarde doit être exécutée de manière récursive |
| [NumberOfAttemptsToRrepeat](../../aspose.email.clients.imap/backupsettings/numberofattemptstorrepeat) { get; set; } | Obtient ou définit la valeur qui définit le nombre de tentatives de répétition de l'opération ayant échoué Si une commande IMAP dans l'opération de sauvegarde renvoie un résultat d'échec, le client IMAP essaie de répéter cette opération à nouveau en fonction du nombre de fois défini. Par exemple, si l'opération FETCH renvoie une erreur AE_1_1_0243 FETCH 219 (BODY) AE_1_1_0243 NO[UNAVAILABLE] Le service FETCH n'est temporairement pas disponible Le client essaie de l'exécuter à nouveau. |
| [RestoreConnection](../../aspose.email.clients.imap/backupsettings/restoreconnection) { get; set; } | Obtient ou définit la valeur qui définit si la connexion doit être restaurée au cas où le serveur ferme la connexion de force Cette option doit être utilisée avec l'option NumberOfAttemptsToRrepeat. |
| [TimeoutBetweenAttempts](../../aspose.email.clients.imap/backupsettings/timeoutbetweenattempts) { get; set; } | Obtient ou définit la valeur qui définit le délai d'attente (en millisecondes) entre les tentatives d'exécution de l'opération à nouveau Cette option doit être utilisée avec l'option NumberOfAttemptsToRrepeat. |

## Méthodes

| Nom | La description |
| --- | --- |
| [implicit operator](../../aspose.email.clients.imap/backupsettings/op_implicit) | Convertit les options énumérables en class |

### Voir également

* espace de noms [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->