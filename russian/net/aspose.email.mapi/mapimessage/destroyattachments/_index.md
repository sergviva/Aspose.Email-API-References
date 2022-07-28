---
title: DestroyAttachments
second_title: Справочник по Aspose.Email для .NET API
description: Уничтожает вложения в указанных файлах сообщений Outlook. DestroyAttachments игнорирует разбор вложений.
type: docs
weight: 410
url: /ru/net/aspose.email.mapi/mapimessage/destroyattachments/
---
## MapiMessage.DestroyAttachments method

Уничтожает вложения в указанных файлах сообщений Outlook. DestroyAttachments игнорирует разбор вложений.

```csharp
public static void DestroyAttachments(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Имя файла сообщений Outlook. |

### Примеры

В следующем примере показано, как уничтожить вложения в файлах сообщений Outlook.

[C#]

```csharp
//Уничтожить вложения из сообщений Outlook files
apiMessage.DestroyAttachment(@"c:\outlookmessage.msg");
```

[Visual Basic]

```csharp
'Уничтожить вложения из файлов сообщений Outlook
MapiMessage.DestroyAttachment("c:\outlookmessage.msg")
```

### Смотрите также

* class [MapiMessage](../../mapimessage)
* пространство имен [Aspose.Email.Mapi](../../mapimessage)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->