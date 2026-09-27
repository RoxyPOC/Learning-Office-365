# **Learning Office 365(Part 2)**

## Office 365 Exchange Admin Center — Mailboxes

The main areas covered are:

- Mailbox properties
- SMTP / POP3 / IMAP / MAPI
- Mailbox usage
- Contact and organization information
- Email addresses / aliases
- Mailbox features
- Mobile devices
- Email connectivity
- Litigation hold
- Archiving
- Mail flow
- Message restrictions
- Mailbox delegation
- Opening another user's mailbox
- Cached Exchange Mode
- Sending on behalf of another user

## Email Protocols

**SMTP = Simple Mail Transfer Protocol** is used to **send and relay email** between mail servers/senders and recipients.

**SIP = Session Initiation Protocol aka TCP/IP** is used to set up and control communication. It is like a contact number that follows you everywhere. Usually in instant messages, phone and video calls 

| Protocol | Port |
| --- | --- |
| SMTP | `25` |
| SMTP submission | `587` |
| SMTP alternate | `2525` |
| SMTP over SSL | `465` |

* the common SMTP ports, especially **25, 587, and 465**.

**POP = Post Office Protocol 3** is primarily used to **retrieve/download email** from a mail server to a local client. Port 110 non encrypted / Port 995 secure 

| Connection | Port |
| --- | --- |
| POP3 | `110` |
| POP3 secure | `995` |

**IMAP = Internet Message Access Protocol** allows a client to access email **while keeping the messages on the server**.

| Connection | Port |
| --- | --- |
| IMAP | `143` |
| IMAP secure | `993` |

<img width="888" height="568" alt="image" src="https://github.com/user-attachments/assets/659ecfad-51bd-48ec-b919-bddf5d9d05f5" />

<img width="553" height="621" alt="image 1" src="https://github.com/user-attachments/assets/24f9024a-c20c-4acf-b590-7762d3e6afca" />

## MAPI

**MAPI = Messaging Application Programming Interface** provides access to mailbox functionality through applications such as **Microsoft Outlook**.

Disabling MAPI can prevent the **Outlook desktop application** from working with the mailbox.

So if a user says:

> "Outlook won't connect to my mailbox."
> 

Check whether the relevant mailbox connectivity protocol has been disabled.

## Troubleshoot Cheat Sheet for Exchange

| User Problem | Check |
| --- | --- |
| Outlook desktop **can't access** mailbox | **MAPI** / connectivity |
| **Mobile** Outlook doesn't **sync** | Exchange **ActiveSync** / mobile settings |
| Outlook **Web doesn't work** | **OWA** connectivity |
| User **can't send large** attachment | Message **size restriction** |
| User **can't email another person** | Message **delivery restrictions** |
| User **can't add another recipient** | **Recipient limit** |
| Need email **delivered to another** employee | **Mail forwarding** |
| Need to **preserve deleted** mailbox data | **Litigation Hold** |
| Need **older email retained** elsewhere | **Archiving / retention** |
| Need to manage **another user's** mailbox | **Full Access** |
| Need to **send as another mailbox** | **Send As** |
| Need to send on someone's behalf | Send on Behalf |
| Outlook **local mailbox is huge** | **Cached Exchange Mode** |
| Need **to configure  out-of-office  OOO for another user** | **Full Access + open mailbox** |

## Resources

A **resource mailbox** represents something that users can reserve through the organization’s email/calendar system.

| Resource Type | Represents | Examples |
| --- | --- | --- |
| **Room Mailbox** | A physical location | Conference room, auditorium, training room, floor |
| **Equipment Mailbox** | A reservable piece of equipment | Laptop, projector, microphone, company car |

An **Equipment Mailbox** is similar to a room mailbox, except it represents **equipment rather than a physical location**.
