# avr_programmer_adapter
An impromptu adapter to program the ATMega 328P on an Arduino Nano through its normal socket rather than the ICSP header.

I got a Maker Nano the other day (https://www.cytron.io/p-maker-nano-simplifying-arduino-for-projects) and while I like the fact it has extra stuff on the board, like LEDs and a button, this comes at the expense of not having an ICSP header. I needed to burn a new bootloader into the Nano, so I improvised an adapter with a perfboard. A bit crude, but does the job. Schematic to follow.

Photos show regular Arduino Nano (albeit a cheap clone) without header, for testing. Lower 2 holes in the ZIF socket not needed. Arduino has 30 pins, and I could only find ZIF sockets with either 28 or 32 pins.

![IMG_20230430_004503](https://github.com/avlunen/avr_programmer_adapter/assets/11347973/57a349b3-73d6-48d7-978e-2f768dae7c58)
![IMG_20230430_004917](https://github.com/avlunen/avr_programmer_adapter/assets/11347973/08743f16-c672-447e-a9d6-18a19d3372ac)
![IMG_20230430_004929](https://github.com/avlunen/avr_programmer_adapter/assets/11347973/893a1b4c-1b97-4cf8-a2be-31b324b7f291)
