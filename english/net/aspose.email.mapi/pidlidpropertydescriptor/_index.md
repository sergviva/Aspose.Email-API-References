---
title: Class PidLidPropertyDescriptor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.PidLidPropertyDescriptor class. Class contains property description information
type: docs
weight: 19200
url: /net/aspose.email.mapi/pidlidpropertydescriptor/
---
## PidLidPropertyDescriptor class

Class contains property description information.

```csharp
public class PidLidPropertyDescriptor : PropertyDescriptor
```

## Constructors

| Name | Description |
| --- | --- |
| [PidLidPropertyDescriptor](pidlidpropertydescriptor/#constructor)(long, PropertyDataType, Guid) | Initializes a new instance of the `PidLidPropertyDescriptor` class Properties identified by an unsigned 32-bit quantity along with a property set. |
| [PidLidPropertyDescriptor](pidlidpropertydescriptor/#constructor_1)(string, long, PropertyDataType, Guid) | Initializes a new instance of the `PidLidPropertyDescriptor` class Properties identified by an unsigned 32-bit quantity along with a property set. |
| [PidLidPropertyDescriptor](pidlidpropertydescriptor/#constructor_2)(string, string, long, PropertyDataType, Guid) | Initializes a new instance of the `PidLidPropertyDescriptor` class Properties identified by an unsigned 32-bit quantity along with a property set. |

## Properties

| Name | Description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname/) { get; } | The name used to refer to the property in the documentation. The prefix of the canonical name identifies the basic characteristics of a property to the implementer. The canonical naming structure uses three categories that are denoted by the following prefixes to the canonical property name: * PidLid prefix: Properties identified by an unsigned 32-bit quantity along with a property set. * PidName prefix: Properties identified by a string name along with a property set. * PidTag prefix: Properties identified by an unsigned 16-bit quantity. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype/) { get; } | The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property. |
| [LongId](../../aspose.email.mapi/pidlidpropertydescriptor/longid/) { get; } | Gets an unsigned 32-bit quantity that, along with the property set, identifies a named property. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype/) { get; } | Indicates if data type contains of multiple values |
| [Name](../../aspose.email.mapi/propertydescriptor/name/) { get; } | Gets string that, identifies a property. |
| [PropertySet](../../aspose.email.mapi/pidlidpropertydescriptor/propertyset/) { get; } | A GUID that identifies a group of properties with a similar purpose. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidlidpropertydescriptor/equals/#equals_1)(object) | Determines whether the specified System.Object is equal to the current System.Object. |
| override [Equals](../../aspose.email.mapi/pidlidpropertydescriptor/equals/#equals)(PropertyDescriptor) | Indicates whether the current object is equal to another object of the same type. |
| override [GetHashCode](../../aspose.email.mapi/pidlidpropertydescriptor/gethashcode/)() | Serves as a hash function for a type. |
| override [ToString](../../aspose.email.mapi/pidlidpropertydescriptor/tostring/)() | Returns a string that represents the property description. |
| [operator ==](../../aspose.email.mapi/pidlidpropertydescriptor/op_equality/) | Determines whether the specified objects are equal to each another. |
| [operator !=](../../aspose.email.mapi/pidlidpropertydescriptor/op_inequality/) | Determines whether the specified objects are not equal to each another. |

### See Also

* class [PropertyDescriptor](../propertydescriptor/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


