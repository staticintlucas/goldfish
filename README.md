# Goldfish
The goldfish is a Pro Micro compatible microcontroller designed for use in mechanical keyboards, although it is perfectly suitable for any other hobby electronics project.
It is based on the same ATMega32U4 chip as the original Pro Micro and can be programmed using the Arduino IDE, or keyboard specific firmware such as TMK or QMK.

## Advantages
* The through-hole USB connector is much less likely to break off compared to surface mount connectors.
* USB-C is reversible, more durable and just plain cool.
* Pin-compatible with the original Pro Micro and Pro Micro clones.
* Goldfish has five extra pins available along its bottom edge if more pins are required.
* USB data lines are easily accessible through two internal pins.
* A mid-mounted USB-C connector allows goldfish to be much thinner than a Pro Micro.

## Disadvantages
* Fewer custom cable options for USB-C when compared to Mini-B/Micro-B.
* More expensive (depends on order quantity of course).
* No onboard voltage regulator (this makes no difference for keyboards; an external regulator is only required when power supplies of over 5.5V are used).
* No onboard RX, TX or Power indicator LEDs

## Known Issues
* Rev. 0 and Rev. A both suffer from a similar issue to the [green Pro Micro clone](http://www.40percent.club/2017/09/green-pro-micro.html) making it unsuitable for split keyboards. This should now be fixed in Rev. B.

## Repo Contents
**/cad** - KiCad source files.  
**/doc** - Schematics, Documentation and Data Sheets (when I create them).  

## License Information
Released under the Creative Commons Attribution Share-Alike 4.0 License.  
https://creativecommons.org/licenses/by-sa/4.0/  

Original Arduino Mini Design by Team Arduino.  
Arduino Pro Mini Design by Spark Fun Electronics.  
Pro Micro Design by Spark Fun Electronics.  
Goldfish Design by Dr Derivative.  
   
## Changes
**Rev. 0** - Initial Design  
**Rev. A** - Changed the footprint of C6 from 0402 to 0603 to reduce component cost by a few cent.  
**Rev. B** - Fixed split keyboard issue described above. Redid parts of the layout to be less messy and remove signal lines from under the crystal.
**Rev. C** - Changed layout of the bottom edge pins to match the Elite-C
