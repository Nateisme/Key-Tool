Key Tool Refurbished (KTR) is a keyboard, mouse, and controller macro utility for Windows PCs.

KTR supports:

* Keyboard macros
* Mouse click macros
* Controller macros
* Analog stick emulation
* Trigger emulation
* Xbox 360 virtual controller output
* DualShock 4 virtual controller output
* Optional passthrough mode
* Physical controller remapping through a virtual controller layer

 Features

Keyboard Support

* Hold keys continuously
* Timed key presses
* Multi-key combinations

Mouse Support

* Mouse click macros
* Continuous click support

Controller Support

* Xbox controller support
* PlayStation controller support
* Generic controller support
* Analog sticks
* Analog triggers
* D-pad support
* Touchpad click support in DS4 mode

KTR can emulate:

* Xbox 360 controllers
* DualShock 4 controllers

This allows games to detect KTR as a real controller.

---

ViGEmBus Driver (Required for virtual controller support.)

Download:
https://github.com/nefarius/ViGEmBus/releases

Install the latest: ViGEmBusSetup_x64.msi

HidHide (Optional but Recommended)

Recommended for stubborn games that:

* detect multiple controllers
* assign KTR as Player 2
* flicker between keyboard/controller prompts
* ignore virtual controller input

Download:
https://github.com/nefarius/HidHide/releases

Install the latest HidHide_x64.exe

HidHide Setup

1. Open HidHide Configuration Client

2. Add KTR.exe to Applications (This allows KTR to still see your physical controller)

3. Hide Your Physical Controller

Hide:

* PS5 controller
* PS4 controller
* Xbox controller
* other physical gamepads

DO NOT hide:

* keyboard
* mouse
* KTR virtual controller

Running Macros

1. Select Hold Inputs
2. Select Press Inputs
3. Press Start
4. Press Stop to end the macro

Some games may require:

* restarting the game after launching KTR
* HidHide
* switching between Xbox and DS4 output modes

 Troubleshooting:

Game Does Not Detect Inputs

Try:

* launching KTR before the game
* using HidHide
* restarting the game
* switching output mode

Steam Sees Wrong Controller Type Restart KTR and choose a different virtual output mode. (only really matters if you care what buttons are displayed in games)

KTR Does Not Detect Controller

Try:

* reconnecting the controller
* refreshing controllers in KTR
* restarting KTR
* checking HidHide settings

---

# Credits

KTR uses:

* vgamepad
* ViGEmBus
* pygame
* HidHide
* PyInstaller

Special thanks to the ViGEm and Nefarius projects for virtual controller support.

---

# Version

Key Tool Refurbished V0.9.1
