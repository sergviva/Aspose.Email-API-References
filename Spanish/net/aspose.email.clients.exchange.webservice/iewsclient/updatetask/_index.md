---
title: UpdateTask
second_title: Referencia de la API de Aspose.Email para .NET
description: Actualiza la tarea especificada.
type: docs
weight: 1520
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/updatetask/
---
## UpdateTask(MapiTask) {#updatetask}

Actualiza la tarea especificada.

```csharp
public string UpdateTask(MapiTask task)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| task | MapiTask | Un[`MapiTask`](../../../aspose.email.mapi/mapitask) que contiene la información de la tarea. |

### Valor_devuelto

Tarea uri.

### Ver también

* class [MapiTask](../../../aspose.email.mapi/mapitask)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## UpdateTask(string, MapiTask) {#updatetask_1}

Actualiza la tarea especificada.

```csharp
public string UpdateTask(string uri, MapiTask task)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uri | String | Identificador de tareas |
| task | MapiTask | Un[`ExchangeTask`](../../exchangetask) que contiene la información de la tarea. |

### Valor_devuelto

Tarea uri.

### Ver también

* class [MapiTask](../../../aspose.email.mapi/mapitask)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## UpdateTask(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) {#updatetask_2}

Actualiza la tarea especificada.

```csharp
public string UpdateTask(string uri, MapiTask task, 
    IEnumerable<PropertyDescriptor> additionalProperties)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uri | String | Identificador de tareas |
| task | MapiTask | Un[`ExchangeTask`](../../exchangetask) que contiene la información de la tarea. |
| additionalProperties | IEnumerable`1 | Una propiedad MAPI adicional que se puede usar en el objeto MAPI. |

### Valor_devuelto

Tarea uri.

### Ver también

* class [MapiTask](../../../aspose.email.mapi/mapitask)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## UpdateTask(ExchangeTask) {#updatetask_3}

Actualiza la tarea especificada.

```csharp
public void UpdateTask(ExchangeTask task)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| task | ExchangeTask | Un[`ExchangeTask`](../../exchangetask) que contiene la información de la tarea. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | Una propiedad UniqueUri de*task* es`nulo`o`vacío`. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task* es`nulo`. |

### Ver también

* class [ExchangeTask](../../exchangetask)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## UpdateTask(ExchangeTask, UpdateTaskOptions) {#updatetask_4}

Actualiza la tarea especificada.

```csharp
public void UpdateTask(ExchangeTask task, UpdateTaskOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| task | ExchangeTask | Un[`ExchangeTask`](../../exchangetask) que contiene la información de la tarea. |
| options | UpdateTaskOptions | Opciones de actualización. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | Una propiedad UniqueUri de*task* es`nulo`o`vacío`. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task* es`nulo`. |

### Ver también

* class [ExchangeTask](../../exchangetask)
* enum [UpdateTaskOptions](../../updatetaskoptions)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->