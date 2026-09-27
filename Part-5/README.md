# **Learning Office 365**(Part 5)

## What Are Role-Based Permissions?

**Role-based permissions** control what administrators and users are allowed to do within Exchange. A **management role** defines a specific set of tasks that someone can perform.
For example, a role could allow an administrator to manage:

- Mailboxes
- Contacts
- Distribution groups
- Mail recipients

### Why use roles?

You generally don't want every IT employee to have unrestricted administrative access.

Administrator
↓
Specific Role
↓
Specific Permissions
↓
Specific Tasks

## Two Types of Exchange Roles

| Role Type | Purpose |
| --- | --- |
| **Administrator Roles** | Manage parts of the Exchange organization |
| **End User Roles** | Allow users to manage aspects of their own mailbox or groups they own |

### Administrator roles

These are assigned to administrators or specialized users and can control things such as:

- Recipients
- Servers
- Databases
- Other Exchange administrative functions

<img width="549" height="394" alt="image" src="https://github.com/user-attachments/assets/5ad2d58b-5784-45e8-a72b-13b9692e3bcb" />

<img width="392" height="522" alt="image 1" src="https://github.com/user-attachments/assets/b04730c4-20f0-42ff-ab21-2be6746c3be1" />

### End-user roles

These allow users to manage certain settings associated with:

- Their own mailbox
- Distribution groups they own

## Role Groups vs Role Assignment Policies

### Role Groups

**Role groups** are used to grant permissions to:

- Administrators
- Specialized users

### Role Assignment Policies

**Role assignment policies** give end users permission to manage aspects of:

- Their own mailbox
- Distribution groups they own

## Least Privilege

### Principle of Least Privilege

Give users **only the permissions they need** to perform their job.

Don't give someone unrestricted administrative access when they only need to perform one or two tasks.

## Microsoft 365 Admin Permissions

In the Microsoft 365 admin center, administrators can have roles that control broader Microsoft 365 capabilities.

Microsoft 365 Admin Center
↓
Users
↓
Active Users
↓
Select User
↓
Roles

## Differences between `Microsoft 365 Admin Roles vs Exchange Roles --`

Microsoft 365 Admin Roles
- Manage Microsoft 365 services
- Groups
- Service requests
- Service health

Exchange Roles
- Mailboxes
- Recipients
- Distribution groups
- Exchange-specific management
