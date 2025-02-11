# smartport-nano-shield with 20pin IDC

the zip file called SmartPortSD-Nano-Shield-Main-20IDC.ZIP has the kicad files, the new gerbers etc. :)
please view the gerbers before ordering board just to make sure this is the correct file. :)


This is a custom PCB from DJTERSTEEGC, with an IDC connector to run the SmartportSD FAT code from Katherine Stark (based on the work of Robert Justice and Andrea Ottaviani) allowing you to connect a 32MB ProDOS partition to your SmartPort enabled Apple II (IIc, IIc+, IIgs).  Yes, it works with Total Replay.

Katherine's original repo is at https://gitlab.com/nyankat/smartportsd

this is forked from  https://gitlab.com/tersteeg/smartportsd that adds support for the four LED's in this design that show you the currently active partition.

All components can be sourced from the usual low cost China based vendors for a total build cost of around $10.  Please see the assembly page for more details.

[Hardware Component Choices and Assembly](https://djtersteegc.github.io/smartportsd-nano-shield/assembly.html)

Please see the original version of this board for the interactive BOM and component placement, the only thing that changed is the IDC20 pin.

If you wish to power your board from the 5V SmartPort line, simply install and close jumper JP1.  Be warned there is no protection on the board from back feeding voltage into the Apple host computer if you also power the Arduino via the USB connector, so only close this jumper when not using another power source on the Arduino.

I will add the gerbers for the IDC version incase someone wants that

Otherwise you can download the Gerbers and use your favorite fab (JLCPCB, PCBWay, etc.) to make your own batch.  It's a standard two layer, 1oz copper board with dimensions of 70mm x 56mm.

# Hardware Revisions

### Version 1.0

Tested and working.

# Acknowledgments

DJTERSTEEGC for doing most of the work on this board, Steve Gray removed the 25 pin connector and replaced with a 20 pin IDC.

Robert Justice for his original SmartPortCFA project http://www.users.on.net/~rjustice/SmartportCFA/SmartportCFA.htm

Andrea Ottaviani for his Arduino/SD port of Robert's work http://www.users.on.net/~rjustice/SmartportCFA/SmartportSD.htm

Katherine Stark for adding FAT support to Andrea's work to make it easier to manage the partitions on the SD card.



