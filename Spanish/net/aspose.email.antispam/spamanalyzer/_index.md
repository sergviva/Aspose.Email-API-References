---
title: SpamAnalyzer
second_title: Referencia de la API de Aspose.Email para .NET
description: Clase que permite a las aplicaciones detectar correos electrónicos no deseados con filtro bayesiano de autoaprendizaje.
type: docs
weight: 250
url: /es/net/aspose.email.antispam/spamanalyzer/
---
## SpamAnalyzer class

Clase que permite a las aplicaciones detectar correos electrónicos no deseados con filtro bayesiano de autoaprendizaje.

```csharp
public class SpamAnalyzer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SpamAnalyzer](spamanalyzer#constructor)() | Inicializa una nueva instancia del[`SpamAnalyzer`](../spamanalyzer) clase. |
| [SpamAnalyzer](spamanalyzer#constructor_1)(Stream) | Inicializa una nueva instancia del[`SpamAnalyzer`](../spamanalyzer) clase. |
| [SpamAnalyzer](spamanalyzer#constructor_2)(string) | Inicializa una nueva instancia del[`SpamAnalyzer`](../spamanalyzer) clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [LoadDatabase](../../aspose.email.antispam/spamanalyzer/loaddatabase#loaddatabase)(Stream) | Carga la base de datos bayesiana desde stream. |
| [LoadDatabase](../../aspose.email.antispam/spamanalyzer/loaddatabase#loaddatabase_1)(string) | Carga la base de datos bayesiana desde el archivo. |
| [Reset](../../aspose.email.antispam/spamanalyzer/reset)() | Borra todas las estadísticas (base de datos bayesiana). |
| [SaveDatabase](../../aspose.email.antispam/spamanalyzer/savedatabase#savedatabase)(Stream) | Guarda la base de datos bayesiana en flujo. |
| [SaveDatabase](../../aspose.email.antispam/spamanalyzer/savedatabase#savedatabase_1)(string) | Guarda la base de datos bayesiana en el archivo. |
| [Test](../../aspose.email.antispam/spamanalyzer/test)(MailMessage) | Analiza el mensaje y devuelve la probabilidad de que el mensaje sea spam. |
| [TrainFilter](../../aspose.email.antispam/spamanalyzer/trainfilter#trainfilter)(MailMessage, bool) | Aprende del mensaje especificado a partir de una fuente de spam o no spam. |
| [TrainFilter](../../aspose.email.antispam/spamanalyzer/trainfilter#trainfilter_1)(MailMessage[], MailMessage[]) | Aprende de los mensajes especificados como spam o fuente no spam. |
| [TrainFilter](../../aspose.email.antispam/spamanalyzer/trainfilter#trainfilter_2)(string, bool) | Aprende de la cadena especificada a partir de una fuente de spam o no spam. |

### Ver también

* espacio de nombres [Aspose.Email.AntiSpam](../../aspose.email.antispam)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->