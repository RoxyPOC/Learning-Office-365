# **Learning Office 365**(Part 8)

## Outlook Troubleshooting - Documentation Notes

The major issues covered are:

- Outlook add-in problems
- Outlook Safe Mode
- Corrupted Outlook profiles
- Slow Outlook performance
- Mailbox/retention issues
- Outlook search/index problems
- Send/receive failures
- Outlook crashes
- Repeated password prompts
- Attachment problems
- Corrupt PST files
- Calendar synchronization problems

## Outlook Add-ins

An **Outlook add-in** provides additional functionality to Outlook.

**As an example we see Zoom**.

Add-ins can sometimes become corrupted and cause Outlook to:

- Crash
- Start incorrectly
- Behave unexpectedly
- Have problems sending/receiving mail
- Fail during normal use

**Outlook —>File—>Options—>Add-ins —>COM Add-ins**

<img width="281" height="104" alt="image" src="https://github.com/user-attachments/assets/d52fc1e4-c8d5-437d-9105-7ca78749b8fc" />

<img width="106" height="132" alt="image 1" src="https://github.com/user-attachments/assets/aa975567-5725-4daa-bcf2-45528265b659" />
<img width="416" height="459" alt="image 2" src="https://github.com/user-attachments/assets/0dcff786-6241-4c86-8bb7-fb72d9e05e6c" />

## Outlook Safe Mode

One of the first troubleshooting techniques is starting Outlook in **Safe Mode**.

The purpose is to start Outlook without loading the normal add-ins.

### Why use Safe Mode?

If Outlook works correctly in Safe Mode, an add-in or customization becomes a possible cause of the problem.

**Run —> outlook.exe /safe —> Outlook starts with add-ins disabled —> Test Outlook**

## Re-enable a Disabled Add-in

Sometimes Outlook may automatically disable an add-in after a crash. We need to check the COM Add-ins section and re-enabling the affected add-in.

**File —> Options  —>Add-ins —>COM Add-ins —>Select add-in —>Enable —>OK —>Restart/test Outlook**

## Repair or Reinstall an Add-in

If enabling the add-in doesn't resolve the issue, then it is suggested repairing or reinstalling the affected application/add-in.

Example: 

**Control Panel —>Programs / Uninstall a program —>Find application —>Repair**

If repair doesn't help:

**Uninstall  —>Reinstall —>Restart/test Outlook**

## Creating a New Outlook Profile

Another troubleshooting method is creating a **new Outlook profile**.

**Control Panel —>Mail —>Show Profiles —>Add —>Create new profile —>Configure account  —> Set new profile as default —>Open Outlook**

The new profile forces Outlook to retrieve the mailbox configuration again.

<img width="876" height="535" alt="image 3" src="https://github.com/user-attachments/assets/8356aecc-53b3-410d-ace6-0a084ffb20a3" />

<img width="297" height="193" alt="image 4" src="https://github.com/user-attachments/assets/c89817a7-4324-47f8-a7c5-eaac153e482e" />

<img width="262" height="307" alt="image 5" src="https://github.com/user-attachments/assets/845d98d1-9bec-4b08-aafe-8f1a4e00c6d0" />

<img width="473" height="360" alt="image 6" src="https://github.com/user-attachments/assets/384fdfa4-f44b-486c-8f48-758113117494" />

<img width="289" height="336" alt="image 7" src="https://github.com/user-attachments/assets/c7822342-3ec6-425c-b19d-f8a56335428f" />

## Important Warning: New Profiles

Creating a new profile isn't always the first thing to do. It is suggested that after creating a new profile, Outlook **may need to download the user's mailbox data again**. For a user with a very large mailbox, this could take significant time.

**Large mailbox  —>New Outlook profile —>Mailbox synchronization —>Potentially long download**

## Workaround: Outlook on the Web

If Outlook desktop is rebuilding/synchronizing a profile, the user may be able to continue working through **Outlook on the web**.

**Outlook Desktop —>Profile being rebuilt —>Mailbox still synchronizing —>Use Outlook on the Web**

This allows the user to continue accessing email while the desktop client catches up.

## Outlook Slow Performance

Also there are several possible causes of slow Outlook performance:

- Large mailbox
- Too many add-ins
- Outdated software
- Large amounts of email

Possible approaches mentioned include:

- Archive emails
- Disable unnecessary add-ins
- Address mailbox size/retention
- Update/repair software

## Retention Policies

There is retention policies as a way organizations manage how long emails are retained.

Examples shown include policies involving:

- One week
- One month
- Six months
- One year
- Five years
- Never delete

The exact retention period is determined by the organization's policy

### Important distinction

A retention policy is an **organizational policy**, not simply a troubleshooting setting that a help-desk technician should change whenever Outlook is slow.

