---
title: MapiCalendarRecurrencePattern
second_title: Aspose.Email for Java API Reference
description: Represents the mapi recurrence pattern
type: docs
weight: 422
url: /java/com.aspose.email/mapicalendarrecurrencepattern/
---

**Inheritance:**
java.lang.Object
```
public abstract class MapiCalendarRecurrencePattern
```

Represents the mapi recurrence pattern
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarRecurrencePattern()](#MapiCalendarRecurrencePattern--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendarType()](#getCalendarType--) | Gets or sets the type of calendar that is used |
| [getClass()](#getClass--) |  |
| [getDeletedInstanceDates()](#getDeletedInstanceDates--) | An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence. |
| [getEndDate()](#getEndDate--) | Gets or sets Defines the end date of an item recurrence pattern. |
| [getEndType()](#getEndType--) | Gets or sets the ending type for the recurrence. |
| [getExceptions()](#getExceptions--) | An exception specifies changes to an instance of a recurring series. |
| [getFrequency()](#getFrequency--) | Gets or sets the frequency of the recurring series. |
| [getModifiedInstanceDates()](#getModifiedInstanceDates--) | An array of dates, each of which is the date of a modified instance. |
| [getOccurrenceCount()](#getOccurrenceCount--) | Gets or sets the number of occurrences in a recurrence. |
| [getPatternType()](#getPatternType--) | Gets or sets the type of recurrence pattern |
| [getPeriod()](#getPeriod--) | Gets or sets interval at which the meeting pattern repeats |
| [getSlidingFlag()](#getSlidingFlag--) | Defines whether pattern is sliding or not. |
| [getStartDate()](#getStartDate--) | Gets or sets the start date of an item recurrence pattern. |
| [getWeekStartDay()](#getWeekStartDay--) | Gets or sets the first day of the calendar week. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendarType(int value)](#setCalendarType-int-) | Gets or sets the type of calendar that is used |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Gets or sets Defines the end date of an item recurrence pattern. |
| [setEndType(int value)](#setEndType-int-) | Gets or sets the ending type for the recurrence. |
| [setOccurrenceCount(long value)](#setOccurrenceCount-long-) | Gets or sets the number of occurrences in a recurrence. |
| [setPatternType(int value)](#setPatternType-int-) | Gets or sets the type of recurrence pattern |
| [setPeriod(long value)](#setPeriod-long-) | Gets or sets interval at which the meeting pattern repeats |
| [setSlidingFlag(boolean value)](#setSlidingFlag-boolean-) | Defines whether pattern is sliding or not. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the start date of an item recurrence pattern. |
| [setWeekStartDay(int value)](#setWeekStartDay-int-) | Gets or sets the first day of the calendar week. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarRecurrencePattern() {#MapiCalendarRecurrencePattern--}
```
public MapiCalendarRecurrencePattern()
```


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
### getCalendarType() {#getCalendarType--}
```
public final int getCalendarType()
```


Gets or sets the type of calendar that is used

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeletedInstanceDates() {#getDeletedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getDeletedInstanceDates()
```


An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets or sets Defines the end date of an item recurrence pattern.

**Returns:**
java.util.Date
### getEndType() {#getEndType--}
```
public final int getEndType()
```


Gets or sets the ending type for the recurrence.

**Returns:**
int
### getExceptions() {#getExceptions--}
```
public final System.Collections.Generic.IGenericList<MapiCalendarExceptionInfo> getExceptions()
```


An exception specifies changes to an instance of a recurring series.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiCalendarExceptionInfo>
### getFrequency() {#getFrequency--}
```
public int getFrequency()
```


Gets or sets the frequency of the recurring series.

**Returns:**
int
### getModifiedInstanceDates() {#getModifiedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getModifiedInstanceDates()
```


An array of dates, each of which is the date of a modified instance.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getOccurrenceCount() {#getOccurrenceCount--}
```
public final long getOccurrenceCount()
```


Gets or sets the number of occurrences in a recurrence.

**Returns:**
long
### getPatternType() {#getPatternType--}
```
public final int getPatternType()
```


Gets or sets the type of recurrence pattern

**Returns:**
int
### getPeriod() {#getPeriod--}
```
public abstract long getPeriod()
```


Gets or sets interval at which the meeting pattern repeats

**Returns:**
long
### getSlidingFlag() {#getSlidingFlag--}
```
public final boolean getSlidingFlag()
```


Defines whether pattern is sliding or not.

**Returns:**
boolean
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the start date of an item recurrence pattern.

**Returns:**
java.util.Date
### getWeekStartDay() {#getWeekStartDay--}
```
public final int getWeekStartDay()
```


Gets or sets the first day of the calendar week.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCalendarType(int value) {#setCalendarType-int-}
```
public final void setCalendarType(int value)
```


Gets or sets the type of calendar that is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Gets or sets Defines the end date of an item recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndType(int value) {#setEndType-int-}
```
public final void setEndType(int value)
```


Gets or sets the ending type for the recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOccurrenceCount(long value) {#setOccurrenceCount-long-}
```
public final void setOccurrenceCount(long value)
```


Gets or sets the number of occurrences in a recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPatternType(int value) {#setPatternType-int-}
```
public final void setPatternType(int value)
```


Gets or sets the type of recurrence pattern

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPeriod(long value) {#setPeriod-long-}
```
public abstract void setPeriod(long value)
```


Gets or sets interval at which the meeting pattern repeats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setSlidingFlag(boolean value) {#setSlidingFlag-boolean-}
```
public final void setSlidingFlag(boolean value)
```


Defines whether pattern is sliding or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the start date of an item recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setWeekStartDay(int value) {#setWeekStartDay-int-}
```
public final void setWeekStartDay(int value)
```


Gets or sets the first day of the calendar week.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

