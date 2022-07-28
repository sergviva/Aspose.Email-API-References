---
title: ExchangeMailboxAuditGroupActivity
second_title: Referencia de la API de Aspose.Email para .NET
description: 
type: docs
weight: 2530
url: /es/net/aspose.email.clients.activity/exchangemailboxauditgroupactivity/
---
## ExchangeMailboxAuditGroupActivity class

```csharp
public class ExchangeMailboxAuditGroupActivity : Content
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExchangeMailboxAuditGroupActivity](exchangemailboxauditgroupactivity)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AffectedItems](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/affecteditems) { get; set; } | Información sobre cada elemento del grupo. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | La dirección IP del dispositivo que se usó cuando se registró la actividad. La dirección IP se muestra en formato de dirección IPv4 o IPv6. Obligatorio: Sí |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La fecha y hora en Tiempo Universal Coordinado (UTC) cuando el usuario realizó la actividad. Obligatorio: Sí |
| [CrossMailboxOperations](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/crossmailboxoperations) { get; set; } | Indica si la operación involucró a más de un buzón. |
| [DestFolder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destfolder) { get; set; } | La carpeta de destino, para operaciones como Move. |
| [DestMailboxId](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxid) { get; set; } | Se establece solo si el parámetro CrossMailboxOperations es True. Especifica el GUID del buzón de destino. |
| [DestMailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownermasteraccountsid) { get; set; } | Se establece solo si el parámetro CrossMailboxOperations es True. Especifica el SID para el SID de la cuenta maestra del propietario del buzón de correo de destino. |
| [DestMailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownersid) { get; set; } | Se establece solo si el parámetro CrossMailboxOperations es True. Especifica el SID del buzón de destino. |
| [DestMailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownerupn) { get; set; } | Se establece solo si el parámetro CrossMailboxOperations es True. Especifica el UPN del propietario del buzón de destino. |
| [Folder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folder) { get; set; } | La carpeta donde se encuentra un grupo de elementos. |
| [Folders](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folders) { get; set; } | Información sobre las carpetas de origen involucradas en una operación; por ejemplo, si se seleccionan carpetas y luego se eliminan. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identificador único de un registro de auditoría. Obligatorio: Sí |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Para la actividad de SharePoint y OneDrive para empresas, el nombre completo de la ruta de acceso del archivo o carpeta al que accede el usuario. Para el registro de auditoría de administración de Exchange, el nombre del objeto que modificó el cmdlet. Obligatorio: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | El nombre del usuario o actividad de administrador. Para obtener una descripción de las operaciones/actividades más comunes, consulte Buscar en el registro de auditoría en el Centro de protección de Office 365. Para la actividad de administración de Exchange, esta propiedad identifica el nombre del cmdlet que se ejecutó. Para eventos DLP, puede ser "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", que se describen en "Esquema DLP" a continuación. Obligatorio: Sí |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | El GUID del inquilino de Office 365 de su organización. Este valor siempre será el mismo para su organización, independientemente del servicio de Office 365 en el que se produzca. Obligatorio: Sí |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | El tipo de operación que indica el registro. Obligatorio: Sí |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indica si la acción (especificada en la propiedad Operación) fue exitosa o no. Los valores posibles son Correcto, Parcialmente exitoso o Error. Para la actividad de administración de Exchange, el valor es Verdadero o Falso. Obligatorio: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | ¿Este evento fue creado por un servicio O365 alojado o un servidor local? Los valores posibles son online y onprem. Tenga en cuenta que SharePoint es la única carga de trabajo que actualmente envía eventos desde las instalaciones a O365. Obligatorio: No |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | El UPN (Nombre principal de usuario) del usuario que realizó la acción (especificada en la propiedad Operación) que resultó en el registro del registro; por ejemplo, my_name@my_domain_name. Tenga en cuenta que también se incluyen los registros de la actividad realizada por las cuentas del sistema (como SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obligatorio: Sí |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternativo para el usuario identificado en la propiedad UserId. Por ejemplo, esta propiedad se completa con el identificador único de pasaporte (PUID) para eventos realizados por usuarios en SharePoint, OneDrive para la Empresa y Exchange. Esta propiedad también puede especificar el mismo valor que la propiedad UserID para eventos que ocurren en otros servicios y eventos realizados por cuentas del sistema. Obligatorio: Sí |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | El tipo de usuario que realizó la operación. Obligatorio: Sí |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | El servicio de Office 365 donde se produjo la actividad en la cadena de carga de trabajo. Los valores posibles para esta propiedad son: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorio: No |

### Ver también

* class [Content](../content)
* espacio de nombres [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->