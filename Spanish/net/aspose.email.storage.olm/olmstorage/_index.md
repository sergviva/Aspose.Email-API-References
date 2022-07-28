---
title: OlmStorage
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el archivo de almacenamiento de Outlook para Mac .OLM.
type: docs
weight: 20120
url: /es/net/aspose.email.storage.olm/olmstorage/
---
## OlmStorage class

Representa el archivo de almacenamiento de Outlook para Mac (.OLM).

```csharp
public class OlmStorage : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OlmStorage](olmstorage#constructor_1)(Stream) | Inicializa una nueva instancia del[`OlmStorage`](../olmstorage) clase. |
| [OlmStorage](olmstorage#constructor_2)(string) | Inicializa una nueva instancia del[`OlmStorage`](../olmstorage) clase. |
| [OlmStorage](olmstorage#constructor)(TraversalExceptionsCallback) | Inicializa una nueva instancia del[`OlmStorage`](../olmstorage)class. Permite establecer un método de devolución de llamada para manejar las excepciones que ocurren durante el recorrido de almacenamiento OLM. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FolderHierarchy](../../aspose.email.storage.olm/olmstorage/folderhierarchy) { get; } | Obtiene la jerarquía de carpetas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFile](../../aspose.email.storage.olm/olmstorage/fromfile)(string) | Cargar almacenamiento OLM desde archivo. |
| static [FromStream](../../aspose.email.storage.olm/olmstorage/fromstream)(Stream) | Cargar OLM desde stream. |
| [Dispose](../../aspose.email.storage.olm/olmstorage/dispose)() | Realiza tareas definidas por la aplicación asociadas con la liberación, liberación o el restablecimiento de recursos no administrados. |
| [EnumerateMessages](../../aspose.email.storage.olm/olmstorage/enumeratemessages)(OlmFolder) | Expone el enumerador, que admite una iteración de mensajes en la carpeta. |
| [ExtractMapiMessage](../../aspose.email.storage.olm/olmstorage/extractmapimessage)(OlmMessageInfo) | Obtener el mensaje del almacenamiento OLM. |
| [GetFolder](../../aspose.email.storage.olm/olmstorage/getfolder)(string, bool) | Obtiene la carpeta por nombre. |
| [GetFolders](../../aspose.email.storage.olm/olmstorage/getfolders)() | Obtiene la colección de carpetas. |
| [Load](../../aspose.email.storage.olm/olmstorage/load#load)(Stream) | Cargar almacenamiento OLM desde flujo. Este método se usa cuando se crea un objeto OlmStorage usando un constructor con el parámetro TraversalExceptionsCallback. |
| [Load](../../aspose.email.storage.olm/olmstorage/load#load_1)(string) | Cargar almacenamiento OLM desde archivo. Este método se usa cuando se crea un objeto OlmStorage usando un constructor con el parámetro TraversalExceptionsCallback. |

### Ver también

* espacio de nombres [Aspose.Email.Storage.Olm](../../aspose.email.storage.olm)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->