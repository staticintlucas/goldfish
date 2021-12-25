
# Goldfish

Goldfish is a Pro Micro compatible board designed for use in mechanical keyboards.
It is based on the same ATMega32U4 chip and is programmable using the Arduino IDE or a keyboard specific firmware such as TMK or QMK.

*Of course it is perfectly usable for any other electronics projects as well.*


![Preview]


---

**⸢ [PCB] ⸥ ⸢ [Schematic] ⸥**

---

## Advantages

- Lower board profile with the mid-mounted USB-C connector.
- Two internal pins make the USB data lines easily accessible.
- USB-C is more durable, reversible and just plain cool.
- 5 additional pins on the underside of the board.
- Pin-compatible with the original Pro Micro.
- Sturdier through-hole USB connector.

---

## Disadvantages

- Less choice for custom cables for USB-C compared to Mini-B / Micro-B.
- More expensive, depending on order quantity.
- No onboard RX, TX, LEDs.
- No onboard Voltage Regulator
  This is irrelevant for keyboards.
  External power supplies of > 5.5V require one.


---

## Known Issues

- `Rev 0` | `Rev A`:

  **Fixed:** `Rev B`

  Same problem as the **[Green Pro Micro]**,
  making it unsuitable for `Split Keyboards`.

---

## Vendors

**Selling Goldfish**

- `Rev C` \| Available on **[BeeKeeb]**.

- `Comet` \| Modified design \| Available on **[Tokas' Kable Works]**.

*Please let me know if any are missing from this list.*

### Note

These products are sold by **3rd Party Vendors**
and are not 'officially' endorsed by me.

*I'm simply listing them here for convenience.*

---

## License

**[Creative Commons Attribution Share-Alike 4.0 License][License]**.


**-** Original `Arduino Mini` design by **Team Arduino**.
**-** Arduino `Pro Mini` design by **Spark Fun Electronics**.
**-** `Pro Micro` design by **Spark Fun Electronics**.
**-** `Goldfish` design by **Dr Derivative**.

---

## Related Projects

- **[Alvaro]** by **Ariamelon**
    A modified goldfish using `0603` components instead of `0402`.

- **[Comet]** by **Tokas**
    A modified goldfish using a different `USB-C` connector.

- **[Goldfish-clone-JLCPCB]** by **Jeremy J Starcher**
    A modified goldfish designed to meet **JLCPCB**'s assembly requirements.

* **[Elite-C]** from `keeb.io`
    An unrelated and ***closed source*** project with similar design goals.



*Be sure to let me know if anything is missing form this list.*

---

## Changelog

#### Rev C

Changed layout of the bottom edge pins to match the `Elite-C`.

#### Rev B

Fixed split keyboard issue.

Tidied up parts of the layout, including the
removal of signal lines from under the crystal.

#### Rev A

Changed the footprint of `C6` from `0402` to
`0603` to reduce component cost by a few cent.

#### Rev 0

Initial Design.  



<!----------------------------------------------------------------------------->

[Schematic]: docs/schematic.pdf
[Preview]: docs/preview.png
[PCB]: cad

[Green Pro Micro]: http://www.40percent.club/2017/09/green-pro-micro.html
[License]: https://creativecommons.org/licenses/by-sa/4.0/

[Alvaro]: https://github.com/Ariamelon/Alvaro
[Comet]: https://github.com/vattern/comet
[Elite-C]: https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4
[Goldfish-clone-JLCPCB]: https://github.com/JeremyJStarcher/Goldfish-clone-JLCPCB

<!---------------------------------{ Vendors }--------------------------------->

[BeeKeeb]: https://shop.beekeeb.com/product/goldfish-rev-c-open-source-pro-micro-replacement/
[Tokas' Kable Works]: https://shop.tokas.co.uk/product/comet-usb-c-microcontroller/
