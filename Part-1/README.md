# **Learning Office 365(Part 1)**

## **Troubleshooting Outlook Office 365 Using Command Line Switches**

- Goal: When troubleshooting Outlook for a user, command-line switches can be used to isolate or reset specific Outlook components.
- **Don't immediately recreate/reinstall the Outlook profile.** Try targeted troubleshooting switches first

These switches are particularly useful when dealing with:

- Outlook crashes
- Problematic add-ins
- Corrupted rules
- Corrupted/custom view settings
- Broken categories
- Reading-pane/view issues

## Opening Outlook in Safe Mode

- Wnd + R to run the cmd —> `outlook.exe /safe`

<img width="295" height="225" alt="image 4" src="https://github.com/user-attachments/assets/3a417927-018d-4efb-b87d-a39bdddd0d3e" />

This is useful when Outlook is behaving strangely or crashing, particularly when an **add-in** may be responsible.

**File → Options → Add-ins**

- Locate the relevant **COM Add-ins**.
- Disable/uncheck the suspected problematic add-in.
- Restart Outlook normally.

<img width="387" height="376" alt="image 3" src="https://github.com/user-attachments/assets/b600ecb1-16a3-498f-80fe-593a3ad58ac4" />

**Troubleshooting logic:**

```
Outlook problem
      │
      ▼
Start Outlook in Safe Mode
      │
      ▼
Does Outlook behave normally?
      │
      ├── Yes → Investigate/disable add-ins
      │
      └── No → Continue troubleshooting other Outlook components
```

## Clearing Outlook Categories

- Wnd + R to run the cmd—> `outlook.exe /cleancategories`

<img width="342" height="176" alt="image 2" src="https://github.com/user-attachments/assets/c588a46a-b4e9-4cdd-8e17-9e70cd52c207" />

When to use it

Useful when troubleshooting problems involving:

- Categories
- Category colors
- Shared mailbox category issues
- Corrupted category configuration

In the demonstration, an existing category was assigned to an email. After running the command, the category was no longer present.

This is a **reset/cleanup operation**, not a harmless diagnostic command.

<img width="927" height="902" alt="image 1" src="https://github.com/user-attachments/assets/8c5c3e4c-6068-434d-b241-ca063e88e2bb" />

## Outlook Rules

- Outlook rules automate actions on incoming/outgoing messages.

Email from specific sender
↓
Rule
↓
Move email to specific folder

- Rules are useful for automatically organizing messages.

<img width="335" height="177" alt="image 8" src="https://github.com/user-attachments/assets/05ee2f13-a8f0-4c67-a5e5-1890fdf0a3ab" />

## Clearing Client Rules

- Wnd + R to run the cmd—>`outlook.exe /cleanclientrules`

<img width="340" height="180" alt="image 7" src="https://github.com/user-attachments/assets/697b563d-8bd9-4b9d-9dca-10c2b7f94432" />

Removes the **client-side Outlook rules**.

## Outlook Views

- Outlook has customizable **views** controlling how information is displayed.

**View → Change View → Save Current View as a New View**

!image.png

## Clearing Outlook Views

- Wnd + R to run the cmd—> `outlook.exe /cleanviews`

<img width="604" height="700" alt="image 6" src="https://github.com/user-attachments/assets/4b4d9e57-0de4-4dea-881f-958756dbe510" />

Resets/clears Outlook's custom view settings.

Useful when:

- Outlook's views are behaving incorrectly
- A user's view configuration appears corrupted
- Folder/message display settings are behaving unexpectedly

## Starting Outlook Without the Reading Panel

- Wnd + R to run the cmd—> `outlook.exe /nopreview`

<img width="348" height="181" alt="image 5" src="https://github.com/user-attachments/assets/2852bf4b-4967-46c1-a4fa-3abc4a4dad69" />

Starts Outlook with the **Reading Pane disabled**.
A user is experiencing problems potentially associated with the Reading Panel or simply needs Outlook opened without message preview.
