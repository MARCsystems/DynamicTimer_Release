This repository acts as a release port for the DynamicTimer, as the main repository is private.







----------------------
Dynamic Timer : by SolarPH / MARCsystems

Features:
  - Timer Labeling : Assign a label to your timer for more timer distinction
  - Auto-Stop on Zero : A timer setting that stops the time when it hits Zero, or a few milliseconds below.
  - Carry-Over to Next : A timer setting that is best paired with "Auto-Stop on Zero" and "Start Next on Stop". This ensures that the excess value from the previous timer will be accounted on the next timer in the sequence
  - Delta-Time Adjustment : This application uses Delta-Time formula to ensure that every millisecond counts.
  - Time View Mode : Choose the view between "H:MM:SS", "MM:SS", or "SS". You can even add the three-digit millisecond on your timer.
  - OBS Overlay Element : A zero-visibility window that only OBS can detect via Windows Capture with Capture Mode "Windows 10 (1903 and up)" for transparency capture.

Controls:
  - Start/Pause and Stop : Basic timer operations.
  - Record : Take note of the current time when needed.
  - Freeze/Unfreeze : Control the time shown on screen without actually pausing the timer.
  - Update Frozen : Best used if the time needs to continue updating even if it was meant to be paused.
  - Reset Current Timer: Resets the timer to its initial value without resetting the whole sequence.
  - Reset All : Resets the whole sequence. Best if you have 2 or more timers created in sequence.

Upgrade Milestones:
  - Better UI
  - Floating Controls that can be pinned on top of every window
  - Separate menus for all
  - Modifiable Background
