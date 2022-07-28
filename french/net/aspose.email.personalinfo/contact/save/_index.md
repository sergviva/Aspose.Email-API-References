---
title: Save
second_title: Référence de l'API Aspose.Email pour .NET
description: Enregistre ceciMapiContactaspose.email.mapi/mapicontact dans le flux donné au format vCard. La version vCard prise en charge est 2.1
type: docs
weight: 410
url: /fr/net/aspose.email.personalinfo/contact/save/
---
## Save(Stream) {#save}

Enregistre ceci[`MapiContact`](../../../aspose.email.mapi/mapicontact) dans le flux donné au format vCard. La version vCard prise en charge est 2.1

```csharp
public void Save(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* est`nul` |
| NotSupportedException | *stream* ne prend pas en charge l'écriture |

### Voir également

* class [Contact](../../contact)
* espace de noms [Aspose.Email.PersonalInfo](../../contact)
* Assemblée [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Enregistre ceci[`MapiContact`](../../../aspose.email.mapi/mapicontact) au fichier vCard avec une option par défaut. La version vCard prise en charge est 2.1

```csharp
public void Save(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un nom de fichier vCard |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |

### Voir également

* class [Contact](../../contact)
* espace de noms [Aspose.Email.PersonalInfo](../../contact)
* Assemblée [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Enregistre ceci[`MapiContact`](../../../aspose.email.mapi/mapicontact) dans le fichier à l'aide des options d'enregistrement spécifiées. Les options d'enregistrement prises en charge sont[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un nom de fichier vCard |
| saveOptions | ContactSaveOptions | Une sauvegarde des options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* est`nul`ou`vide` |
| ArgumentNullException | *saveOptions* est`nul` |
| NotSupportedException | certaines options de sauvegarde ne sont pas prises en charge |

### Voir également

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [Contact](../../contact)
* espace de noms [Aspose.Email.PersonalInfo](../../contact)
* Assemblée [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Enregistre ceci[`MapiContact`](../../../aspose.email.mapi/mapicontact)au fichier spécifié avec un format utilisant les options par défaut. Le format de sauvegarde pris en charge est vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Un nom de fichier vCard |
| saveFormat | ContactSaveFormat | Un format de sauvegarde |

### Voir également

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [Contact](../../contact)
* espace de noms [Aspose.Email.PersonalInfo](../../contact)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Enregistre ceci[`Contact`](../../contact) au flux donné avec un format utilisant les options par défaut.

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |
| saveFormat | ContactSaveFormat | Un format de sauvegarde |

### Voir également

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [Contact](../../contact)
* espace de noms [Aspose.Email.PersonalInfo](../../contact)
* Assemblée [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Enregistre ceci[`Contact`](../../contact) au flux donné en utilisant les options de sauvegarde spécifiées.

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Un flux dans lequel enregistrer |
| saveOptions | ContactSaveOptions | Une sauvegarde des options |

### Voir également

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [Contact](../../contact)
* espace de noms [Aspose.Email.PersonalInfo](../../contact)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->