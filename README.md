# Digital-Alarm-Clock-using-8051-microcontroller
The Digital Alarm Clock project is aimed to design and implement an alarm clock in a 8051 development board that integrates essential and user-friendly features. The user can set an alarm to a preferred time. Then, at that time, a buzzer will make a loud sound for the alarm. There would be a snooze functionality with different snooze durations such as 5, 10 or 15 minutes. To stop the alarm, the user has to go through a LED-based user input system. Finally we want to integrate some additional features such as a stopwatch mode, sleep mode, brightness adjustment and gradual increment of volume.

# Main Project Goals:
Develop an alarm system with input through a keypad and snooze option.
Integrate an interactive alarm stopping mechanism using a sequence of colored LEDs.
# Additional Features:
Implement a functional real-time clock to back the alarm system
Implement additional features like stopwatch, time set up functions
Implement quality of life improvements such as alarm indicator light

# Features:
1. Alarm Setting:
  
Clock Initialization and Running:

When the simulation starts, the clock begins running automatically from 00:00 (zero time).
The clock counts up every second, showing the current time on the display.
No manual input is needed initially for time progression.
To provide a continuously updating real-time clock right after powering on.

Setting the Current Time (Using 'D' Button):
To set the correct current time manually, the user presses the ‘D’ button on the keypad.
After pressing 'D', the system enters Time Set Mode.
The user can then input the desired time (hours and minutes) using the keypad.
After setting, the clock resumes counting from the newly entered time.
This  allows the user to manually adjust the clock to the real current time whenever needed.

Setting the Alarm Time (Using '*' Button):
To set an alarm, the user presses the ‘*’ button on the keypad.
After pressing '*', the system enters Alarm Set Mode.
The user inputs the alarm time (hours and minutes) using the keypad.
Once set, the alarm time is stored internally, and the clock continues running normally.
This lets the user program an alarm that will trigger at a specific future time.

2. Buzzer Alarm
When the real-time clock matches the stored alarm time, the system turns ON the buzzer (sounder).
The buzzer produces a loud, continuous sound to alert the user.
The buzzer keeps ringing until the user either snoozes the alarm or dismisses it through the LED input system.
This feature wakes the user or alerts them clearly when it’s time.

3. Snooze Functionality
When the alarm rings, the user can press a SNOOZE button.
Upon snoozing, the alarm temporarily stops.
The system adds a fixed snooze period (5, 10, or 15 minutes) to the current time.
After the snooze period passes, the alarm rings again.
Gives the user extra time before the alarm rings again, without requiring full dismissal.

4. LED-Based Input System for Alarm Dismissal
Instead of easily turning off the alarm, the system demands a correct sequence of inputs through an LED-guided challenge.
LEDs flash in a particular sequence or pattern.
The user must press matching buttons correctly, according to the LED pattern.
Only after successfully completing the sequence, the buzzer stops.
This feature forces the user to become fully awake and alert, making it harder to casually dismiss the alarm and fall back asleep.

5. Stopwatch Mode
The user activates Stopwatch Mode by pressing the '#' button on the keypad.
After entering Stopwatch Mode, the display shows 00:00:00 (hours:minutes:seconds).
To Start the stopwatch, the user presses the 'A' button on the keypad. The stopwatch begins counting up every second.
To Stop or Pause the stopwatch, the user presses the 'B' button. The stopwatch halts at the current time.
This feature provides a basic, manual stopwatch functionality — useful for timing events, exercises, experiments, etc., making the alarm clock device more versatile.
