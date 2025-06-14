---
title: Enum SmtpStatusCode
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Smtp.SmtpStatusCode enum. Smtp status codes
type: docs
weight: 17240
url: /net/aspose.email.clients.smtp/smtpstatuscode/
---
## SmtpStatusCode enumeration

Smtp status codes

```csharp
public enum SmtpStatusCode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NotDefined | `0` | Not defined |
| GeneralFailure | `-1` | General failure |
| SystemStatus | `211` | System status, or system help reply. A SMTP status 211 is a message that gives details about the Mail Server status. In the case of a System Help reply, it is a message to the user requesting help information. |
| HelpMessage | `214` | A help message for a human reader will follow. SMTP 214 is usually provided as a response to the “HELP” command. A user will usually receive this as a displays of information about the mail server and it will most likely be in the form of a link to the FAQ page of THAT particular SMTP software that is running on the mail server. Due to the nature of this error and how the email server responds, it is normally called a reply, as in SMTP Reply 214. |
| ServiceReady | `220` | SMTP Service ready. |
| ServiceClosingTransmissionChannel | `221` | Service closing transmission channel |
| AuthenticationSucceeded | `235` | Authentication Succeeded |
| Ok | `250` | Requested action taken and completed. |
| UserNotLocalWillForward | `251` | The recipient is not local to the server, but the server will accept and forward the message. |
| CannotVerifyUserWillAttemptDelivery | `252` | The recipient cannot be VRFYed, but the server accepts the message and attempts delivery. |
| Base64Response | `334` | Text part containing the [BASE64] encoded string |
| StartMailInput | `354` | Start message input and end with. This indicates that the server is ready to accept the message itself |
| ServiceNotAvailable | `421` | The service is not available and the connection will be closed. |
| PasswordTransitionNeeded | `432` | A password transition is needed |
| MailboxBusy | `450` | The requested command failed because the user’s mailbox was unavailable (such as being full). Try again later. |
| LocalErrorInProcessing | `451` | The command has been aborted due to a server error. (on their side) |
| InsufficientStorage | `452` | The command has been aborted because the server has insufficient system storage. |
| ClientNotPermitted | `454` | Client does not have permission. TLS not available due to temporary reason. Encryption required for requested authentication mechanism. |
| CommandUnrecognized | `500` | The server could not recognize the command due to a syntax error. |
| SyntaxError | `501` | A syntax error was encountered in command arguments. |
| CommandNotImplemented | `502` | This command is not implemented. |
| CommandNotPermitted | `503` | Сommand is not permitted during a mail transaction |
| UnrecognizedAuthenticationType | `504` | Unrecognized authentication type |
| AuthenticationRequired | `530` | The SMTP server requires a secure connection or the client was not authenticated. But sometimes it's about the recipient's server blacklisting yours, or an invalid email address. |
| AuthenticationMechanismIsToWeak | `534` | Authentication mechanism is to weak |
| CredentialsInvalid | `535` | Authentication credentials invalid |
| EncryptionRequiredRequestedMechanism | `538` | Encryption required for requested authentication mechanism |
| MailboxUnavailable | `550` | It usually defines a non-existent email address on the remote side. |
| UserNotLocalTryAlternatePath | `551` | "User not local or invalid address – Relay denied". Meaning, if both your address and the recipient's are not locally hosted by the server, a relay can be interrupted. |
| ExceededStorageAllocation | `552` | "Requested mail actions aborted – Exceeded storage allocation": simply put, the recipient's mailbox has exceeded its limits. |
| MailboxNameNotAllowed | `553` | "Requested action not taken – Mailbox name invalid". That is, there's an incorrect email address into the recipients line. |
| TransactionFailed | `554` | This means that the transaction has failed. It's a permanent error and the server will not try to send the message again. |

### See Also

* namespace [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp/)
* assembly [Aspose.Email](../../)


