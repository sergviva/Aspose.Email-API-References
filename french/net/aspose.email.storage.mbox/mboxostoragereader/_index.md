---
title: MboxoStorageReader
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente le lecteur de stockage au format mboxo ce format est utilisé par Eudora.
type: docs
weight: 20050
url: /fr/net/aspose.email.storage.mbox/mboxostoragereader/
---
## MboxoStorageReader class

Représente le lecteur de stockage au format mboxo, ce format est utilisé par Eudora.

```csharp
public sealed class MboxoStorageReader : MboxStorageReader
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MboxoStorageReader](mboxostoragereader#constructor)(Stream, MboxLoadOptions) | Initialise une nouvelle instance du[`MboxoStorageReader`](../mboxostoragereader) classer. |
| [MboxoStorageReader](mboxostoragereader#constructor_2)(string, MboxLoadOptions) | Initialise une nouvelle instance du[`MboxrdStorageReader`](../mboxrdstoragereader) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BaseStream](../../aspose.email.storage.mbox/mboxstoragereader/basestream) { get; } | Obtient le flux de base. |
| [CurrentDataSize](../../aspose.email.storage.mbox/mboxstoragereader/currentdatasize) { get; } | Obtient le nombre d'octets lus par la méthode ReadNextMessage. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.email.storage.mbox/mboxstoragereader/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages)() | Expose l'énumérateur, qui prend en charge une itération de messages dans le stockage. |
| override [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxostoragereader/gettotalitemscount)() | Renvoie le nombre de messages dans un stockage. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage#readnextmessage)() | Lit le message suivant à partir du flux de stockage sous-jacent. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage#readnextmessage_1)(out string) | Lit le message suivant à partir du flux de stockage sous-jacent. |

### Voir également

* class [MboxStorageReader](../mboxstoragereader)
* espace de noms [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->