# Snake

A semi-ortholinear keyboard with LEDs, rotary encoder support and spacebar options.

## How to build one

Very easy project.

### Part list
| #     | name                 | comments                                  |
|-------|----------------------|-------------------------------------------|
| 1     | main PCB             | Order at fabricator of your choice (ouch, expensive!)        |
| 42    | hotswap sockets      | Whatever you are into                 |
| 42    | switches             | MX compatible                        |
| 42    | Keycaps              | MX-compatible                         |
| 1     | Rotary Encoder       | optional                             |
| NA    | Rubber cord D3.53 mm |  https://www.amazon.de/-/en/SHOCRE-Rubber-Gasket-Nitrile-Diameter/dp/B0CGDMGRZM      |

- Solder the sockets to the PCB according to chosen layout. 
- Mount stabilizers. Note: depending on the layout you [i]may[/i] need to file just a tad the stabilizer lips, so they clear the diodes. If they do not seem to fit, do not force them into place, inspect and file if needed!
- Mount the plate to the PCB and secure it with switches in the corners. 
- Mount all other switches.
- Cut and insert cord pieces into the pockets between the PCB and the plate.
- Insert the assembly into the case. Start with the USB side.

### Firmware

- Install WinUSB driver, using Zadig (https://github.com/qmk/qmk_firmware/blob/master/docs/driver_installation_zadig.md)
- Flash the firmware onto the board. Bootloader mode: hold top left key while plugging in. I used QMK Toolbox (https://qmk.fm/toolbox).

### Done

Enjoy your Snake!

## Acknowledgements

Joe Scotto for publishing the STM32 Scottomodule (https://www.youtube.com/joe_scotto). 
Theycallmeboxy for case inspirations (https://github.com/theycallmeboxy/bassik).

## Gallery

![](gallery/snake-main.jpg)
