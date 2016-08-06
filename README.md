# myevic
````
This is My eVic VTC Mini.

Upgraded 3.03 firmware

Usage:
Unencoded firmware in the bin/ directory
Use evic-usb to upload it to you box

Main Features:
My custom firmware is more or less identical to the official firmware - Just added some missing features

Menus:
  Holding fire and right button a few seconds enters menus.
  There's many more to LOGO and Game menus now. See below.

Double-click:
  A double fire click switches between standard view and clock screen.
  The clock screen is close to the one viewed on the VTwo box; just better.
  See below to know how to configure clock.

Menus:

-Screen
  -Contrast
    Self-explanatory
  -Protection
    Configure screen saver timing

-Coils
  See and/or reset saved coil resistances for each TC mode.
  Click on a resistance to unlock and reset it.

-Clock
  -Date/Time
    Setup date and time.
    Fire change edited field, + and - set value.
   -Clk Adjust
    Adjust clock: for small adjustments to clock time
    + and - adjust clock by seconds. Fire to save. For VTwo owners,
    this option also adjusts the X32 frequency accordingly.
  -Clk Speed
    For owners of VTC mini (useless for VTwo owners)
    The VTC mini does not have the needed 32kHz crystal soldered on
    the pcb to regulate the clock speed; so, another internal clock
    source is used to drive the clock. Since its frequency is quite
    different, a clock speed ratio is needed to regulate the clock.
    Usage: First setup date & time. Wait a few hours to let the
    clock drift; then use this menu to adjust time to the real time.
    This will compute the box-specific ratio between real time and
    internal processor clock speed. Accuracy of a few seconds per
    day can be achieved this way.

-Modes
  Configure used/useless modes.
  Click on each menu item to set 'Y' or 'N' if you want to see any
  given mode proposed while cycling between modes in menu mode.
  Typically, you'll set "START" mode to 'N'. Typically.

-Miscs
  -LOGO
    Guenuine menu
  -Game
    Flappy bird. Guenuine menu.
  -3D
    Cool 3D spinning cube.
    Come back to this menu and set it to "None" to cancel animation.
    Or reset the box.
```
