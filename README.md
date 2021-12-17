# NOTE: THIS IS NOW NATIVE TO MACOS 12 MONTEREY

# Scheduled-Join-Zoom-Meeting

This is an automated script that will prompt you to join your Zoom meeting at the meeting start time. It will then enter the necessary id and password and join. It will also quit Zoom after your meeting window closes. 

This is exclusive to MacOS.

<img src="https://github.com/EmaadKhwaja/Scheduled-Join-Zoom-Meeting/blob/main/Images/Prompt.jpg?raw=true" height="200">

## Guide

1. Download the ```Template.zip``` file and unzip it to a permanent location.
2. Open ```Automator``` and open the ```Template.app``` file.
<img src="https://github.com/EmaadKhwaja/Scheduled-Join-Zoom-Meeting/blob/main/Images/Automator.jpg?raw=true" height="500">

3. Set ```Title``` to whatever you'd like it to say in the prompt box.

4. Enter the 10 digit zoom id in the quotes next to ```zoom_id```.

5. If there is a password for the meeting, similarly set this in ```pword```.
6. Launch the app and click 'OK'. It will fail. Next, open ```System Preferences```. Navigate to ```Full Disk Access``` and add ```Template.app```. 
7. Open the ```Calendar``` app and create a new meeting corresponding to your meeting time. I set this as a recurring meeting.
<img src="https://github.com/EmaadKhwaja/Scheduled-Join-Zoom-Meeting/blob/main/Images/meeting.jpg?raw=true" height="500">

8. Click on the meeting block, click the ```+``` sign next to alert. On the newly made alert, click the box that says ```None``` and set it to ```Custom```
<img src="https://github.com/EmaadKhwaja/Scheduled-Join-Zoom-Meeting/blob/main/Images/CustomAlert.jpg?raw=true" height="500">

9. Select ```Open file``` and set it to the ```Template.app``` application. Set the time to 1 minute before the meeting.
<img src="https://github.com/EmaadKhwaja/Scheduled-Join-Zoom-Meeting/blob/main/Images/OpenFile.jpg?raw=true" height="200">
