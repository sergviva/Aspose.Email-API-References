---
title: InboxRule
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa una regla de bandeja de entrada
type: docs
weight: 3510
url: /es/net/aspose.email.clients.exchange/inboxrule/
---
## InboxRule class

Representa una regla de bandeja de entrada

```csharp
public sealed class InboxRule
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [InboxRule](inboxrule)() | Inicializa una nueva instancia del[`InboxRule`](../inboxrule) clase |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.email.clients.exchange/inboxrule/actions) { get; set; } | Obtiene o establece las acciones que se realizarán en un mensaje cuando se cumplan las condiciones. |
| [Conditions](../../aspose.email.clients.exchange/inboxrule/conditions) { get; set; } | Obtiene o establece las condiciones que, cuando se cumplan, activarán las acciones de regla para esa regla. |
| [DisplayName](../../aspose.email.clients.exchange/inboxrule/displayname) { get; set; } | Obtiene o establece el nombre para mostrar de una regla. |
| [Exceptions](../../aspose.email.clients.exchange/inboxrule/exceptions) { get; set; } | Obtiene o establece las excepciones que representan todas las condiciones de excepción de regla disponibles para la regla de bandeja de entrada. |
| [IsEnabled](../../aspose.email.clients.exchange/inboxrule/isenabled) { get; set; } | Obtiene o establece un valor que indica si la regla está habilitada. |
| [IsInError](../../aspose.email.clients.exchange/inboxrule/isinerror) { get; } | Obtiene un valor que indica si la regla está en condición de error. |
| [IsNotSupported](../../aspose.email.clients.exchange/inboxrule/isnotsupported) { get; } | Obtiene un valor que indica si la regla no se puede modificar con las API de código administrado. |
| [IsReadOnly](../../aspose.email.clients.exchange/inboxrule/isreadonly) { get; set; } | Obtiene o establece un valor que indica si la regla es de solo lectura. |
| [Priority](../../aspose.email.clients.exchange/inboxrule/priority) { get; set; } | Obtiene o establece un valor que indica el orden en que se debe ejecutar una regla. |
| [RuleId](../../aspose.email.clients.exchange/inboxrule/ruleid) { get; set; } | Obtiene o establece el identificador de la regla. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateRuleDeleteContaining](../../aspose.email.clients.exchange/inboxrule/createruledeletecontaining)(string[]) | Crea una regla de bandeja de entrada que elimina los mensajes que contienen las cadenas especificadas en el cuerpo o en el asunto |
| static [CreateRuleDeleteFrom](../../aspose.email.clients.exchange/inboxrule/createruledeletefrom)(MailAddress) | Crea una regla de bandeja de entrada que elimina los mensajes de los remitentes especificados |
| static [CreateRuleMoveContaining](../../aspose.email.clients.exchange/inboxrule/createrulemovecontaining)(string[], string) | Crea una regla de bandeja de entrada que mueve los mensajes que contienen las cadenas especificadas en el cuerpo o en el asunto a la carpeta especificada |
| static [CreateRuleMoveFrom](../../aspose.email.clients.exchange/inboxrule/createrulemovefrom)(MailAddress, string) | Crea una regla de bandeja de entrada que mueve los mensajes de los remitentes especificados a la carpeta especificada |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->