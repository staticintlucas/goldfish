# Goldfish v2

> [!NOTE]\
> The main branch contains the design for Goldfish v2. The Goldfish v1 design is available in the [v1 branch](https://github.com/staticintlucas/goldfish/tree/v1)

Goldfish is a Pro Micro compatible microcontroller board designed for use in mechanical keyboards. It is based on the same Atmel ATMega32U4 chip and is programmable using the Arduino IDE or a keyboard specific firmware such as TMK or QMK. Of course it is perfectly usable for any other electronics projects too, not just keyboards.

![preview](docs/preview.png)

## Links

- [PCB Source Files](cad)

- [Schematic](docs/schematic.pdf)

- [BOM](BOM.csv)

## Features

- Lower board profile with the mid-mounted USB-C connector
- Two internal pins make the USB data lines easily accessible
- USB-C is more durable, reversible and just plain cool
- 5 additional pins on the bottom edge of the board
- Pin-compatible with the original Pro Micro
- Sturdier through-hole USB connector
- On board ESD protection for USB lines

## Changes compared to Goldfish v1

- Addition of on board ESD protection and fuse
- All 0603 resistors and capacitors for (slightly) easier hand assembly
- Castellated edge connectors similar to the Elite-C
- Less obscure USB-C connector
  - Use of more commonly available components in 2022
  - Choice between multiple compatible connectors and suppliers
  - Uses USB 2.0-only connector for easier and cheaper assembly

## USB-C Connectors

| Manufacturer | Part number | | | |
|:--- |:---:|:---:|:---:|:---:|
| Molex | 216990-0001 | - | 216990-0003 | 216990-0002 |
| HRO | - | TYPE-C-31-M-13C | TYPE-C-31-M-13B | TYPE-C-31-M-13A |
| GCT | USB4520 | USB4510 | USB4505 | USB4500 |
| Approx. thickness<br>1.2 mm PCB | ![c21p12]<br>3.2 mm | ![c16p12]<br>3.2 mm | ![c10p12]<br>3.4 mm | ![c08p12]<br>3.6 mm |
| Approx. thickness<br>1.6 mm PCB | ![c21p16]<br>3.2 mm | ![c16p16]<br>3.2 mm | ![c10p16]<br>3.8 mm | ![c08p16]<br>4.0 mm |

[c21p12]: docs/connectors/conn-21-pcb-12.png
[c16p12]: docs/connectors/conn-16-pcb-12.png
[c10p12]: docs/connectors/conn-10-pcb-12.png
[c08p12]: docs/connectors/conn-08-pcb-12.png
[c21p16]: docs/connectors/conn-21-pcb-16.png
[c16p16]: docs/connectors/conn-16-pcb-16.png
[c10p16]: docs/connectors/conn-10-pcb-16.png
[c08p16]: docs/connectors/conn-08-pcb-16.png

## Limitations compared to a Pro Micro

- No onboard RX, TX LEDs
- No onboard voltage regulator (this makes no difference for keyboards; a regulator is only required when power supplies of over 5.5V are used)

## Vendors Selling Goldfish

#### Goldfish v1 rev. C

- [BeeKeeb]

#### Comet (modified design based on Goldfish v1; see related projects)

- [Tokas' Kable Works]

**Note:** These products are sold by 3rd party vendors and are not 'officially' endorsed by me. I'm simply listing them here for convenience.

[beekeeb]: https://shop.beekeeb.com/product/goldfish-rev-c-open-source-pro-micro-replacement/
[tokas' kable works]: https://shop.tokas.co.uk/product/comet-usb-c-microcontroller/

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

[alvaro]: https://github.com/Ariamelon/Alvaro
[comet]: https://github.com/vattern/comet
[whale]: https://github.com/JiaGengChang/Whale
[elite-c]: https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4
[goldfish-clone-jlcpcb]: https://github.com/JeremyJStarcher/Goldfish-clone-JLCPCB

*(Please let me know if anything is missing form this list)*

## License

Released under the Creative Commons Attribution Share-Alike 4.0 License.
https://creativecommons.org/licenses/by-sa/4.0/

Original Arduino Mini Design by Team Arduino.
Arduino Pro Mini Design by Spark Fun Electronics.
Pro Micro Design by Spark Fun Electronics.
Goldfish Design by Lucas Jansen.
