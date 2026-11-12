<img src="assets/icon.png" width="128" alt="Jammy Note icon: a hot dog">

# Jammy Note

A small sticky-note app for macOS, with notes in jam colors.

**[Download the latest version](https://github.com/Dino-Boooo/jammy-note-releases/releases/latest)**: get **Jammy-Note-x.y.z.zip** from that page. Requires macOS 13 or later, on Apple silicon or Intel Macs.

## Install

1. Open the zip to unzip **Jammy Note**.
2. Drag **Jammy Note** into **Applications**.
3. The first time you open it, macOS says it can't check the app. Click **Done**, go to **System Settings ▸ Privacy & Security**, scroll down, click **Open Anyway**, and enter your password.
   - On macOS 14 or earlier, you can also right-click the app ▸ **Open**.

## Updates

Jammy Note checks for new versions by itself. When one is out, a red dot shows on its menu bar icon: click **Update Now** and it downloads the update, replaces itself and reopens. Your notes and settings stay, and you won't need Open Anyway again.

## How to use

**Style a note**
- **Shape button**: square, tomato or orange; drag a fruit's lower corners to resize it
- **Drop button**: a jam color and a paper · **Aa**: font
- **Pin**: keeps it above other windows (new notes start pinned) · double-click a note to fold it up

<img src="assets/demos/note-basics.gif" width="560" alt="Three plain notes: one becomes a tomato, one an orange, and the third turns Blueberry with a linen paper; a web page comes over the fruits but not the pinned note; double-clicking the note folds it up">

**Write**
- **New note**: ⌘N, or ⌃⌥N from any app
- **Format**: select text and a format bar pops up (bold, italic, headings, lists, size, colors)
- **Lists**: start a line with `-`, `1.` or `[]` and a space; click a circle to check it off
- **Pictures**: paste or drop them in; drag a picture's corner to resize it

<img src="assets/demos/note-writing.gif" width="560" alt="Typing a title and making it bold from the format bar; '- ' starts a bulleted list and '[] ' a checklist item, which is checked off; a picture dragged from the Desktop lands in the note">

**Smart list**: lines with a date go into Calendar and Reminders

<img src="assets/demos/smart-list.gif" width="560" alt="Typing / and picking Calendar for 'call mom fri 6:30pm'; changing it to 7pm moves the event; a reminder checked off in the note and in Reminders; clicking a tag takes the event out and puts it back; Tidy moves the date into the tag; a Smart note tagged Work goes to its own calendar; alerts in Settings and from the bell; deleting a line removes its event">

*Put a line in your calendar.* Type **/** at the start of a line and pick **Calendar**. An empty tag appears under the line. Write what it is and when; the tag fills in as you type. Press Return (or click anywhere else) and the line is in your calendar.


*A reminder instead.* Pick **Reminder** and the line becomes a checklist item. Check it off in the note or in Reminders: the other one follows. Dates can be written in English or Chinese.


Some ways of writing a date (on Thursday, November 12):

| You write | The tag says |
|---|---|
| `call mom fri 6:30pm` | 11/13 FRI 6:30 PM |
| `dentist tomorrow 9am` | 11/13 FRI 9 AM |
| `send report 11/20` | 11/20 FRI (all day) |
| `明天下午3點 開會` | 11/13 FRI 3 PM |
| `下週一 早上10點 晨會` | 11/16 MON 10 AM |
| `11/14 下午3點` | 11/14 SAT 3 PM |

A time alone (`3pm`, `下午3點`) means the next time that comes. You can also type **/** at the end of a line you've already written, after a space.

*What the tag tells you.*

| The tag looks | It means |
|---|---|
| dashed, `CALENDAR` or `REMINDER` | Marked with /, no date yet |
| dashed, with a date | Not in the calendar yet: it goes in when you leave the line |
| solid, with a date | In your calendar or Reminders. The bell beside an event's tag sets its alerts |
| dashed, `+` and a date | Taken out of the calendar. Click to put it back |

*Take a line out, or put it back.* Click a solid tag and the line leaves your calendar (the line itself stays). Click it again to put it back.


*Keep the calendar in step.* Change a line and its event changes with it. Delete the line and an event that hasn't started yet is deleted too (one that has started stays, as a record).

*Smart note: every line, no / needed.* Click the bolt on a note (or **File ▸ New Smart Note**) and every line with a date in it goes into your calendar. Dates that have already gone by aren't added by themselves: click their `+` tag if you want them.

*Note tags sort the calendar.* A note can have one tag, like **Work** or **Daily** (the tag button in the note's toolbar, next to the bolt). Its lines go to a calendar of their own, **Jammy Note · Work**, and their tags take that calendar's color. Lines in untagged notes go to **Jammy Note**.


Prefer your own calendars? In **Settings**, turn off **Jammy Note's own calendars** and pick where events and checklists go. A note tagged Work then goes to your calendar called Work, if you have one.

*Tidy.* With **Tidy dates out of the text** on (Settings), once a line is in your calendar its date moves into the tag: "Reach out Prof at 10AM 11/13" becomes "Reach out Prof". Turn Tidy off and the dates are written back into the lines.


*Alerts.* **Calendar: alert me** in Settings sets when events alert you (10 minutes before, to start with). The bell beside an event's tag changes it for that one event. Reminders alert you at their own time, or not at all.

The first time, Jammy Note asks for permission to use Calendar and Reminders. If you said no, turn it on in **System Settings ▸ Privacy & Security ▸ Calendars** (and **Reminders**).

**Share a note**

Click a note's share button and pick **Messages**, **Mail** or **AirDrop** (or **Save as Picture…**). The note goes as a picture of itself, with the note tucked inside. Anyone can look at the picture. If they have Jammy Note too (and it's open), they drag the picture onto their Desktop and it becomes a note again, with its colors and formatting; the picture file goes to the Trash. Pictures of your own notes stay pictures on your Desktop, so you don't get a second copy.

<img src="assets/demos/share-note.gif" width="560" alt="Clicking the share button, picking Messages, the note arriving as a picture; on the other Mac, dragging the picture to the Desktop turns it into a note">

Dropping the picture on the Jammy Note icon in the Dock, on All Notes, or on a note works too. If the note inside got lost on the way (Messages sometimes re-saves pictures), drop it on the Dock icon or All Notes: Jammy Note reads the words in the picture and makes the note again, without its formatting.

**Find notes**
- **All Notes** (⌘F): every note, open or closed. Search, filter by tag, and click a note to open it again. **Edit** renames or deletes tags.
- Closing a note (⌘W) only puts it away; ⇧⌘T reopens the last one.
- Deleted notes wait in **Trash** (in All Notes) for 30 days: pick one and click **Restore**.

<img src="assets/demos/find-and-delete.gif" width="560" alt="⌘W puts a note away; All Notes lists it as closed; searching and filtering by the Work tag; clicking the closed note opens it again; deleting a note sends it to Trash, where Restore brings it back">

| Shortcut | |
|---|---|
| New note | ⌘N · ⌃⌥N from any app |
| All Notes | ⌘F · ⌃⌥F from any app |
| Hide / show all notes | ⌃⌥H |
| Settings | ⌘, |
| Every shortcut | ⌘/ |

Everything saves by itself. **Help ▸ Show Welcome Note** walks you through it, and **Send Feedback…** in the menu bar icon's menu reaches the jam maker.
