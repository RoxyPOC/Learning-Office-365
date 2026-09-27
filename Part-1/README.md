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

<img width="398" height="194" alt="image" src="https://github.com/user-attachments/assets/a3dd184e-f2e2-4e4a-837c-58b7371fd344" />

This is useful when Outlook is behaving strangely or crashing, particularly when an **add-in** may be responsible.

**File → Options → Add-ins**

- Locate the relevant **COM Add-ins**.
- Disable/uncheck the suspected problematic add-in.
- Restart Outlook normally.

<img width="927" height="902" alt="image 1" src="https://github.com/user-attachments/assets/75abb978-0e27-4d13-a9de-da1bdd823941" />

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

<img width="342" height="176" alt="image 2" src="https://github.com/user-attachments/assets/2a9cc5ed-5b9c-4697-bf1c-88555da6b785" />

When to use it

Useful when troubleshooting problems involving:

- Categories
- Category colors
- Shared mailbox category issues
- Corrupted category configuration

In the demonstration, an existing category was assigned to an email. After running the command, the category was no longer present.

This is a **reset/cleanup operation**, not a harmless diagnostic command.

<img width="387" height="376" alt="image 3" src="https://github.com/user-attachments/assets/327be57b-9b7f-49a2-b065-ed48bee51a23" />

## Outlook Rules

- Outlook rules automate actions on incoming/outgoing messages.

Email from specific sender
↓
Rule
↓
Move email to specific folder

- Rules are useful for automatically organizing messages.

<img width="295" height="225" alt="image 4" src="https://github.com/user-attachments/assets/bc2e9da9-c1d9-46aa-83c7-427cf45723d6" />

## Clearing Client Rules

- Wnd + R to run the cmd—>`outlook.exe /cleanclientrules`

<img width="348" height="181" alt="image 5" src="https://github.com/user-attachments/assets/d70f1a7f-20af-438b-8622-1444479c8a34" />

Removes the **client-side Outlook rules**.

## Outlook Views

- Outlook has customizable **views** controlling how information is displayed.

**View → Change View → Save Current View as a New View**

<img width="604" height="700" alt="image 6" src="https://github.com/user-attachments/assets/38a2cd1d-0528-4c54-b4f9-8188747d2f5f" />

## Clearing Outlook Views

- Wnd + R to run the cmd—> `outlook.exe /cleanviews`

<img width="340" height="180" alt="image 7" src="https://github.com/user-attachments/assets/8c3031f5-6ff9-414e-bb0b-4339d89f9f02" />

Resets/clears Outlook's custom view settings.

Useful when:

- Outlook's views are behaving incorrectly
- A user's view configuration appears corrupted
- Folder/message display settings are behaving unexpectedly

## Starting Outlook Without the Reading Panel

- Wnd + R to run the cmd—> `outlook.exe /nopreview`

<img width="335" height="177" alt="image 8" src="https://github.com/user-attachments/assets/f2f76ae7-c8ce-4a04-86cf-b0d368f9a8b8" />

Starts Outlook with the **Reading Pane disabled**.
A user is experiencing problems potentially associated with the Reading Panel or simply needs Outlook opened without message preview.

CMDs Sheet
Command	                    Purpose
outlook.exe /safe	Start         Outlook in Safe Mode
outlook.exe /cleancategories	  Clear Outlook categories
outlook.exe /cleanclientrules	  Remove client-side Outlook rules
outlook.exe /cleanviews	        Reset/clear custom Outlook views
outlook.exe /nopreview	        Start Outlook with Reading Pane disabled
