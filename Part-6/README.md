# **Learning Office 365**(Part 6)

## Active Users

The **Active Users** section is one of the most important areas for help-desk/support technicians. Common tickets include:

- Create a new employee account
- Create a vendor account
- Reset a forgotten password
- Block/unblock a user
- Remove a user who left the company
- Assign/remove licenses
- Add/remove applications
- Modify user information
- Manage administrative roles

## Creating Users

### Add a Single User

Typical workflow:

1. Go to **Active Users**
2. Select **Add User**
3. Enter:
    - First name
    - Last name
    - Display name
    - Username
    - Password
4. Configure password options.
5. Assign the appropriate license.
6. Select which applications/services the user can access.
7. Assign an administrative role if required.
8. Enter job/department/contact information.
9. Review and create the account.

<img width="786" height="447" alt="image" src="https://github.com/user-attachments/assets/d2ee9e3f-6f51-4768-8f5d-c24f43b68820" />

# User Templates

User templates allow administrators to create accounts using predefined settings.

Example:

**Employee template**

- Standard license
- Standard applications
- Standard permissions

**Vendor template**

- Different access requirements
- Potentially fewer applications/permissions

This reduces repetitive account-creation work.

<img width="637" height="488" alt="image 1" src="https://github.com/user-attachments/assets/54713295-fe9d-46a1-80af-3dab99ad3982" />

# Adding Multiple Users

Office 365 provides an option to add users in bulk.

This primarily as useful during **migration scenarios**, such as moving hundreds of users/mailboxes into Office 365.

Typical process:

1. Download the provided CSV/sample.
2. Modify user information.
3. Upload the file.
4. Assign licenses/settings.
5. Create the users in bulk.

<img width="400" height="441" alt="image 2" src="https://github.com/user-attachments/assets/40cc0ce0-5931-44c9-acb4-528146c1a0e7" />

# Multi-Factor Authentication

MFA requires an additional authentication factor, such as a phone/app, when the user signs in.

Username + Password
↓
Additional authentication
↓
Phone / Authentication App
↓
Access granted

# Removing Incorrect Admin Access

A real-world example involves accidentally giving a user **Global Administrator** access.

Troubleshooting workflow:

1. Open the user's account.
2. Review assigned roles.
3. Identify the incorrect administrator role.
4. Remove the role.
5. Save the change.
6. Refresh/re-authenticate as necessary.
7. Verify that the user no longer has administrative access.

### Important cloud behavior

Changes may not appear immediately.

You may need to:

- Refresh the browser
- Sign out
- Sign back in
- Wait for the change to propagate

<img width="439" height="314" alt="image 3" src="https://github.com/user-attachments/assets/f4c3b7ea-05ff-4dbf-8cb8-e9e196c88850" />

# Resetting a User Password

A very common help-desk ticket:

> “I forgot my password.”
> 

Basic workflow:

1. Open the user's account.
2. Select **Reset Password**.
3. Generate or create a temporary password.
4. Provide it according to company security policy.
5. User signs in.
6. User changes the temporary password if required.

<img width="435" height="363" alt="image 4" src="https://github.com/user-attachments/assets/c79e581c-8d2a-4b03-ac62-9a8b4a510b87" />

<img width="432" height="37" alt="image 5" src="https://github.com/user-attachments/assets/2ce439fa-0e51-4cf2-ba14-52404b33cac6" />

# Contacts

The **Contacts** section is used for people outside the organization who should be represented in the organization's address book.

Examples:

- Retired employees
- Important external contacts
- Vendors
- External business contacts

### Contact information can include:

- Display name
- Email address
- Company
- Phone
- Mobile
- Title
- Website

There is also an option to: **Hide from organizational address list.** This controls whether the contact appears in organizational address-list searches.

<img width="1175" height="142" alt="image 6" src="https://github.com/user-attachments/assets/f05224bd-aa16-4d8d-9e23-6d3fcb38c716" />

# MailTip for Contacts

Exchange settings can provide a **MailTip**. Example: When a user selects an external recipient, Outlook can display a warning/information message.

Possible use:

> “This recipient is external to the organization. Verify the address before sending confidential information.”
> 

The exact message should follow company policy.
<img width="771" height="150" alt="image 7" src="https://github.com/user-attachments/assets/a6a62e16-b3ba-43ad-bc8a-0f870f5d74e0" />
