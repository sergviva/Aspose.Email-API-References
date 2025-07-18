---
title: PemReader
second_title: Aspose.Email for Java API Reference
description: PEM format reader.
type: docs
weight: 584
url: /java/com.aspose.email/pemreader/
---

**Inheritance:**
java.lang.Object
```
public class PemReader
```

PEM format reader.
## Constructors

| Constructor | Description |
| --- | --- |
| [PemReader()](#PemReader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrivateKey(InputStream pem)](#getPrivateKey-java.io.InputStream-) | Reads private key from stream |
| [getPrivateKey(String pemFile)](#getPrivateKey-java.lang.String-) | Reads private key from PEM file |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PemReader() {#PemReader--}
```
public PemReader()
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
### getPrivateKey(InputStream pem) {#getPrivateKey-java.io.InputStream-}
```
public static PrivateKey getPrivateKey(InputStream pem)
```


Reads private key from stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pem | java.io.InputStream | Stream to read from |

**Returns:**
java.security.PrivateKey - Certificate that was read
### getPrivateKey(String pemFile) {#getPrivateKey-java.lang.String-}
```
public static PrivateKey getPrivateKey(String pemFile)
```


Reads private key from PEM file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pemFile | java.lang.String | path to file to read from |

**Returns:**
java.security.PrivateKey - Certificate that was read
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

