---
title: Task
second_title: Aspose.Email for Java API Reference
description:  Represents the exchange task information.
type: docs
weight: 657
url: /java/com.aspose.email/task/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Task implements System.IDisposable, Closeable
```

Represents the exchange task information.
## Constructors

| Constructor | Description |
| --- | --- |
| [Task()](#Task--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRelatedTo()](#getRelatedTo--) | Gets or sets a related UID |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | Gets or sets a related UID |
| [getSubject()](#getSubject--) | Gets or sets a task subject. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets a task subject. |
| [getStartDate()](#getStartDate--) | Gets or sets a start date of task. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets a start date of task. |
| [getDueDate()](#getDueDate--) | Gets or sets the date by which the user expects work on the task to be complete. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Gets or sets the date by which the user expects work on the task to be complete. |
| [getPriority()](#getPriority--) | Gets or sets a task priority. |
| [setPriority(int value)](#setPriority-int-) | Gets or sets a task priority. |
| [getPercentComplete()](#getPercentComplete--) | Gets or sets a pecent of task completion. |
| [setPercentComplete(float value)](#setPercentComplete-float-) | Gets or sets a pecent of task completion. |
| [getBody()](#getBody--) | Gets or sets a task body. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets or sets a task body. |
| [getUniqueId()](#getUniqueId--) | Gets or sets unique identifier |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Gets or sets unique identifier |
| [getSequenceId()](#getSequenceId--) | Gets or sets the sequence id. |
| [setSequenceId(int value)](#setSequenceId-int-) | Gets or sets the sequence id. |
| [getAttendees()](#getAttendees--) | Gets or sets the attendees. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Gets or sets the attendees. |
| [getOrganizer()](#getOrganizer--) | Gets or sets the organizer. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Gets or sets the organizer. |
| [getMethod()](#getMethod--) | Gets or sets iTIP methods associated with an task. |
| [setMethod(int value)](#setMethod-int-) | Gets or sets iTIP methods associated with an task. |
| [getAttachments()](#getAttachments--) | Gets or sets a collection of file attached to the task. |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | Gets or sets a collection of file attached to the task. |
| [request()](#request--) | Requests the object. |
| [close()](#close--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves current object to the given stream using MSG format. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves current object to the given stream using specified format. |
| [save(String filePath)](#save-java.lang.String-) | Saves current object into file using MSG format. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves current object into file using specified format. |
| [dispose()](#dispose--) | Release all resources. |
### Task() {#Task--}
```
public Task()
```


### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


Gets or sets a related UID

**Returns:**
java.lang.String
### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


Gets or sets a related UID

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets a task subject.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets a task subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets a start date of task.

**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets a start date of task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Gets or sets the date by which the user expects work on the task to be complete.

**Returns:**
java.util.Date
### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Gets or sets the date by which the user expects work on the task to be complete.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getPriority() {#getPriority--}
```
public final int getPriority()
```


Gets or sets a task priority.

**Returns:**
int
### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


Gets or sets a task priority.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPercentComplete() {#getPercentComplete--}
```
public final float getPercentComplete()
```


Gets or sets a pecent of task completion.

**Returns:**
float
### setPercentComplete(float value) {#setPercentComplete-float-}
```
public final void setPercentComplete(float value)
```


Gets or sets a pecent of task completion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBody() {#getBody--}
```
public final String getBody()
```


Gets or sets a task body.

**Returns:**
java.lang.String
### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Gets or sets a task body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets or sets unique identifier

**Returns:**
java.lang.String
### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Gets or sets unique identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Gets or sets the sequence id.

Value: The sequence id.

**Returns:**
int
### setSequenceId(int value) {#setSequenceId-int-}
```
public final void setSequenceId(int value)
```


Gets or sets the sequence id.

Value: The sequence id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


Gets or sets the attendees.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


Gets or sets the attendees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


Gets or sets the organizer.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


Gets or sets the organizer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### getMethod() {#getMethod--}
```
public final int getMethod()
```


Gets or sets iTIP methods associated with an task.

**Returns:**
int
### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Gets or sets iTIP methods associated with an task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAttachments() {#getAttachments--}
```
public final AttachmentCollection getAttachments()
```


Gets or sets a collection of file attached to the task.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### setAttachments(AttachmentCollection value) {#setAttachments-com.aspose.email.AttachmentCollection-}
```
public final void setAttachments(AttachmentCollection value)
```


Gets or sets a collection of file attached to the task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AttachmentCollection](../../com.aspose.email/attachmentcollection) |  |

### request() {#request--}
```
public final AlternateView request()
```


Requests the object.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### close() {#close--}
```
public void close()
```




### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves current object to the given stream using MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int saveFormat)
```


Saves current object to the given stream using specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to. |
| saveFormat | int | A save format. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Saves current object into file using MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name. |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public void save(String filePath, int saveFormat)
```


Saves current object into file using specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name. |
| saveFormat | int | A save format. |

### dispose() {#dispose--}
```
public final void dispose()
```


Release all resources.
