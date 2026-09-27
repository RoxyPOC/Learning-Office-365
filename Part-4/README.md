# **Learning Office 365**(Part 4)

## Office 365 - Contacts & Shared Mailboxes Documentation Notes

An **Office 365 contact** is an administrator-created contact that is available to users throughout the organization.

### Key characteristics

- Created and managed by **Office 365 administrators**
- Visible to users through:
    - Outlook
    - Outlook on the Web
    - Mobile devices
- Used to represent people **outside the organization**
- Cannot be customized with arbitrary fields such as birthdays or anniversaries
- Can be added to **distribution groups**

### Common real-world uses

Contacts are useful for people such as:

- IT vendors
- Consultants
- Third-party support companies
- External executives or other external users
- People who need to receive organizational email but don't have an internal Microsoft 365 mailbox

## Types of Contacts

| Type | Purpose |
| --- | --- |
| **Mail Contact** | Represents an external email address |
| **Mail User Contact** | Represents an external person with additional identity information |

<img width="409" height="447" alt="image" src="https://github.com/user-attachments/assets/b69894b2-b357-4f2c-a850-f66966596e24" />

When creating a mail contact, you can provide information such as:

- First name
- Last name
- Display name
- Alias / unique identifier
- External email address

### Additional contact settings

After creating the contact, administrators can configure information such as:

- Hide from GAL
- Contact information
- Department
- Job title
- Company
- MailTip

## What Is a Shared Mailbox?

A **shared mailbox** is a mailbox that multiple users can access. Unlike a normal user mailbox, the shared mailbox does **not** have its own username/password that users directly log into. Users access the shared mailbox using permissions assigned to their own accounts.

<img width="635" height="526" alt="image 1" src="https://github.com/user-attachments/assets/922fc9b1-95d7-463e-aeaf-f6a792faeb78" />

## Shared Mailbox Permissions

Before users can access a shared mailbox, administrators need to grant the appropriate permissions.

### Full Access

Allows a user to access the contents of the shared mailbox.

### Send As / Send on Behalf

Allows the user to send messages associated with the shared mailbox.

The exact behavior depends on the permission configured.

## Shared Mailbox Licensing

A shared mailbox can hold **up to 50 GB** without assigning a license. Once the mailbox exceeds that amount, a license is required.

## Shared Mailbox vs Distribution Group

| Distribution Group | Shared Mailbox |
| --- | --- |
| Distributes email to members | Provides a shared mailbox |
| Messages generally arrive in users' regular inboxes | Users access the shared mailbox |
| Good for broadcasting/distribution | Good for team-based mailbox workflows |
| Members receive the message individually | Team works from the shared mailbox |

## Shared Mailbox Replication

One important help-desk issue is **replication delay**. After adding a user to a shared mailbox, the mailbox may **not immediately appear** in Outlook.

### Troubleshooting workflow

If a user was just added:

1. Verify the user was actually added.
2. Give Microsoft 365/Exchange time to replicate the change.
3. Restart or refresh Outlook if necessary.
4. Check whether the mailbox appears.
5. If it doesn't appear automatically, manually add the shared mailbox.

## Manually Adding a Shared Mailbox in Outlook

If Outlook doesn't automatically display the mailbox, it may be possible to manually add it through the account's advanced settings.

## Testing a Shared Mailbox

After creating the shared mailbox and adding yourself:

1. Open Outlook.
2. Locate the shared mailbox.
3. Send a test email to the shared mailbox.
4. Confirm the message appears.
5. Test sending from/on behalf of the shared mailbox.

<img width="422" height="388" alt="image 2" src="https://github.com/user-attachments/assets/a1ea89b1-450e-4cd1-941e-5096e4b26890" />

## Shared Mailbox Synchronization Problems

### Possible symptoms

- One user receives an email while another doesn't immediately see it.
- The shared mailbox isn't appearing.
- Outlook isn't synchronizing correctly.
- The mailbox disappears/reappears.
- Users need to remove and re-add the mailbox.

### Troubleshooting actions mentioned

- Verify permissions.
- Allow time for replication.
- Remove and re-add the shared mailbox.
- Manually add the mailbox.
- Check Outlook settings.
- Investigate synchronization issues.

## Categories in Shared Mailboxes

For example
| Category | Meaning |
| --- | --- |
| Green | Completed |
| Papers | Paper-related task |
| Newspapers | Paper-related task |
| Publishing | Publishing-related task |
