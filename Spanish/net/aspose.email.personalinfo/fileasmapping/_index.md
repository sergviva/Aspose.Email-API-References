---
title: FileAsMapping
second_title: Referencia de la API de Aspose.Email para .NET
description: Especifica cómo generar y volver a calcular el valor de la propiedad dispidFileAs cuando cambian otras propiedades de nombre de contacto. Coincide con la revisión 16.2 de MS-OXPROPS del 31/7/2014
type: docs
weight: 19410
url: /es/net/aspose.email.personalinfo/fileasmapping/
---
## FileAsMapping enumeration

Especifica cómo generar y volver a calcular el valor de la propiedad dispidFileAs cuando cambian otras propiedades de nombre de contacto. Coincide con la revisión 16.2 de MS-OXPROPS del 31/7/2014

```csharp
public enum FileAsMapping : long
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Empty | `0` | Valor vacío. |
| DisplayName | `12289` | Nombre para mostrar |
| FirstName | `14854` | Nombre_dado |
| LastName | `14865` | Apellido |
| Organization | `14870` | Nombre de la empresa |
| FirstMiddleLastGen | `32823` | GivenName Segundo nombre Apellido Generation |
| LastFirstMiddle | `32791` | Apellido, Nombre Segundo Nombre |
| LastFirstMiddle2 | `32816` | ApellidoNombre Segundo Nombre |
| LastFirstMiddle3 | `32817` | Apellido Nombre Segundo Nombre |
| OrgLastFirstMiddle | `32792` | CompanyName\r\nSurname, GivenName MiddleName |
| OrgLastFirstMiddle2 | `32818` | CompanyName\r\nSurnameGivenName SecondName |
| OrgLastFirstMiddle3 | `32819` | CompanyName\r\nSurname GivenName SecondName |
| LastFirstMiddleOrg | `32793` | Apellido, GivenName Segundo nombre\r\nCompanyName |
| LastFirstMiddleOrg2 | `32820` | ApellidoGivenName Segundo nombre\r\nCompanyName |
| LastFirstMiddleOrg3 | `32821` | Apellido GivenName PidTagMiddleName\r\nCompanyName |
| LastFirstMiddleGen | `32822` | Apellido Nombre Segundo Nombre Generación |
| LastFirstMiddleGen2 | `32824` | ApellidoGivenName Segundo Nombre Generación |
| BestMatch | `4294967293` | Especifica que, al mostrar el contacto, la aplicación debe intentar usar el valor actual de dispidFileUnder y otras propiedades de contacto para encontrar la "mejor coincidencia" para dispidFileUnderId con uno de los valores anteriores de esta tabla. |
| AccordingToLocale | `4294967294` | Especifica que, al mostrar el contacto, la aplicación debe elegir los valores predeterminados apropiados (según la configuración regional del idioma) para dispidFileUnderId y actualizar dispidFileUnder para que coincida con la elección. |
| None | `4294967295` | Especifica que FileUnder es proporcionado por el usuario y no debe cambiarse cuando cambia otra propiedad de nombre de contacto. Es decir, el valor de FileUnder no se construye a partir de otras propiedades. |

### Ver también

* espacio de nombres [Aspose.Email.PersonalInfo](../../aspose.email.personalinfo)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->