# **Learning Office 365**(Part 7)

The theme is **setting the user up correctly while giving them only the access they actually need.**

For this lab the main tasks include:

- Managing an existing user
- Resetting passwords
- Assigning licenses
- Reviewing admin permissions
- Creating users/templates

## Resetting a User's Password

In the Microsoft 365 admin environment, an administrator can reset a user's password.

Steps:

- Locate the user.
- Select **Reset Password**.
- Generate or enter a temporary password.
- Save the change.
- Provide the temporary password according to the organization's procedure.
- Have the user change it when required.

For production environments, there is the organization's password policy and secure password-handling procedures.

## Review the User Before Giving Access

After resetting the password, there is the user's configuration.

Things to check include:

- Connected devices
- Licenses
- Applications
- Mailbox
- Administrative roles
- Other assigned permissions

The goal is to make sure the user has **appropriate access rather than excessive access**.

## Microsoft 365 Licensing

Licenses determine which Microsoft 365 services the user can access.

For example when a user says:

> "I can't access Outlook."
> 

Check:

1. Does the user have the appropriate license?
2. Is Exchange/mail enabled?
3. Does the account exist and work?
4. Is the user blocked?
5. Can they access Outlook on the web?
6. Is the desktop application configured correctly?

## Exchange Admin Center -  Administrative Access

Reviewing:

- Mailbox type
- Exchange settings
- Administrative roles
- Other Microsoft/Azure-related roles

### Security principle

**Least privilege:** Give a user only the permissions they actually need to perform their job.

## User Templates

The Microsoft 365 environment can use **user templates** to simplify account creation for multiple users on the same group with the concept of uploading a **CSV**

### Useful for

- Large onboarding projects
- Migrations
- Departments with many new accounts
- Initial tenant setup
