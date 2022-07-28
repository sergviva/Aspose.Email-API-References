---
title: HeaderType
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente les normes Internet et les RFC définissent les champs den-tête qui peuvent apparaître sur les messages de messagerie Internet .
type: docs
weight: 17510
url: /fr/net/aspose.email/headertype/
---
## HeaderType class

Représente les normes Internet et les RFC définissent les champs d'en-tête qui peuvent apparaître sur les messages de messagerie Internet .

```csharp
public sealed class HeaderType
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [ApparentlyTo](../../aspose.email/headertype/apparentlyto) { get; } | Inséré en envoyant un e-mail lorsqu'il n'y a pas de destinataire "À :" dans le message d'origine. Ainsi, les destinataires dérivés de l'enveloppe sont répertoriés dans l'en-tête du message. Ce comportement n'est pas tout à fait approprié, les MTA ne doivent pas modifier les en-têtes (à l'exception de l'insertion de lignes Received), et cela peut dans certains cas entraîner la divulgation erronée des destinataires Cci à des destinataires non Cci. Exemple : Apparemment-To : quelqu'un@undomaine.com En-tête non standard dont l'utilisation est déconseillée, mentionnée dans la RFC1211. |
| static [ApprovedBy](../../aspose.email/headertype/approvedby) { get; } | Nom du modérateur de la liste de diffusion à qui ce message est envoyé ; nécessaire sur une annonce envoyée à une liste de diffusion modérée pour permettre sa diffusion aux membres de la liste. Exemple : Approved-By : quelqu'un@undomaine.com Non standard pour une utilisation dans les e-mails. Défini dans RFC1036. |
| static [Bcc](../../aspose.email/headertype/bcc) { get; } | Une copie du message électronique envoyé à un ou plusieurs destinataires à l'insu des destinataires principaux. Les destinataires principaux sont répertoriés dans les lignes À : et Cc :. Ceci est utile si vous souhaitez copier un message à plusieurs personnes sans que chacune d'elles ne voie qui sont les autres destinataires. Si vous voyez cet en-tête sur le courrier entrant, quelque chose ne va pas car il n'apparaît pas dans les en-têtes. |
| static [CC](../../aspose.email/headertype/cc) { get; } | Cet en-tête peut être considéré comme une extension du champ "À :" car il est utilisé pour spécifier des destinataires supplémentaires. Dans ce cas, la copie d'un message électronique envoyé à un destinataire comporte l'adresse du destinataire apparaissant dans le message. Ceci est utile si vous souhaitez copier un message à plusieurs personnes, chacune d'entre elles voyant qui sont les autres destinataires ; contraste avec Cci ci-dessus. Cet en-tête apparaît dans les e-mails entrants. Exemple : Cc : gboyd@netcom.com |
| static [Comments](../../aspose.email/headertype/comments) { get; } | Il s'agit d'un champ d'en-tête de forme libre défini dans RFC2822. L'en-tête est utilisé pour placer un texte explicatif dans la partie d'en-tête d'un message électronique. Le champ peut contenir du texte arbitraire. Exemple : Commentaires : l'expéditeur authentifié est quelqu'un@somedonmain.com. |
| static [ContentTransferEncoding](../../aspose.email/headertype/contenttransferencoding) { get; } | Le troisième des en-têtes liés à MIME. Indique la méthode de codage utilisée dans un corps de message MIME. Il n'a pas de rapport direct avec la livraison du courrier électronique, mais il affecte la manière dont les programmes de messagerie compatibles MIME interprètent le contenu du message. Défini dans RFC2045. Content-Transfer-Encoding : 8bit Content-transfer-encoding : 7BIT Content-Transfer-Encoding : 7bit Content-Transfer-Encoding : base64 Content-Transfer-Encoding : quoted-printable |
| static [ContentType](../../aspose.email/headertype/contenttype) { get; } | Le "Content-Type" définit le format du contenu (jeu de caractères, etc.) Notez que les valeurs de cet en-tête sont définies de différentes manières dans RFC1049 et dans MIME (RFC2045). Recherchez l'en-tête MIME-version: pour comprendre si Content-Type doit être interprété selon RFC1049 ou selon MIME (RFC2045). La définition MIME doit être utilisée pour générer le courrier. Historiquement, le champ Content-Type était proposé dans la RFC1049. Dans celui-ci, Content-Type ne distinguait pas le type et le sous-type comme le fait RFC2045. Exemple : Content-Type : text/plain ; charset="us-ascii" Type de contenu : text/plain ; charset=US-ASCII Content-Type : text/plain ; charset="iso-8859-1" Type de contenu : text/plain ; charset=koi8-r Content-Type : text/plain ; jeu de caractères=inconnu-8bit |
| static [Date](../../aspose.email/headertype/date) { get; } | Cet en-tête spécifie une date (et une heure), normalement la date à laquelle le message a été composé et envoyé. Dans les systèmes de messagerie X.400, heure à laquelle un message a été soumis. Certains systèmes de messagerie Internet utilisent également la date à laquelle le message a été soumis. Si cet en-tête est omis par l'ordinateur de l'expéditeur, il est concevable qu'il soit ajouté par un serveur de messagerie ou même par une autre machine le long de la route. Ce que vous ne savez peut-être pas, c'est que les informations de la ligne "Date :" sont fournies par l'heure de l'ordinateur de l'expéditeur, qui peut être définie correctement ou non. De plus, l'en-tête "Date :" n'indique normalement pas quand le message a été envoyé, mais seulement quand il a été composé. La date est sous la forme jour de la semaine à 3 caractères (dim - sam), numéro du jour (1-31) jj, nom du mois à 3 caractères, année à 4 chiffres aaaa, suivi de l'heure (24 heures) hh :mm:ss et format zone zzz. Le fuseau horaire (zzz) est soit le fuseau horaire à 3 caractères, soit le différentiel local en heures et minutes décalé par rapport à UTC (Universal Time Coordinated - ancien temps moyen de Greenwich). "-" indique l'ouest et "+" indique l'est de UTC. Aucune définition de fuseau horaire standard ne semble exister. De nombreuses versions d'UNIX comprennent un large éventail d'abréviations, mais la liste la plus exhaustive que j'ai trouvée était l'élément Timezone du manuel GNU tar et la documentation du module de manipulation de date Perl TIMEZONES. Exemple : Date : mardi 9 janvier 2001 23:40:00 -0800 Date : dimanche 1er avril 2001 22:52:04 EDT Date : lundi 2 avril 2001 16:02:19 +0200 Date : ven, 30 mars 2001 10:47:15 -0800 |
| static [DispositionNotificationTo](../../aspose.email/headertype/dispositionnotificationto) { get; } | Lorsque le champ DispositionNotificationTo est défini, une demande de MDN (Message Delivery Notification) est effectuée. Le logiciel de messagerie du destinataire (Outlook, Eudora, etc.) peut ignorer silencieusement la demande ou demander à l'utilisateur l'autorisation d'envoyer le MDN. Il n'y a aucune garantie de "récépissé de retour". Le champ DispositionNotificationTo est la norme de facto pour demander des accusés de réception (c'est-à-dire MDN ou notifications de livraison de message). |
| static [FollowupTo](../../aspose.email/headertype/followupto) { get; } | Utilisé dans Usenet News pour indiquer que les discussions futures (= suivi) sur un article doivent aller dans un ensemble de groupes de discussion différent de celui auquel l'article a répondu. L'utilisation la plus courante est lorsqu'un article est posté sur plusieurs groupes de discussion et que les discussions ultérieures doivent avoir lieu dans un seul d'entre eux. Défini dans RFC 1036 : 2.2.3, non normalisé pour une utilisation dans les e-mails. |
| static [From](../../aspose.email/headertype/from) { get; } | Ce champ contient l'identité de la ou des personnes qui ont souhaité que ce message soit envoyé. Le processus de création de message doit par défaut ce champ être une seule adresse de machine authentifiée, indiquant l'AGENT (personne, système ou processus) qui compose le message. Si cela n'est pas fait, le champ "Expéditeur :" DOIT être présent. Si le champ « De : » EST défini par défaut de cette façon, le champ « Expéditeur : » est facultatif et est redondant avec le champ « De : ». Exemple : De : "M. Quelqu'un" quelqu'un@undomaine.com |
| static [Importance](../../aspose.email/headertype/importance) { get; } | Obtient l'importance. |
| static [InReplyTo](../../aspose.email/headertype/inreplyto) { get; } | Référence au message auquel ce message est une réponse. |
| static [MessageID](../../aspose.email/headertype/messageid) { get; } | ID unique de ce message. Défini dans RFC 822 : 4.6.1, RFC 1036 : 2.1.5. |
| static [MIMEVersion](../../aspose.email/headertype/mimeversion) { get; } | Un indicateur que ce message est formaté selon la norme MIME, et une indication de la version de MIME qui est utilisée. Défini dans RFC 2045 |
| static [Newsgroups](../../aspose.email/headertype/newsgroups) { get; } | Dans Usenet News : groupe(s) auquel cet article a été posté. Certains systèmes fournissent ce champ d'en-tête également dans les e-mails bien qu'il n'y soit pas normalisé. Malheureusement, le champ d'en-tête peut apparaître dans un e-mail avec trois significations différentes et contradictoires : (a) Indique le destinataire du groupe de discussion d'un article/message envoyé à la fois aux destinataires de l'e-mail et de Usenet News. (b) Dans un message adressé à certains courriers vers des passerelles de nouvelles, indique le ou les groupes de discussion auxquels le message doit être envoyé. (c) Dans une réponse adressée personnellement à un article dans un groupe de discussion, en indiquant le groupe de discussion dans lequel cette discussion est née. Défini dans RFC 1036 : 2.1.3, non standardisé et controversé pour une utilisation dans les e-mails. |
| static [Received](../../aspose.email/headertype/received) { get; } | Trace des MTA qu'un message est passé. Défini dans RFC 822 |
| static [References](../../aspose.email/headertype/references) { get; } | Référence à d'autres messages connexes. |
| static [ReplyTo](../../aspose.email/headertype/replyto) { get; } | Ce champ d'en-tête est destiné à indiquer où l'expéditeur souhaite que les réponses aillent. Malheureusement, cela est ambigu, car il existe différents types de réponses, que l'expéditeur peut souhaiter envoyer à différentes adresses. En particulier, il existe des réponses personnelles destinées à une seule personne, et des réponses de groupe, destinées à l'ensemble des personnes qui lisent le message répondu (souvent une liste de diffusion, un nom de groupe de discussion ne peut pas apparaître ici en raison d'une syntaxe différente, voir " Suivi de" .). |
| static [ReturnPath](../../aspose.email/headertype/returnpath) { get; } | Utilisé pour transmettre les informations de l'attribut d'enveloppe MAIL FROM dans la livraison finale, lorsque le message quitte l'environnement SMTP dans lequel "MAIL FROM" est utilisé. /// |
| static [ReturnReceiptTo](../../aspose.email/headertype/returnreceiptto) { get; } | Un expéditeur peut demander un accusé de réception en incluant ce champ d'en-tête. L'accusé de réception est envoyé à l'adresse Return-Path de l'e-mail et non à l'adresse spécifiée dans le champ d'en-tête Return-Receipt-To. Cet en-tête n'est pas standard et n'est généralement pas pris en charge. Utilisez Disposition-Notification-To à la place. Même si pris en charge, il n'y a aucune garantie d'envoi d'un accusé de réception. |
| static [Sender](../../aspose.email/headertype/sender) { get; } | La personne ou l'agent soumettant le message au réseau, s'il n'est pas indiqué par le champ d'en-tête De :. Devrait être authentifié, selon RFC 822, mais quel type d'authentification n'est pas clair. |
| static [Sensitivity](../../aspose.email/headertype/sensitivity) { get; } | Obtient la sensibilité. |
| static [Subject](../../aspose.email/headertype/subject) { get; } | Titre, titre, sujet. Souvent utilisé comme indicateur de fil pour les messages répondant ou commentant d'autres messages. |
| static [To](../../aspose.email/headertype/to) { get; } | Destinataires principaux. Exemple : À : quelqu'un@undomaine.com |
| static [XConfirmReadingTo](../../aspose.email/headertype/xconfirmreadingto) { get; } | Cet en-tête demande un avis de confirmation automatisé lorsque le message est reçu ou lu. Il est généralement ignoré ; vraisemblablement certains logiciels agissent dessus. |
| static [XMailer](../../aspose.email/headertype/xmailer) { get; } | Informations sur le logiciel client de l'auteur. Exemple : X-Mailer : Aspose.Email |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.email/headertype/equals)(object) | Renvoie un booléen indiquant si l'objet obj transmis est égal à ceci. |
| override [GetHashCode](../../aspose.email/headertype/gethashcode)() | Sert de fonction de hachage pour un type particulier. |
| override [ToString](../../aspose.email/headertype/tostring)() | Renvoie unString qui représente le courantObject . |
| [implicit operator](../../aspose.email/headertype/op_implicit) | Effectue une conversion implicite de[`HeaderType`](../headertype) àString . |

### Voir également

* espace de noms [Aspose.Email](../../aspose.email)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->