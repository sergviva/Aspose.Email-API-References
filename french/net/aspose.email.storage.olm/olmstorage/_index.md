---
title: OlmStorage
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente le fichier de stockage Outlook pour Mac .OLM.
type: docs
weight: 20120
url: /fr/net/aspose.email.storage.olm/olmstorage/
---
## OlmStorage class

Représente le fichier de stockage Outlook pour Mac (.OLM).

```csharp
public class OlmStorage : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [OlmStorage](olmstorage#constructor_1)(Stream) | Initialise une nouvelle instance du[`OlmStorage`](../olmstorage) classe. |
| [OlmStorage](olmstorage#constructor_2)(string) | Initialise une nouvelle instance du[`OlmStorage`](../olmstorage) classe. |
| [OlmStorage](olmstorage#constructor)(TraversalExceptionsCallback) | Initialise une nouvelle instance du[`OlmStorage`](../olmstorage)class. Permet de définir une méthode de rappel pour gérer les exceptions qui se produisent lors de la traversée du stockage OLM. |

## Propriétés

| Nom | La description |
| --- | --- |
| [FolderHierarchy](../../aspose.email.storage.olm/olmstorage/folderhierarchy) { get; } | Obtient la hiérarchie des dossiers. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromFile](../../aspose.email.storage.olm/olmstorage/fromfile)(string) | Charger le stockage OLM à partir du fichier. |
| static [FromStream](../../aspose.email.storage.olm/olmstorage/fromstream)(Stream) | Charger OLM à partir du flux. |
| [Dispose](../../aspose.email.storage.olm/olmstorage/dispose)() | Effectue des tâches définies par l'application associées à la libération, de la libération ou de la réinitialisation des ressources non gérées. |
| [EnumerateMessages](../../aspose.email.storage.olm/olmstorage/enumeratemessages)(OlmFolder) | Expose l'énumérateur, qui prend en charge une itération de messages dans le dossier. |
| [ExtractMapiMessage](../../aspose.email.storage.olm/olmstorage/extractmapimessage)(OlmMessageInfo) | Obtenir le message du stockage OLM. |
| [GetFolder](../../aspose.email.storage.olm/olmstorage/getfolder)(string, bool) | Obtient le dossier par son nom. |
| [GetFolders](../../aspose.email.storage.olm/olmstorage/getfolders)() | Obtient une collection de dossiers. |
| [Load](../../aspose.email.storage.olm/olmstorage/load#load)(Stream) | Charger le stockage OLM à partir du flux. Cette méthode est utilisée lorsqu'un objet OlmStorage est créé à l'aide du constructeur avec le paramètre TraversalExceptionsCallback. |
| [Load](../../aspose.email.storage.olm/olmstorage/load#load_1)(string) | Charger le stockage OLM à partir du fichier. Cette méthode est utilisée lorsqu'un objet OlmStorage est créé à l'aide du constructeur avec le paramètre TraversalExceptionsCallback. |

### Voir également

* espace de noms [Aspose.Email.Storage.Olm](../../aspose.email.storage.olm)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->