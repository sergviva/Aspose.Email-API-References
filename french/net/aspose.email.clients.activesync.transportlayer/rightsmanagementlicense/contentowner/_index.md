---
title: ContentOwner
second_title: Référence de l'API Aspose.Email pour .NET
description: Spécifie si le contenu de le-mail dorigine peut être modifié par lutilisateur lorsque lutilisateur transfère répond ou répond à tous le-mail. La valeur est TRUE si le-mail peut être modifié par lutilisateur  sinon FALSE. Une valeur de FALSE exige que le client DOIT exclure le message électronique dorigine géré par des droits de la demande SmartForward ou SmartReply. Par conséquent les réponses en ligne ne sont pas autorisées si lélément EditAllowed est défini sur FALSE. Lorsque EditAllowed est défini sur FALSE et que ReplaceMime nest pas présent dans une demande SmartForward ou SmartReply le serveur ajoute le message électronique original géré par des droits en tant que pièce jointe au nouveau message. Inversement si ReplaceMime est présent le serveur ne joindra pas le-mail dorigine en tant que pièce jointe.
type: docs
weight: 30
url: /fr/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner/
---
## RightsManagementLicense.ContentOwner property

Spécifie si le contenu de l'e-mail d'origine peut être modifié par l'utilisateur lorsque l'utilisateur transfère, répond ou répond à tous l'e-mail. La valeur est TRUE si l'e-mail peut être modifié par l'utilisateur ; sinon, FALSE. Une valeur de FALSE exige que le client DOIT exclure le message électronique d'origine géré par des droits de la demande SmartForward ou SmartReply. Par conséquent, les réponses en ligne ne sont pas autorisées si l'élément EditAllowed est défini sur FALSE. Lorsque EditAllowed est défini sur FALSE et que ReplaceMime n'est pas présent dans une demande SmartForward ou SmartReply, le serveur ajoute le message électronique original géré par des droits en tant que pièce jointe au nouveau message. Inversement, si ReplaceMime est présent, le serveur ne joindra pas l'e-mail d'origine en tant que pièce jointe.

```csharp
public bool ContentOwner { get; set; }
```

### Voir également

* class [RightsManagementLicense](../../rightsmanagementlicense)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../rightsmanagementlicense)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->