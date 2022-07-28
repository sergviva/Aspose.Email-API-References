---
title: PidNamePropertyDescriptor
second_title: Referencia de la API de Aspose.Email para .NET
description: La clase contiene información de descripción de la propiedad.
type: docs
weight: 18980
url: /es/net/aspose.email.mapi/pidnamepropertydescriptor/
---
## PidNamePropertyDescriptor class

La clase contiene información de descripción de la propiedad.

```csharp
public class PidNamePropertyDescriptor : PropertyDescriptor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PidNamePropertyDescriptor](pidnamepropertydescriptor#constructor)(string, PropertyDataType, Guid) | Inicializa una nueva instancia del[`PidNamePropertyDescriptor`](../pidnamepropertydescriptor) class Propiedades identificadas por un nombre de cadena junto con un conjunto de propiedades. |
| [PidNamePropertyDescriptor](pidnamepropertydescriptor#constructor_1)(string, string, PropertyDataType, Guid) | Inicializa una nueva instancia del[`PidNamePropertyDescriptor`](../pidnamepropertydescriptor) class Propiedades identificadas por un nombre de cadena junto con un conjunto de propiedades. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | El nombre utilizado para referirse a la propiedad en la documentación. El prefijo del nombre canónico identifica las características básicas de una propiedad para el implementador. La estructura de nomenclatura canónica utiliza tres categorías que se indican mediante los siguientes prefijos al nombre de propiedad canónica: * Prefijo PidLid: propiedades identificadas por una cantidad de 32 bits sin firmar junto con un conjunto de propiedades. * Prefijo PidName: propiedades identificadas por un nombre de cadena junto con un conjunto de propiedades. * Prefijo PidTag: propiedades identificadas por una cantidad de 16 bits sin signo. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | El tipo de valor de propiedad, como se describe en [MS-OXCDATA], que especifica el tipo de valores permitidos para la propiedad. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Indica si el tipo de datos contiene varios valores |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Obtiene una cadena que identifica una propiedad. |
| [PropertySet](../../aspose.email.mapi/pidnamepropertydescriptor/propertyset) { get; } | GUID que identifica un grupo de propiedades con un propósito similar. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidnamepropertydescriptor/equals#equals_1)(object) | Determina si el System.Object especificado es igual al System.Object. actual |
| override [Equals](../../aspose.email.mapi/pidnamepropertydescriptor/equals#equals)(PropertyDescriptor) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| override [GetHashCode](../../aspose.email.mapi/pidnamepropertydescriptor/gethashcode)() | Sirve como función hash para un tipo. |
| override [ToString](../../aspose.email.mapi/pidnamepropertydescriptor/tostring)() | Devuelve una cadena que representa la descripción de la propiedad. |
| [operator ==](../../aspose.email.mapi/pidnamepropertydescriptor/op_equality) | Determina si los objetos especificados son iguales entre sí. |
| [operator !=](../../aspose.email.mapi/pidnamepropertydescriptor/op_inequality) | Determina si los objetos especificados no son iguales entre sí. |

### Ver también

* class [PropertyDescriptor](../propertydescriptor)
* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->