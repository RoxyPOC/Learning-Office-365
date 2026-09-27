# **Learning Office 365**(Part 3)

## Types of Groups

| Group Type | Main Purpose |
| --- | --- |
| **Distribution Group** | Distribute email to multiple members |
| **Security Group** | Assign permissions to resources |
| **Mail-Enabled Security Group** | Email distribution + resource permissions |
| **Dynamic Distribution Group** | Dynamically determine members |
| **Microsoft 365 Group** | Collaboration across Microsoft 365 services |

A Microsoft 365 group is presented as a collaboration mechanism across Microsoft 365 tools. Adding members to the group can automatically provide the permissions needed for the associated resources.

Examples of collaboration include:

- Working on documents
- Creating spreadsheets
- Project planning
- Scheduling meetings
- Sending email

## Groups in Outlook

- **if your team prefers to collaborate via email and prefers shared calendar**: create Microsoft 365 Group in Outlook
- **if your team wants to collaborate in a chat environment or embedded apps:** create a Microsoft Team
- **if your team wants to create a big forum for discussion:** create a group in Yammer

## Security Groups

A **security group** is primarily used to assign permissions to resources.

## Distribution Group

A **distribution group** is primarily used to send an email to multiple people through a single group address.

Imagine a company has 100 employees in HR. Instead of manually selecting every employee whenever HR needs to send an announcement. An IT administrator may be asked to add or remove people from the group.

## Distribution Group vs Security Group

| Feature | Distribution Group | Security Group |
| --- | --- | --- |
| Main purpose | Email distribution | Permissions |
| Sends email | ✅ | Not the primary purpose |
| Assigns resource permissions | ❌ | ✅ |
| Has members | ✅ | ✅ |
| Example | `HR@company.com` | `HR-FileShare-Access` |

<img width="673" height="456" alt="image" src="https://github.com/user-attachments/assets/4acbec92-63bd-4010-8186-78f3c224caf7" />

<img width="747" height="416" alt="image 1" src="https://github.com/user-attachments/assets/bd437adb-cbae-4504-8a3b-709d18f9233d" />

<img width="457" height="406" alt="image 2" src="https://github.com/user-attachments/assets/2ab6e4f1-3eee-47b3-a96b-e52ab2f912f5" />

<img width="338" height="287" alt="image 3" src="https://github.com/user-attachments/assets/8df9bd49-bb3c-441f-8f02-7c73c1ceb15e" />

## Group Ownership

The **owner** of a distribution group is important for help-desk work.

When someone asks:

> "Can you add this employee to the distribution group?"
> 

you may need to determine **who owns the group** and whether approval is required.

Help-desk workflow

User requests group membership
↓
Find group
↓
Check owner
↓
Determine approval requirements
↓
Add user if authorized

## Membership Approval

Distribution groups can have different membership settings. 

### Open

Users can join without approval.

### Closed

Members can only be added by group owners.

### Owner Approval

Requests require approval from the group owner.

## Delivery Management

One of the most important troubleshooting sections is **Delivery Management**.

A group can be configured to accept email from:

- Internal senders only
- Internal and external senders
- Specific allowed senders

## External Email and Bounce-Backs

### Scenario

A user tries to send:

```
Gmail → Company Distribution Group
```

But the distribution group only allows internal senders.

The sender receives a **bounce-back/NDR** indicating that the message wasn't accepted because the sender isn't permitted.

## Allowing External Senders

If the organization wants outside users to email the group, the administrator needs to configure the group's delivery settings to allow external senders.

<img width="432" height="427" alt="image 4" src="https://github.com/user-attachments/assets/573399d6-7ac3-4165-8975-8ade0920114a" />

<img width="632" height="321" alt="image 5" src="https://github.com/user-attachments/assets/7a4124fe-e13f-48e1-af8b-8f6f6ecc68fc" />

## MailTip

A **MailTip** can display information when someone is composing a message to the group.
