# nRF52840 tag

## What's this?

This is a development board works with coin batteries based on Adafruit Feather nRF52840 Express. This board works on all bootloaders of Adafruit Feather nRF52840 Express.


## Features

- Works with coin battery(CR2032)
- Extra battery(PH connector) support(Not suport charging)
- USB Type-C(USB 2.0)
- Warking same as Adafruit Feather nRF52840 Express(CircuitPython etc)
    - Programmable Full color LED(NeoPIXEL)
    - 1 usable push switch in program
    - 16MBit Flash memory


## How to use

1. Connect j-link and this board via SWD vias back side of this board.
2. Burn a bootloader you want to use with nrfjprog command.
    (For more detail, read "Burninng new Bootloader" on [adafruit's github](https://github.com/adafruit/Adafruit_nRF52_Arduino)