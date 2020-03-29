# ALU-Remapper-and-Mouse-Mode

This file was created to be used with the AtGames Legends Ultimate in USB OTG mode with CoinOPs Next/ RetroFE. Currently the following the configurations for ALU control mapping are available for CoinOPs menu, MaMe, Cemu, DEmul, DolphinX, FuturePinball, mednafen, N64, Pinballfx 3, redream, RetroArch,RetroArchSNES, Rpcs3, Samsung Gamboy, Sega Model 2 Emulator v1.1a, Sega Model 3, Sony Playstation 2, and Teknoparrot. Also include are MaMe custom profiles for using Trackball for games that use it as well as TOP down games for P1. Spinner games are supported as well in the custom profiles.

MaMe keys: Rewind + P1 = Exit Game, Rewind + Menu = MaMe Configuration menu.

- Setting [C] should only be used if your USB has the controllers swapped.
- Setting [D] copies some slight changes to the CoinOPS theme settings and layouts to increase speed.
- Setting [E] to bypass JoyToKey if using ALU MM file
- Setting [F] to replace retroFE with the latest version (3/24/2020) from gitHub I compiled
- Setting [G] Copy new custom CoinOPs executable to just load RetroFE and not load JoyToKey
- Setting [H] Should only be used when copying files has issues. Such as 0 files copied or errors.
- Setting [J] Opens Devices and Printers to so you can check if the ALU is showing up correctly.

[I] Add Mouse Mode to startup and run joystick mouse mode which allows you to use the ALU P1 and P2 controls to act like a mouse. Please be aware that this ALU OTG MM may throw a false positive on your virus scanner due to using MPRESS on the executable to make the executable smaller. This is the latest version (this will also check if running as admin, if not it will run as admin to be able to click on some other windows such as onscreenkeyboard).

A = Left Click 
B = Right Click
C = Middle Click (scrolling)

P1 A + Menu = Enable / Disable P1 MM
P2 A + Menu = Enable / Disable P2 MM

Rewind + P1 = Close App
Z + Menu = Open / Close x360ce 4.10 

*If you are using [H] This will run the takeown command allowing your account full access to the coinops folder and sub-folders. This make take some time if you have lot of add-on packs or the larger CoinOPS next file.
Special thanks to AtGames for an Awesome Arcade and the creators and members of RetroFE and CoinOPS. - Steve

3/27/2020 Release for the ALU CoinOPS joystick support

-------------------
- Installation
-------------------

Copy/Extract to the ROOT CoinOPS next folder and run the Restore AtGames USB.exe



--------------------
- What's New
--------------------

What's new in the version.

v1.3

- Created a windows app rather than a DOS batch file, so users can click rather than using a keyboard.
- Add an option to fix issues when copying files. The new option will use the windows takeown command to allow the current account full access to the coinops folders.
- Minor fixes
- Swap controllers due to ALU swapping controllers
- Added the joystick mouse mode to this. Will create a startup shortcut and launch mouse mode
- Add button to open the device and printers panel to see if ALU shows up and to be able to see if controls are defined correctly.
- Add the option to copy the latest RetroFE to the core folder (as of 3/24/2020)
- Added a new CoinOPS executable to just launch RetroFE without launching joytokey
- Add a slightly changed layout to the CoinOPS theme

v1.2
- Added trackball for top-down shooters and spinner support for games that can use it
	- Added support for trackball and spinner for over 150+ mame games
- Control definition for Cemu
- Control definition for DEmul
- Control definition for DolphinX
- Control definition for FuturePinball (P1 A left flipper, P2 Z right flipper, Rewind Launcher, Menu Coin, P1 Coin)
- Control definition for mednafen
- Control definition for N64
- Control definition for Pinballfx3 (P1 A left flipper, P2 Z right flipper, Rewind Launcher, etc)
- Control definition for redream
- Control definition for RetroArch
- Control definition for RetroArchSNES
- Control definition for Rpcs3
- Control definition for Samsung Gamboy
- Control definition for Sega Model 2 Emulator v1.1a
- Control definition for Sega Model 3
- Control definition for Sony Playstation 2
- Control definition for Teknoparrot
- Let's use change joytokey ALT-F4 to use ALU_USB_OTG_MouseMode Rewind+P1 to close emulator apps.

v1.1
- You can now choose ABC or XYZ default setup. 

v1.0
- Adds support for the ALU USB mode in CoinOPs
- Default is XYZ
- Controls are for MaMe (no setup yet for trackball or spinner, but can be added per game in mame config)
- MaMe config controller support (Rewind + Menu opens mame config)


