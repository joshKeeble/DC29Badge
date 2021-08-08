# DC29Badge
Steps and references for hacking the Defcon 29 Badge

Before you begin ensure that you have the latest firmware for the board, the firmware it comes with has had multiple bugs including only generating 31 char codes instead of 32 char ones. You can download the latest firmware from defcon.org/signal, or from this repo, called D29Human3.uf2

Boot your board into USB mode by holding the bottom right key and turning the power on. Then connect to your computer through the provided USB-C cable. Navigate to the new device in your file explorer and place the firmware file into it, it should automatically restart the badge and eject it from your computer. You can then serial into your board using the commands below in your terminal.

For Mac devices: screen /dev/tty.usbmodem123451 9600
For PC devices: 
