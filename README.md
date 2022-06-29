# QuickNote
### A way to take Quick Notes in [Obsidian](https://obsidian.md/) on Android

This task displays an input dialog to take a note in the app Obsidian.

---
[Link to project in TaskerNet](https://taskernet.com/shares/?user=AS35m8nSFNRSqPmtuWoUzDvbOkD1v%2FlqgfcQ2ZMUW6BRdBoRrpot%2BuokAci2FnhAYxkZxeZC&id=Project%3AObsidian+QuickNote)

#### Features
- Open a Quick Note dialog from a home screen widget, quick tile or notification
- Special characters - configurable characters that do a certain thing.
	- Save note
		- Saves the note. Must be written at the end of a note.
	- Save and exit note
		- Saves the note and closes the input dialog. Must be written at the end of a note.
	- Clear note
		- Clears all the text in the input dialog. Must be written at the end of the note. 
	- Escape
		- Tells the task to ignore a custom character.

#### Instructions to import and use the project
- Install Obsidian
- Install Tasker
- Open this [TaskerNet](https://taskernet.com/shares/?user=AS35m8nSFNRSqPmtuWoUzDvbOkD1v%2FlqgfcQ2ZMUW6BRdBoRrpot%2BuokAci2FnhAYxkZxeZC&id=Project%3AObsidian+QuickNote) link on your phone
- Tap on "Import"
- View the description if you want to
- When the "Import Data" prompt appears, tap "Yes"
- When the "Do you want to enable all the profiles right away?" prompt appears, tap "No"
- When the "This project has a launch task, run?" prompt appears, tap "Yes"
- Follow the instructions.

#### Permissions
- Manage external storage - To write and read notes in the device
- Accessibly service - To detect tapped notification with Tasker notification (this is optional)
- App usage stats - To detect AutoNotification is installed. (this is optional)
- Calendar - To detect AutoNotification is installed. (this is optional)

#### Apps
##### Required
- [Obsidian](https://obsidian.md/) - A notes app that is a powerful knowledge base on top of a local folder of plain text Markdown files.
	- [Play Store link](https://play.google.com/store/apps/details?id=md.obsidian)
- [Tasker](https://tasker.joaoapps.com/) -  Tasker is an Android application that performs tasks, based on contexts like application, event, gesture, date, time, location in user defined profiles or home screen widgets. A 7 day free trial can be downloaded [here](https://tasker.joaoapps.com/download.html).
	- [Play Store link](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en&gl=US)

##### Optional
- [AutoNotification](https://play.google.com/store/apps/details?id=com.joaomgcd.autonotification) - To add quick tile to trigger the Quick Notes dialog (this can be done with just Tasker too)

#### What is TaskerNet
TaskerNet is a website where you can store and share Tasker projects and tasks.

#### Notes
- Tapping outside of the input dialog when the keyboard is hidden will cancel the note and delete all contents, if you are writing a long note, you can save the note by typing the "SaveNoteCharacter" and pressing ok.
- Locking the screen when taking a note will cancel the note and delete all contents, use the "SaveAndExitNoteCharacter" before locking the screen
- The timestamp format can be configured in the "QuickNote" task, enter the task, tap on the search icon and search "timestamp", this will lead you to the action where you can edit the timestamp format.
