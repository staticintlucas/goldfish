# Goldfish v2

**Note: This branch contains the work in progress design for Goldfish v2. The original Goldfish v1 design files are available in the [v1 branch].**

Goldfish is a Pro Micro compatible microcontroller board designed for use in mechanical keyboards. It is based on the same Atmel ATMega32U4 chip and is programmable using the Arduino IDE or a keyboard specific firmware such as TMK or QMK. Of course it is perfectly usable for any other electronics projects too, not just keyboards.

![preview]

## Links

- [PCB Source Files]

- [Schematic]

## Features

- Lower board profile with the mid-mounted USB-C connector
- Two internal pins make the USB data lines easily accessible
- USB-C is more durable, reversible and just plain cool
- 5 additional pins on the underside of the board
- Pin-compatible with the original Pro Micro
- Sturdier through-hole USB connector
- On board ESD protection for USB lines

## Changes compared to Goldfish v1

- Less obscure USB-C connector
  - Use of more commonly available components in 2022
  - Choice between multiple compatible connectors and suppliers
  - Uses USB 2.0-only connector for easier and cheaper assembly
- Addition of board ESD protection and fuse
- All 0603 resistors and capacitors for (slightly) easier hand assembly
- Castellated edge connectors similar to the Elite-C

## Disadvantages

- No onboard RX, TX, LEDs
- No onboard Voltage Regulator (this makes no difference for keyboards; a regulator is only required when power supplies of over 5.5V are used)

## Vendors Selling Goldfish

#### Goldfish v1 rev. C

- [BeeKeeb]

#### Comet (modified design based on Goldfish v1; see related projects) 

- [Tokas' Kable Works]

**Note:** These products are sold by 3rd party vendors and are not 'officially' endorsed by me. I'm simply listing them here for convenience.

*(Also please let me know if anything is missing from this list)*

## Related Projects

#### [Alvaro] by Ariamelon

- A modified Goldfish v1 using 0603 components instead of 0402

#### [Comet] by Tokas

- A modified Goldfish v1 using a HRO TYPE-C-31-M-12 connector

#### [Whale] by Jia Geng Chang

- A modified Goldfish v1 using a Jing 918-418K2024S40000 connector

#### [Goldfish-clone-JLCPCB] by Jeremy J Starcher

- A modified Goldfish v1 designed to meet JLCPCB's assembly requirements

#### [Elite-C] from keeb.io

- An unrelated and closed source project with similar design goals

*(Please let me know if anything is missing form this list)*

## License

Released under the Creative Commons Attribution Share-Alike 4.0 License.  
https://creativecommons.org/licenses/by-sa/4.0/  

Original Arduino Mini Design by Team Arduino.  
Arduino Pro Mini Design by Spark Fun Electronics.  
Pro Micro Design by Spark Fun Electronics.  
Goldfish Design by Lucas Jansen.  

<!-- Links -->

[v1 branch]: https://github.com/staticintlucas/goldfish/tree/v1
[schematic]: docs/schematic.pdf
[preview]: docs/preview.png
[pcb source files]: cad

[beekeeb]: https://shop.beekeeb.com/product/goldfish-rev-c-open-source-pro-micro-replacement/
[tokas' kable works]: https://shop.tokas.co.uk/product/comet-usb-c-microcontroller/

[alvaro]: https://github.com/Ariamelon/Alvaro
[comet]: https://github.com/vattern/comet
[whale]: https://github.com/JiaGengChang/Whale
[elite-c]: https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4
[goldfish-clone-jlcpcb]: https://github.com/JeremyJStarcher/Goldfish-clone-JLCPCB
