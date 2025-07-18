---
title: SyntaxValidatingEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the SyntaxValidating event.
type: docs
weight: 697
url: /java/com.aspose.email/syntaxvalidatingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class SyntaxValidatingEventArgs extends System.EventArgs
```

Provides data for the SyntaxValidating event.
## Constructors

| Constructor | Description |
| --- | --- |
| [SyntaxValidatingEventArgs(String mail)](#SyntaxValidatingEventArgs-java.lang.String-) | Initializes a new instance of the SyntaxValidatingEventArgs class. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMail()](#getMail--) | Gets the mail address is being validating. |
| [getResult()](#getResult--) | Gets or sets the validation result. |
| [getSkip()](#getSkip--) | Indicates whether to ignore the check. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResult(ValidationResult value)](#setResult-com.aspose.email.ValidationResult-) | Gets or sets the validation result. |
| [setSkip(boolean value)](#setSkip-boolean-) | Indicates whether to ignore the check. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SyntaxValidatingEventArgs(String mail) {#SyntaxValidatingEventArgs-java.lang.String-}
```
public SyntaxValidatingEventArgs(String mail)
```


Initializes a new instance of the SyntaxValidatingEventArgs class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mail | java.lang.String | The mail address. |

### Empty {#Empty}
```
public static final System.EventArgs Empty
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMail() {#getMail--}
```
public final String getMail()
```


Gets the mail address is being validating.

**Returns:**
java.lang.String
### getResult() {#getResult--}
```
public final ValidationResult getResult()
```


Gets or sets the validation result.

**Returns:**
[ValidationResult](../../com.aspose.email/validationresult)
### getSkip() {#getSkip--}
```
public final boolean getSkip()
```


Indicates whether to ignore the check.

**Returns:**
boolean
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




### setResult(ValidationResult value) {#setResult-com.aspose.email.ValidationResult-}
```
public final void setResult(ValidationResult value)
```


Gets or sets the validation result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ValidationResult](../../com.aspose.email/validationresult) |  |

### setSkip(boolean value) {#setSkip-boolean-}
```
public final void setSkip(boolean value)
```


Indicates whether to ignore the check.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

