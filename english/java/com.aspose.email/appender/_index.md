---
title: Appender
second_title: Aspose.Email for Java API Reference
description: Represents the base class for Appender.
type: docs
weight: 31
url: /java/com.aspose.email/appender/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IAppender](../../com.aspose.email/iappender), com.aspose.ms.System.IDisposable
```
public abstract class Appender implements IAppender, System.IDisposable
```

Represents the base class for Appender.
## Methods

| Method | Description |
| --- | --- |
| [append(LogEntry entry)](#append-com.aspose.email.LogEntry-) | Appends the specified log entry to the appender. |
| [appendHeader()](#appendHeader--) | Starts log file with specific header. |
| [close()](#close--) | Closes the appender. |
| [dispose()](#dispose--) | Releases the unmanaged resources used by the Appender. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormatter()](#getFormatter--) | Gets or sets the formatter. |
| [hashCode()](#hashCode--) |  |
| [initialize()](#initialize--) | Initializes the appender instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFormatter(IFormatter value)](#setFormatter-com.aspose.email.IFormatter-) | Gets or sets the formatter. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### append(LogEntry entry) {#append-com.aspose.email.LogEntry-}
```
public abstract void append(LogEntry entry)
```


Appends the specified log entry to the appender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entry | [LogEntry](../../com.aspose.email/logentry) | The log entry. |

### appendHeader() {#appendHeader--}
```
public void appendHeader()
```


Starts log file with specific header.

### close() {#close--}
```
public void close()
```


Closes the appender.

### dispose() {#dispose--}
```
public final void dispose()
```


Releases the unmanaged resources used by the Appender.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFormatter() {#getFormatter--}
```
public final IFormatter getFormatter()
```


Gets or sets the formatter.

**Returns:**
[IFormatter](../../com.aspose.email/iformatter)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize() {#initialize--}
```
public void initialize()
```


Initializes the appender instance.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFormatter(IFormatter value) {#setFormatter-com.aspose.email.IFormatter-}
```
public final void setFormatter(IFormatter value)
```


Gets or sets the formatter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormatter](../../com.aspose.email/iformatter) |  |

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

