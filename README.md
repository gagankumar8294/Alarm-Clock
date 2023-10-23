# Alarm-Clock
Alarm clock designed for Coding Ninja project


Alarm Clock App
This alarm clock app allows users to set multiple alarms, display an alarm list, delete alarms, play alarm sounds, and stop alarms. It is a vanilla JavaScript web app, with no external libraries required.

Features
Set multiple alarms with hour, minute, second, and AM/PM selection.
View a list of all set alarms.
Delete alarms with a click.
Play alarm sounds when the alarm time is reached.
Stop alarm sounds with a click.
How it works
The app maintains an array of all set alarms. Every second, the app checks the current time against the array of alarms. If a match is found, the alarm sound is played.

Using the app
To set an alarm, enter the desired time and select AM or PM. Then, click the "Set Alarm" button. To view the list of set alarms, click the "Alarm List" button. To delete an alarm, click the "Delete" button next to the alarm you want to remove. To stop an alarm sound, click the "Stop Alarm" button.

Project approach
The app uses the following approach:

When the user sets an alarm, the alarm is added to the array of alarms.
Every second, the app checks the current time against the array of alarms.
If a match is found, the alarm sound is played.
When the user stops an alarm, the alarm sound is paused and the alarm duration is reset.
When the user deletes an alarm, the alarm is removed from the array of alarms and the alarm list is rendered.
Conclusion
This alarm clock app is a simple and easy-to-use tool for managing alarms. It is written in vanilla JavaScript and does not require any external libraries.