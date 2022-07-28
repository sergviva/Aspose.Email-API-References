---
title: ExchangeMailboxAuditGroupActivity
second_title: Aspose.Email per riferimento all'API .NET
description: 
type: docs
weight: 2530
url: /it/net/aspose.email.clients.activity/exchangemailboxauditgroupactivity/
---
## ExchangeMailboxAuditGroupActivity class

```csharp
public class ExchangeMailboxAuditGroupActivity : Content
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExchangeMailboxAuditGroupActivity](exchangemailboxauditgroupactivity)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AffectedItems](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/affecteditems) { get; set; } | Informazioni su ogni elemento nel gruppo. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'indirizzo IP del dispositivo utilizzato quando l'attività è stata registrata. L'indirizzo IP viene visualizzato in un formato di indirizzo IPv4 o IPv6. Obbligatorio: Sì |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La data e l'ora in UTC (Coordinated Universal Time) in cui l'utente ha eseguito l'attività. Obbligatorio: Sì |
| [CrossMailboxOperations](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/crossmailboxoperations) { get; set; } | Indica se l'operazione ha coinvolto più di una casella di posta. |
| [DestFolder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destfolder) { get; set; } | La cartella di destinazione, per operazioni come Sposta. |
| [DestMailboxId](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxid) { get; set; } | Impostato solo se il parametro CrossMailboxOperations è True. Specifica il GUID della cassetta postale di destinazione. |
| [DestMailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownermasteraccountsid) { get; set; } | Impostato solo se il parametro CrossMailboxOperations è True. Specifica il SID per l'account master SID del proprietario della cassetta postale di destinazione. |
| [DestMailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownersid) { get; set; } | Impostato solo se il parametro CrossMailboxOperations è True. Specifica il SID della cassetta postale di destinazione. |
| [DestMailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownerupn) { get; set; } | Impostato solo se il parametro CrossMailboxOperations è True. Specifica l'UPN del proprietario della cassetta postale di destinazione. |
| [Folder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folder) { get; set; } | La cartella in cui si trova un gruppo di elementi. |
| [Folders](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folders) { get; set; } | Informazioni sulle cartelle di origine coinvolte in un'operazione; ad esempio, se le cartelle vengono selezionate e quindi eliminate. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identificatore univoco di un record di audit. Obbligatorio: Sì |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Per le attività di SharePoint e OneDrive for Business, il percorso completo del file o della cartella a cui l'utente ha eseguito l'accesso. Per la registrazione di controllo dell'amministratore di Exchange, il nome dell'oggetto che è stato modificato dal cmdlet. Obbligatorio: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Il nome dell'utente o dell'attività dell'amministratore. Per una descrizione delle operazioni/attività più comuni, vedere Cerca nel registro di controllo in Office 365 Protection Center. Per l'attività di amministrazione di Exchange, questa proprietà identifica il nome del cmdlet eseguito. Per gli eventi Dlp, può essere "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", descritti in "Schema DLP" di seguito. Obbligatorio: Sì |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Il GUID per il tenant di Office 365 dell'organizzazione. Questo valore sarà sempre lo stesso per l'organizzazione, indipendentemente dal servizio di Office 365 in cui si trova. Obbligatorio: Sì |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Il tipo di operazione indicato dal record. Obbligatorio: Sì |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indica se l'azione (specificata nella proprietà Operazione) è riuscita o meno. I valori possibili sono Succeeded, PartiallySucceded o Failed. Per l'attività di amministrazione di Exchange, il valore è True o False. Obbligatorio: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Questo evento è stato creato da un servizio O365 ospitato o da un server locale? I valori possibili sono online e onprem. Tieni presente che SharePoint è l'unico carico di lavoro che attualmente invia eventi da locale a O365. Obbligatorio: No |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | L'UPN (User Principal Name) dell'utente che ha eseguito l'azione (specificata nella proprietà Operation) che ha portato alla registrazione del record; ad esempio, mio_nome@mio_nome_dominio. Si noti che sono inclusi anche i record per le attività eseguite dagli account di sistema (come SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obbligatorio: Sì |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternativo per l'utente identificato nella proprietà UserId. Ad esempio, questa proprietà viene popolata con l'ID univoco (PUID) del passaporto per gli eventi eseguiti dagli utenti in SharePoint, OneDrive for Business ed Exchange. Questa proprietà può anche specificare lo stesso valore della proprietà UserID per eventi che si verificano in altri servizi ed eventi eseguiti da account di sistema. Obbligatorio: Sì |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Il tipo di utente che ha eseguito l'operazione. Obbligatorio: Sì |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Il servizio di Office 365 in cui si è verificata l'attività nella stringa del carico di lavoro. I valori possibili per questa proprietà sono: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obbligatorio: No |

### Guarda anche

* class [Content](../content)
* spazio dei nomi [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->