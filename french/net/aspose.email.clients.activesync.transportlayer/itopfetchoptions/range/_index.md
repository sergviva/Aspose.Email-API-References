---
title: Range
second_title: Référence de l'API Aspose.Email pour .NET
description: Spécifie la plage doctets que le client peut recevoir en réponse à lopération Fetch pour un élément de bibliothèque de documents. Lélément Range est un champ facultatif. Lélément Range contient une valeur de chaîne au format MN où M est inférieur à N et M est la valeur minimale et N est la valeur maximale. La plage doctets est indexée à zéro  le premier octet est indiqué par un 0 zéro. Si Range est omis dans la requête Fetch lélément entier est récupéré. Si FileReference est présent dans la requête alors lélément Range est le seul élément enfant valide de lélément Options.
type: docs
weight: 60
url: /fr/net/aspose.email.clients.activesync.transportlayer/itopfetchoptions/range/
---
## ItOpFetchOptions.Range property

Spécifie la plage d'octets que le client peut recevoir en réponse à l'opération Fetch pour un élément de bibliothèque de documents. L'élément Range est un champ facultatif. L'élément Range contient une valeur de chaîne au format MN, où M est inférieur à N, et M est la valeur minimale et N est la valeur maximale. La plage d'octets est indexée à zéro ; le premier octet est indiqué par un 0 (zéro). Si Range est omis dans la requête Fetch, l'élément entier est récupéré. Si FileReference est présent dans la requête, alors l'élément Range est le seul élément enfant valide de l'élément Options.

```csharp
public string Range { get; set; }
```

### Voir également

* class [ItOpFetchOptions](../../itopfetchoptions)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../itopfetchoptions)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->