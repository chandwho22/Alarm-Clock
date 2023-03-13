# Alarm-clock
Frontend project Alarm-clock-System using HTML,CSS,JS

The application has a clock display that shows the current time, with three input fields for hour, minute, and median AM/PM. These input fields are mandatory, and if any of them are missing, an invalid time alert is thrown. If a user tries to add an alarm with the same time as an existing one, an alert is displayed indicating that it already exists.

There are three buttons available: SET, RESET, and STOP. The STOP button becomes visible when an alarm starts ringing. When the current time matches the set alarm time, an audio file plays, and the clock image animation starts, indicating that the alarm is ringing. The STOP button is also visible, allowing users to stop the audio file and the clock image animation by clicking on either the stop button or the clock image.

Set alarms are displayed in an upcoming alarm list at the bottom of the screen, and each added alarm is pushed into an array. Multiple alarms can be added to the array, and each element is matched with the current time to trigger the alarm.

The RESET button clears the input fields and returns them to their original values. To add an alarm to the array and upcoming alarm list, a div is created using JavaScript and removed using the remove function.
Testing weather it's working fine or not.......