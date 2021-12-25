
[Changelog]: docs/Changelog.md
[Schematic]: docs/Schematic.pdf
[Preview]: docs/Preview.png
[Vendors]: docs/Vendors.md
[PCB]: cad

[Green Pro Micro]: http://www.40percent.club/2017/09/green-pro-micro.html
[License]: https://creativecommons.org/licenses/by-sa/4.0/

[Alvaro]: https://github.com/Ariamelon/Alvaro
[Comet]: https://github.com/vattern/comet
[Elite-C]: https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4
[Goldfish-clone-JLCPCB]: https://github.com/JeremyJStarcher/Goldfish-clone-JLCPCB

<!----------------------------------------------------------------------------->

# Goldfish

This **Pro Micro** compatible board designed for use in `Mechanical Keyboards`, <br>
based on the same `ATMega32U4` chip and programmable using the **Arduino IDE** <br>
or a keyboard specific firmware such as `TMK` or `QMK`.

![Preview]

*Of course it is perfectly usable for any other electronics projects as well.*

---

**⸢ [PCB] ⸥ ⸢ [Schematic] ⸥ ⸢ [Vendors] ⸥ ⸢ [Changelog] ⸥**

---

## Advantages

- ***Lower board profile*** with the mid-mounted `USB-C` connector.

- Two internal pins make the **USB** data lines easily accessible.

- `USB-C` is more ***durable***, ***reversible*** and just *plain cool*.

- `5` additional pins on the underside of the board.

- Pin-compatible with the original **Pro Micro**.

- ***Sturdier*** through-hole **USB** connector.

---

## Disadvantages

- Less choice for custom cables for `USB-C` compared to `Mini-B` / `Micro-B`.

- More ***expensive***, *depending on order quantity*.

- No onboard `Voltage Regulator`

  *This is irrelevant for keyboards.* <br>
  *External power supplies of `> 5.5V` require one.*

- No onboard `RX`, `TX`, `LEDs`.

---

## Known Issues

- `Rev 0` | `Rev A`:

  **Fixed:** `Rev B`

  Same problem as the **[Green Pro Micro]**, <br>
  making it unsuitable for `Split Keyboards`.

---

## License

**[Creative Commons Attribution Share-Alike 4.0 License][License]**.


**⤷** Original `Arduino Mini` design by **Team Arduino**. <br>
**⤷** Arduino `Pro Mini` design by **Spark Fun Electronics**. <br>
**⤷** `Pro Micro` design by **Spark Fun Electronics**. <br>
**⤷** `Goldfish` design by **Dr Derivative**.

---

## Related Projects

- **[Alvaro]** by **Ariamelon** <br>
    A modified goldfish using `0603` components instead of `0402`.

- **[Comet]** by **Tokas** <br>
    A modified goldfish using a different `USB-C` connector.

- **[Goldfish-clone-JLCPCB]** by **Jeremy J Starcher** <br>
    A modified goldfish designed to meet **JLCPCB**'s assembly requirements.

* **[Elite-C]** from `keeb.io` <br>
    An unrelated and ***closed source*** project with similar design goals.

<br>

*Be sure to let me know if anything is missing form this list.*
