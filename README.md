# Tiny4FSK Ecosystem

### A set of additional features, tools, and boards to expand functionality of Tiny4FSK

### TinyShield
TinyShield is an expansion board which sits atop of Tiny4FSK's expansion pins. It adds:
1. An OLED screen for basic flight diagnostics,
2. SD card for logging,
3. 5v logic headers for more sensors,
4. Integrated buck/boost for wider range of power sources, including a LiPo connector,
5. Qwiic headers for adding more sensors!

Code in the Tiny4FSK repository already implements automatic sensor, SD card, and screen scanning and initialization. Functions pertaining to these features are configurable in both `config.h` and the main `Tiny4FSK.ino` file.

To get started, solder female headers to the 2.54mm pins on the back side of the shield. To interface with the Tiny4FSK board, additionally solder 2.54mm male header rows to the USB, power, and data headers on the Tiny4FSK. Mounting them for alignment may assist with soldering.

Insert the shield board onto the Tiny4FSK's headers as shown. No code changes are required to continue with SD card logging and screen initialization.

![Boards stacked](/Media/headers.png)