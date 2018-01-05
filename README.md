# Goldfish
The goldfish is a Pro Micro compatible microcontroller designed for use in Mechanical Keyboards, although it is perfectly suited for any hobby electronics project.
It is based on the same ATMega32U4 IC as regular Pro Micros so it can be programmed with the Arduino IDE, or keyboard firmwares like TMK, QMK, etc.

## Advantages
* Through-hole USB connector breaks a lot less easily.
* USB-C with it's reversibility and all-around coolness.
* Pin-compatible with Pro Micros.
* Five extra pins available along the bottom edge of the board for larger hand-wired builds.
* USB data lines are easily accessible through two internal pins.
* Mid-mounted USB-C connector allows for thinner keyboard designs.

## Disadvantages
* Fewer custom cable options compared to USB Mini-B/Micro-B.
* More expensive (how much exactly depends greatly on quantity ordered of course).
* No onboard voltage regulator (won't make a difference for keyboards, can be an issue for other electronics projects where supplies >5.5V are used).

## Known Issues
* Rev. 0 and A both suffer from the same issue as the [green Pro Micro clone](http://www.40percent.club/2017/09/green-pro-micro.html) making it unsuitable for split keyboards. This will be fixed in Rev. B.

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
