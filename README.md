<img src="assets/icon.png" width="128" alt="Jammy Note icon: a hot dog">

# Jammy Note

Jammy Note is a small sticky-note app for macOS, with notes in jam colors that can put the dates you write into your calendar.

**[Download the latest version](https://github.com/Dino-Boooo/jammy-note-releases/releases/latest)** · macOS 13 or later · Apple silicon and Intel

[Install](#install) · [Style a note](#style-a-note) · [Write](#write) · [Smart list](#smart-list) · [Share](#share-a-note) · [Find notes](#find-notes) · [Shortcuts](#shortcuts)

## Install

1. Download **Jammy-Note-x.y.z.zip** from the link above and open it.
2. Drag **Jammy Note** into your **Applications** folder.
3. Open it. macOS will say it can't check the app, so click **Done**, go to **System Settings ▸ Privacy & Security**, scroll down and click **Open Anyway**.

This step is only needed once. After that, Jammy Note shows a red dot on its menu bar icon whenever a new version is out, and clicking **Update Now** installs it while keeping your notes and settings.

## How to use

### Style a note

<img src="assets/demos/note-basics.gif" width="560" alt="Three plain notes: one becomes a tomato, one an orange, and the third turns Blueberry with a linen paper; a web page comes over the fruits but not the pinned note; double-clicking the note folds it up">

The buttons along the top of a note change how it looks. The **shape** button turns it into a tomato or an orange, the **drop** picks its color and paper, and **Aa** picks its font. The **pin** keeps a note above your other windows, and double-clicking a note folds it up when you want it out of the way.

### Write

<img src="assets/demos/note-writing.gif" width="560" alt="Typing a title and making it bold from the format bar; '- ' starts a bulleted list and '[] ' a checklist item, which is checked off; a picture dragged from the Desktop lands in the note">

Press ⌘N for a new note, or ⌃⌥N from any other app. Select some text and a format bar appears for bold, colors, headings and more. Starting a line with `-`, `1.` or `[]` and a space begins a list, numbers or a checklist.

Pictures can be pasted or dropped into a note. Drag a picture's corner to resize it, or click the crop button that appears on it to trim its sides.

### Smart list

When you write a date on a line, Jammy Note can add that line to Calendar or Reminders for you.

<img src="assets/demos/smart-list.gif" width="560" alt="Typing / and picking Calendar for 'call mom fri 6:30pm'; changing it to 7pm moves the event; a reminder checked off in the note and in Reminders; clicking a tag takes the event out and puts it back; Tidy moves the date into the tag; a Smart note tagged Work goes to its own calendar; alerts in Settings and from the bell; deleting a line removes its event">

1. Type **/** on a line and pick **Calendar** or **Reminder**.
2. Write what it is and when, for example `call mom fri 6:30pm`.
3. Move on to another line. The line is now in your calendar, and a tag under it shows the date.

If you change the line later, the event changes with it. Clicking the tag takes the line out of your calendar, and clicking it again puts it back.

<details>
<summary>Ways to write a date</summary>

These are read as follows on Thursday, November 12:

| You write | The tag says |
|---|---|
| `call mom fri 6:30pm` | 11/13 FRI 6:30 PM |
| `dentist tmr 9am` | 11/13 FRI 9 AM |
| `lunch next tue 12pm` | 11/17 TUE 12 PM |
| `send report 11/20` | 11/20 FRI |
| `team meeting tonight 8` | 11/12 THU 8 PM |
| `gym nov 16 7:30` | 11/16 MON 7:30 AM |

A time is read the way it is written, so `7:00` is in the morning and the evening needs `7pm` or `19:00`. A time without a day, such as `3pm`, means the next time that hour comes. Dates written in Chinese are understood as well.

</details>

<details>
<summary>What the tag means</summary>

| The tag looks | It means |
|---|---|
| dashed, `CALENDAR` or `REMINDER` | The line has no date yet |
| dashed, with a date | It will be added when you leave the line |
| solid, with a date | It is in your calendar or Reminders |
| dashed, `+` and a date | It was taken out, and a click puts it back |

</details>

<details>
<summary>Reminders, alerts and Smart notes</summary>

Picking **Reminder** turns the line into a checklist item. You can check it off in the note or in the Reminders app, and the other one follows.

**Calendar: alert me** in Settings decides when events alert you, and the bell beside an event's tag changes this for that one event. Reminders alert you at their own time.

A **Smart note** adds every line that has a date, without typing **/**. Click the bolt on a note to make it one, or choose **File ▸ New Smart Note**.

Deleting a line removes its event too, unless the event has already started.

</details>

<details>
<summary>Calendars, tags and Tidy</summary>

Events go to a calendar named **Jammy Note**. If a note has a tag, such as **Work**, its lines go to **Jammy Note · Work** instead, and their tags take that calendar's color. To use your own calendars, turn off **Jammy Note's own calendars** in Settings and choose them there.

With **Tidy dates out of the text** turned on in Settings, a line's date moves into its tag once the line is in your calendar, so "Reach out Prof at 10AM 11/13" becomes "Reach out Prof". Turning it off writes the dates back.

Jammy Note asks for permission to use Calendar and Reminders the first time. If you said no, you can allow it in **System Settings ▸ Privacy & Security**, under **Calendars** and **Reminders**.

</details>

### Share a note

<img src="assets/demos/share-note.gif" width="560" alt="Clicking the share button, picking Messages, the note arriving as a picture; on the other Mac, dragging the picture to the Desktop turns it into a note">

1. Click a note's share button and pick **Messages**, **Mail** or **AirDrop**.
2. The note arrives as a picture of itself, which anyone can look at.
3. If the other person has Jammy Note open, they can drag the picture onto their Desktop and it becomes a note again.

<details>
<summary>If it stays a picture</summary>

Drop the picture on the Jammy Note icon in the Dock, or on All Notes. If the note inside was lost on the way, Jammy Note reads the words in the picture and makes the note again, though without its formatting.

Pictures of your own notes stay pictures on your Desktop, so that you don't end up with a second copy.

</details>

### Find notes

<img src="assets/demos/find-and-delete.gif" width="560" alt="⌘W puts a note away; All Notes lists it as closed; searching and filtering by the Work tag; clicking the closed note opens it again; deleting a note sends it to Trash, where Restore brings it back">

**All Notes** (⌘F) lists every note, open or closed, and lets you search them or filter them by tag. Closing a note with ⌘W only puts it away, and ⇧⌘T brings back the last one you closed. Deleted notes wait in the Trash for 30 days before they are gone for good.

### Shortcuts

| | |
|---|---|
| New note | ⌘N, or ⌃⌥N from any app |
| All Notes | ⌘F, or ⌃⌥F from any app |
| Hide or show all notes | ⌃⌥H |
| Settings | ⌘, |
| Every shortcut | ⌘/ |

Everything saves by itself. If you have an idea or find a bug, **Send Feedback…** in the menu bar icon's menu reaches the jam maker.
