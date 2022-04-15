# QuickNote
 A way to take Quick Notes in Obsidian on Android

 # Quick Notes in Obsidian
### A way to take Quick Notes in [Obsidian](https://obsidian.md/) on Android

This task displays an input dialog to take a note in the app Obsidian.

---
[Link to project in TaskerNet]()

#### Features
- Quick Notes dialog from home screen widget, quick tile or notification
- Quick add to a to do file using a special character
- Special characters - configurable characters that do certain thing when it is the first or last character in a note
	- Todo
		- Saves the note to a todo folder, and prepend it with a checkbox if the option is selected. Must be written at the beginning of a note.
	- Save note
		- Save the note. Must be written at the end of a note.
	- Save and exit note
		- Save the note and close the input dialog. Must be written at the end of a note.
	- Clear note
		- Clears all the text in the input dialog. Must be written at the end of the note. 
	- Escape
		- Tells the task to ignore a custom character

#### Instructions to import and use the project
- Install Obsidian
- Install Tasker
- Open this [TaskerNet]() link on your phone
- Tap on "Import"
- View the description if you want to
- Import Data prompt - Tap on yes
- Do you want to enable all the profiles right away? Tap no
- This project has a launch task, run? yes
- follow the instructions.

#### Permissions
- Accessibly service to detect tapped notification with Tasker notification (this is optional)
- App usage stats to detect AutoNotification is installed. (this is optional)
- Draw over other apps for the settings dialog on the home screen
- Manage external storage to write files

#### Apps
##### Required
- [Obsidian](https://obsidian.md/) - A notes app that is a powerful knowledge base on top of a local folder of plain text Markdown files.
	- [Play Store link](https://play.google.com/store/apps/details?id=md.obsidian)
- [Tasker](https://tasker.joaoapps.com/) -  Tasker is an Android application that performs tasks, based on contexts like application, event, gesture, date, time, location in user defined profiles or home screen widgets. A 7 day free trial can be downloaded [here](https://tasker.joaoapps.com/download.html)
	- [Play Store link](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en&gl=US)

##### Optional
- [AutoNotification](https://play.google.com/store/apps/details?id=com.joaomgcd.autonotification) - To add a permanent notification you can tap to trigger the Quick Notes dialog (this can be done with just Tasker too)
- [AutoApps](https://play.google.com/store/apps/details?id=com.joaomgcd.autoappshub)

#### What is TaskerNet
TaskerNet is a website where you can store and share Tasker projects and tasks.


#### Notes
- Tapping outside of the input dialog when the keyboard is hidden will cancel the note and delete all contents, if you are writing a long note, you can save the note by typing the "SaveNoteCharacter" and pressing ok.
- Locking the screen when taking a note will cancel the note and delete all contents, use the "SaveAndExitNoteCharacter" before locking the screen