## Exchange Admin Center - Mailbox Policies

Administrators can manage mailbox-related policies through Exchange administration.

**Exchange Admin —>Recipients —>Mailboxes —>Select mailbox —>Mailbox settings/policies**

<img width="1064" height="450" alt="image 8" src="https://github.com/user-attachments/assets/381ab320-8b4d-4fad-a8b9-233d24e8b8e3" />

<img width="337" height="519" alt="image 9" src="https://github.com/user-attachments/assets/7e290e4f-4323-4161-a727-c70c6d926a10" />

## Outlook Search Not Working

It may be connected to the Windows search/indexing system.

**Control Panel  —>Indexing Options —>Advanced —>Rebuild**

<img width="770" height="407" alt="image 10" src="https://github.com/user-attachments/assets/f4837811-4634-4410-bbd5-6c1938d0ad04" />

## Restart Windows Search

Another troubleshooting option discussed is restarting the **Windows Search** service.

**Services —>Windows Search —>Stop —>Start —>Test search**

<img width="562" height="407" alt="image 11" src="https://github.com/user-attachments/assets/0803c711-c99b-419c-a237-9a0d6d0c2270" />

<img width="289" height="336" alt="image 12" src="https://github.com/user-attachments/assets/91e6e054-45e9-460c-b5c9-676c6eee3b53" />

## Outlook Can't Send or Receive Email

There are several possible causes.

- Firewall restrictions
- Network problems
- Internet connectivity
- Full inbox
- Outlook connectivity problems
- Outlook being set to **Work Offline**

First to check 

- Internet connection
- Outlook connection
- Work Offline status
- Mailbox capacity
- Firewall/network restrictions

## Work Offline

A surprisingly simple cause of email problems is accidentally enabling **Work Offline**.

If Outlook is offline, sending/receiving can fail.

**Outlook —>Work Offline —>If enabled → disable it —>Test send/receive**

## Outlook Crashes

Possible causes mentioned:

- Bad/corrupted add-in
- Corrupt Outlook profile
- Software problems
- Office installation problems

**Outlook crashes —>Safe Mode —>Check add-ins —>Check profile —>Repair Office —>
Reinstall if necessary**

## Repair Microsoft 365 / Office

**Control Panel  —>Programs / Uninstall a program —>Microsoft 365 / Office —>Change —>
Repair**

## Repeated Password Prompts

If Outlook repeatedly asks for a password, several possibilities are mentioned:

- Corrupt Outlook profile
- Server-side issue
- Cached credentials
- Locked Active Directory account
- Expired password

Credential Manager —> checking Windows **Credential Manager** for old stored credentials.

<img width="844" height="519" alt="image 13" src="https://github.com/user-attachments/assets/893a128d-cc79-451c-8f2b-a640bfde6500" />

## Account Lockout / Expired Password

Repeated password prompts can also happen when the underlying account has an issue.

Possible causes mentioned:

- Active Directory account locked
- Password expired
- Incorrect credentials
- Profile problems

For an AD environment, the help desk may need to check/unlock the user's account according to organizational procedures.

## Attachments Won't Open

Possible causes mentioned:

- Attachment blocked by security controls
- Incorrect application association
- File type issue
- Outlook/security restrictions

**Example**: A user expects a PDF to open in a PDF reader, but Windows opens it with another application. This may be a **file association** problem rather than an Outlook problem.

### Troubleshooting questions

Ask:

1. Does the attachment download?
2. Is the attachment blocked?
3. What file type is it?
4. What application is Windows using to open it?
5. Can another application open the file?

## Corrupt PST Files

PST files can become corrupted and may require repair.

**PST problem —>Identify affected PST —>Run appropriate repair procedure —>Test Outlook**

## Calendar Synchronization Problems

A final issue is a calendar that isn't synchronizing correctly.

**Remove calendar —>Add calendar again —>Browse/select mailbox/calendar —>Test synchronization**

## Troubleshooting sum-up

| Problem | First checks |
| --- | --- |
| Outlook crashes | Safe Mode → add-ins → profile |
| Add-in broken | COM Add-ins → enable/disable → repair/reinstall |
| Outlook slow | Mailbox size → add-ins → software |
| Search broken | Rebuild index → Windows Search |
| Can't send email | Internet → Work Offline → mailbox/network |
| Repeated password prompt | Credentials → account lockout → password expiry → profile |
| Attachment won't open | Security block → file association → file type |
| PST corruption | Repair PST / follow organizational recovery process |
| Calendar won't sync | Remove calendar → add it again |
| Profile corrupted | Create new Outlook profile |
| Office application broken | Office Repair |
| Large mailbox | Retention/archive policies according to organization |
