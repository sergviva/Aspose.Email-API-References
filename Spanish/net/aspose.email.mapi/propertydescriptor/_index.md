---
title: PropertyDescriptor
second_title: Referencia de la API de Aspose.Email para .NET
description: La clase contiene información de descripción de la propiedad.
type: docs
weight: 19010
url: /es/net/aspose.email.mapi/propertydescriptor/
---
## PropertyDescriptor class

La clase contiene información de descripción de la propiedad.

```csharp
public abstract class PropertyDescriptor : IEquatable<PropertyDescriptor>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | El nombre utilizado para referirse a la propiedad en la documentación. El prefijo del nombre canónico identifica las características básicas de una propiedad para el implementador. La estructura de nomenclatura canónica utiliza tres categorías que se indican mediante los siguientes prefijos al nombre de propiedad canónica: * Prefijo PidLid: propiedades identificadas por una cantidad de 32 bits sin firmar junto con un conjunto de propiedades. * Prefijo PidName: propiedades identificadas por un nombre de cadena junto con un conjunto de propiedades. * Prefijo PidTag: propiedades identificadas por una cantidad de 16 bits sin signo. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | El tipo de valor de propiedad, como se describe en [MS-OXCDATA], que especifica el tipo de valores permitidos para la propiedad. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Indica si el tipo de datos contiene varios valores |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Obtiene una cadena que identifica una propiedad. |
| static [Use8BitStringAsUnicode](../../aspose.email.mapi/propertydescriptor/use8bitstringasunicode) { get; set; } | Especifica si PropertyDataType.String8 debe interpretarse como PropertyDataType.String |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_4)(MapiProperty) | recupera[`PropertyDescriptor`](../propertydescriptor) objeto de MAPI property |
| static [Parse](../../aspose.email.mapi/propertydescriptor/parse)(string) | Inicializa una nueva instancia del[`PropertyDescriptor`](../propertydescriptor) clase |
| abstract [Equals](../../aspose.email.mapi/propertydescriptor/equals#equals)(PropertyDescriptor) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_3)(long) | recupera[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) objeto |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_2)(int, PropertyDataType) | recupera[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) objeto |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance)(long, PropertyDataType, Guid) | recupera[`PidLidPropertyDescriptor`](../pidlidpropertydescriptor) objeto |
| static [GetInstance](../../aspose.email.mapi/propertydescriptor/getinstance#getinstance_1)(string, PropertyDataType, Guid) | recupera[`PidNamePropertyDescriptor`](../pidnamepropertydescriptor) objeto |
| [operator ==](../../aspose.email.mapi/propertydescriptor/op_equality) | Determina si los objetos especificados son iguales entre sí. |
| [operator !=](../../aspose.email.mapi/propertydescriptor/op_inequality) | Determina si los objetos especificados no son iguales entre sí. |

### Ver también

* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->