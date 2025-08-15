```________            _____           ______________________________________________
___  __ \______________(_)______ ______  __ )_  __ \__    |__  __ \__  __ \_  ___/
__  / / /  _ \_  __ \_  /__  __ `__ \_  __  |  / / /_  /| |_  /_/ /_  / / /____ \ 
_  /_/ //  __/  / / /  / _  / / / / /  /_/ // /_/ /_  ___ |  _, _/_  /_/ /____/ / 
/_____/ \___//_/ /_//_/  /_/ /_/ /_//_____/ \____/ /_/  |_/_/ |_| /_____/ /____/  
                                                                                  v1.0
==================================================================================================
DESCRIPTION:

Python script compiled to an executable that automatically runs EZBoards + EZ2Pages while 
decrementing waypoints for the F-15C - if necessary - whenever it detects a change to the Falcon 
BMS briefing.txt file.

Runs in the background with no interaction necessary.

Designed for use with OpenKneeboard.

=================================================================================================
INSTRUCTIONS:

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!BEFORE FIRST RUN USER MUST POINT TO FALCON BMS FOLDER VIA "pathtobms.txt" FILE IN THIS FOLDER!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Double click on the DenimBOARDS.exe or add it your Start Up Apps or Task Scheduler for click-free 
operation.  That's it.

It runs in the background.  Anytime you click "PRINT" on the BMS briefing page, it should update 
your DenimBOARDS/briefing folder.

Add the briefing folder to OpenKneeboard's tabs and it will automatically update the kneeboards 
whenever you print a briefing.

Since the app has no interface, if you need to kill it, do so via the Task Manager.

The app should self-prevent multiple instances.
================================================================================================
REQUIRED FILE STRUCTURE:

DenimBOARDS/ (contains EZBoards .bat scripts, pathtobms.txt, main executable, and documentation)
├──_internal/ (contains python libraries)
├──bin/ (contains EZBoards executables)
├──briefing/ (destination for briefing files and contains customizable style.css)

================================================================================================
CREDITS:

All EZBoards code by "Logic".
