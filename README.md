# CwruStimLib
CWRU UECU Muscle Stimulation Board C Library

**Git Clone this repo to your local work folder. Branch it if you need to modify it.**

* [Folder] Example - Sample higher level code to use this library.

* [Folder] CwruStimLibHAL - Platform specific Hardware Abstraction Layer (HAL).

* [Folder] PresetPatterns - Preset pattern files.

* CwruStimLibStruct.h - The data structureesettings.
 of the Stim class.

* CwruStimLibConst.h - Constant values and pr
* CwruStimLib.h/.c - Top level user functions. User 
only need to call these functions to setup, start, and update the stim boards.
* CwruStimExe.h/.c - Advanced user functions, mostly low level hardware related. Normal user don't need to call these functions, but it can give you the full control at channel level.

* CwruStimCmd.h/.c - UECU command functions. Specific design to match the UECU and stim board communication requirements.

* CwruStimLibInit.h/.c - Routine procedures to setup the boards, channels, and patterns.

* CwruStimLibUtils.h/.c - Utility functions to make life easier.

**Note**

The UECU Message Handbook I made, and it would be the most helpful doc if anyone want to work on the stim board communication in the future:
https://goo.gl/s20iH4

