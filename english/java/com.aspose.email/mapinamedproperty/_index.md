---
title: MapiNamedProperty
second_title: Aspose.Email for Java API Reference
description: Represents the data type of Named Property.
type: docs
weight: 472
url: /java/com.aspose.email/mapinamedproperty/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiProperty](../../com.aspose.email/mapiproperty)
```
public final class MapiNamedProperty extends MapiProperty
```

Represents the data type of Named Property.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiNamedProperty()](#MapiNamedProperty--) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-long-java.util.UUID-byte---) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
## Methods

| Method | Description |
| --- | --- |
| [createMapiPropertyFromBytes(long tag, byte[] data)](#createMapiPropertyFromBytes-long-byte---) | Creates the mapi property from bytes. |
| [createMapiPropertyFromDateTime(long tag, Date data)](#createMapiPropertyFromDateTime-long-java.util.Date-) | Creates the mapi property from date time. |
| [createMapiPropertyFromLong(long tag, long data)](#createMapiPropertyFromLong-long-long-) | Creates the mapi property from long. |
| [createMapiPropertyFromLong(long tag, long data, long delimiter)](#createMapiPropertyFromLong-long-long-long-) | Creates the mapi property from long. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolean()](#getBoolean--) | Gets the first bytes of the binary data as boolean. |
| [getClass()](#getClass--) |  |
| [getCurrency()](#getCurrency--) | Gets the Currency as string using the specified code page. |
| [getData()](#getData--) | Gets the binary data. |
| [getDataType()](#getDataType--) | Gets the data type. |
| [getDateTime()](#getDateTime--) | Gets the first bytes of the binary data as datetime. |
| [getDescriptor()](#getDescriptor--) | Gets descriptor of MAPI property |
| [getDouble()](#getDouble--) | Gets the bytes of the binary data as double. |
| [getFloat()](#getFloat--) | Gets the bytes of the binary data as float. |
| [getFloatingDate()](#getFloatingDate--) | Gets the bytes of the binary data as DateTime. |
| [getGuid()](#getGuid--) | gets named property GUID |
| [getGuidValue()](#getGuidValue--) | Gets the bytes of the binary data as Guid. |
| [getIdentifier()](#getIdentifier--) | Gets the indifier. |
| [getInt32()](#getInt32--) | Gets the first 4 bytes of the binary data as int32. |
| [getKind()](#getKind--) | gets named property kind |
| [getLong()](#getLong--) | Gets the first 8 bytes of the binary data as long. |
| [getMVEntries()](#getMVEntries--) | Gets the MV entries list. |
| [getMultipleBinary()](#getMultipleBinary--) | Gets the multyple binary data. |
| [getMultipleBoolean()](#getMultipleBoolean--) | Gets the multyple bool values. |
| [getMultipleCurrency()](#getMultipleCurrency--) | Gets the multyple decimal values. |
| [getMultipleFloating32()](#getMultipleFloating32--) | Gets the multyple float values. |
| [getMultipleFloating64()](#getMultipleFloating64--) | Gets the multyple double values. |
| [getMultipleFloatingTime()](#getMultipleFloatingTime--) | Gets the multyple DateTime values. |
| [getMultipleGuid()](#getMultipleGuid--) | Gets the multyple Guid values. |
| [getMultipleInteger16()](#getMultipleInteger16--) | Gets the multyple Int16 values. |
| [getMultipleInteger32()](#getMultipleInteger32--) | Gets the multyple Int32 values. |
| [getMultipleInteger64()](#getMultipleInteger64--) | Gets the multyple Int64 values. |
| [getMultipleString()](#getMultipleString--) | Gets the multyple strings data. |
| [getMultipleTime()](#getMultipleTime--) | Gets the multyple DateTime values. |
| [getName()](#getName--) | Gets the name. |
| [getNameId()](#getNameId--) | gets named property ID |
| [getOom()](#getOom--) | gets OOM value |
| [getPropertyTagName()](#getPropertyTagName--) | Gets the PropertyName. |
| [getShort()](#getShort--) | Gets the first 2 bytes of the binary data as short. |
| [getString()](#getString--) | Gets the binary data as string. |
| [getString(int codepage)](#getString-int-) | Gets the binary data as string using the specified code page. |
| [getTag()](#getTag--) | Gets the tag. |
| [getValue()](#getValue--) | Gets value as object |
| [hashCode()](#hashCode--) |  |
| [isNamed()](#isNamed--) | Indicates whether the property is a named property. |
| [isSigned()](#isSigned--) | Indicates whether the binary data is signed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSigned(boolean value)](#setSigned-boolean-) | Indicates whether the binary data is signed. |
| [toString()](#toString--) | Returns a String that represents the current Object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiNamedProperty() {#MapiNamedProperty--}
```
public MapiNamedProperty()
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

### MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | long | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | java.lang.String | The name identifier that is used to refer to a named property. |
| propertyGuid | java.util.UUID | The property unique identifier. |
| propertyValue | byte[] | A property value. |

### MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-long-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | long | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | long | The name identifier that is used to refer to a named property. |
| propertyGuid | java.util.UUID | The property unique identifier. |
| propertyValue | byte[] | A property value. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | Property storage that can provide tag for named property |
| pd | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | Property descriptor |
| data | java.lang.Object | A property value. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | Property storage that can provide tag for named property |
| pd | [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) | Property descriptor |
| data | java.lang.Object | A property value. |

### createMapiPropertyFromBytes(long tag, byte[] data) {#createMapiPropertyFromBytes-long-byte---}
```
public static MapiProperty createMapiPropertyFromBytes(long tag, byte[] data)
```


Creates the mapi property from bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag. |
| data | byte[] | The data. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromDateTime(long tag, Date data) {#createMapiPropertyFromDateTime-long-java.util.Date-}
```
public static MapiProperty createMapiPropertyFromDateTime(long tag, Date data)
```


Creates the mapi property from date time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag. |
| data | java.util.Date | The data. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromLong(long tag, long data) {#createMapiPropertyFromLong-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data)
```


Creates the mapi property from long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag. |
| data | long | The data. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromLong(long tag, long data, long delimiter) {#createMapiPropertyFromLong-long-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data, long delimiter)
```


Creates the mapi property from long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag. |
| data | long | The data. |
| delimiter | long | The delimiter. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBoolean() {#getBoolean--}
```
public boolean getBoolean()
```


Gets the first bytes of the binary data as boolean.

**Returns:**
boolean - The boolean value.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrency() {#getCurrency--}
```
public BigDecimal getCurrency()
```


Gets the Currency as string using the specified code page.

**Returns:**
java.math.BigDecimal - A string contains the binary data.
### getData() {#getData--}
```
public byte[] getData()
```


Gets the binary data.

**Returns:**
byte[]
### getDataType() {#getDataType--}
```
public int getDataType()
```


Gets the data type.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public Date getDateTime()
```


Gets the first bytes of the binary data as datetime.

**Returns:**
java.util.Date - The datetime value.
### getDescriptor() {#getDescriptor--}
```
public final PropertyDescriptor getDescriptor()
```


Gets descriptor of MAPI property

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### getDouble() {#getDouble--}
```
public double getDouble()
```


Gets the bytes of the binary data as double.

**Returns:**
double - The double value.
### getFloat() {#getFloat--}
```
public float getFloat()
```


Gets the bytes of the binary data as float.

**Returns:**
float - The double value.
### getFloatingDate() {#getFloatingDate--}
```
public Date getFloatingDate()
```


Gets the bytes of the binary data as DateTime.

**Returns:**
java.util.Date - The DateTime value.
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


gets named property GUID

**Returns:**
java.util.UUID
### getGuidValue() {#getGuidValue--}
```
public UUID getGuidValue()
```


Gets the bytes of the binary data as Guid.

**Returns:**
java.util.UUID - The Guid value.
### getIdentifier() {#getIdentifier--}
```
public long getIdentifier()
```


Gets the indifier.

**Returns:**
long
### getInt32() {#getInt32--}
```
public int getInt32()
```


Gets the first 4 bytes of the binary data as int32.

**Returns:**
int - The int32 value.
### getKind() {#getKind--}
```
public final int getKind()
```


gets named property kind

**Returns:**
int
### getLong() {#getLong--}
```
public long getLong()
```


Gets the first 8 bytes of the binary data as long.

**Returns:**
long - The long value.
### getMVEntries() {#getMVEntries--}
```
public final System.Collections.IList getMVEntries()
```


Gets the MV entries list.

**Returns:**
com.aspose.ms.System.Collections.IList
### getMultipleBinary() {#getMultipleBinary--}
```
public final byte[][] getMultipleBinary()
```


Gets the multyple binary data.

**Returns:**
byte[][] - A multyple byte arrays.
### getMultipleBoolean() {#getMultipleBoolean--}
```
public final boolean[] getMultipleBoolean()
```


Gets the multyple bool values.

**Returns:**
boolean[] - A bool array.
### getMultipleCurrency() {#getMultipleCurrency--}
```
public final BigDecimal[] getMultipleCurrency()
```


Gets the multyple decimal values.

**Returns:**
java.math.BigDecimal[] - A decimal array.
### getMultipleFloating32() {#getMultipleFloating32--}
```
public final float[] getMultipleFloating32()
```


Gets the multyple float values.

**Returns:**
float[] - A float array.
### getMultipleFloating64() {#getMultipleFloating64--}
```
public final double[] getMultipleFloating64()
```


Gets the multyple double values.

**Returns:**
double[] - A double array.
### getMultipleFloatingTime() {#getMultipleFloatingTime--}
```
public final Date[] getMultipleFloatingTime()
```


Gets the multyple DateTime values.

**Returns:**
java.util.Date[] - A DateTime array.
### getMultipleGuid() {#getMultipleGuid--}
```
public final UUID[] getMultipleGuid()
```


Gets the multyple Guid values.

**Returns:**
java.util.UUID[] - A Guid array.
### getMultipleInteger16() {#getMultipleInteger16--}
```
public final short[] getMultipleInteger16()
```


Gets the multyple Int16 values.

**Returns:**
short[] - A Int16 array.
### getMultipleInteger32() {#getMultipleInteger32--}
```
public final int[] getMultipleInteger32()
```


Gets the multyple Int32 values.

**Returns:**
int[] - A Int32 array.
### getMultipleInteger64() {#getMultipleInteger64--}
```
public final long[] getMultipleInteger64()
```


Gets the multyple Int64 values.

**Returns:**
long[] - A Int64 array.
### getMultipleString() {#getMultipleString--}
```
public final String[] getMultipleString()
```


Gets the multyple strings data.

**Returns:**
java.lang.String[] - A string array.
### getMultipleTime() {#getMultipleTime--}
```
public final Date[] getMultipleTime()
```


Gets the multyple DateTime values.

**Returns:**
java.util.Date[] - A DateTime array.
### getName() {#getName--}
```
public String getName()
```


Gets the name.

**Returns:**
java.lang.String
### getNameId() {#getNameId--}
```
public final String getNameId()
```


gets named property ID

**Returns:**
java.lang.String
### getOom() {#getOom--}
```
public final String getOom()
```


gets OOM value

**Returns:**
java.lang.String
### getPropertyTagName() {#getPropertyTagName--}
```
public String getPropertyTagName()
```


Gets the PropertyName.

**Returns:**
java.lang.String
### getShort() {#getShort--}
```
public short getShort()
```


Gets the first 2 bytes of the binary data as short.

**Returns:**
short - The short value.
### getString() {#getString--}
```
public String getString()
```


Gets the binary data as string.

**Returns:**
java.lang.String - A string contains the binary data.
### getString(int codepage) {#getString-int-}
```
public String getString(int codepage)
```


Gets the binary data as string using the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | The code page. |

**Returns:**
java.lang.String - A string contains the binary data.
### getTag() {#getTag--}
```
public long getTag()
```


Gets the tag.

**Returns:**
long
### getValue() {#getValue--}
```
public final Object getValue()
```


Gets value as object

**Returns:**
java.lang.Object - value of a property
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNamed() {#isNamed--}
```
public final boolean isNamed()
```


Indicates whether the property is a named property.

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Indicates whether the binary data is signed.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


Indicates whether the binary data is signed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents the current Object.

**Returns:**
java.lang.String - A String that represents the current Object.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

