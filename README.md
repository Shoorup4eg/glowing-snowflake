# Glowing SnowFlake

A large glowing snowflake (diameter 31cm). One universal PCB. Simple assembly, simple setup. Great variability in the use of components. Recommended black textolite with white color mask for better visual effect. 

Scheme of the project

<a href="https://github.com/Shoorup4eg/glowing-snowflake/blob/master/snowflake_sheme.png"><img src="https://github.com/tShoorup4eg/glowing-snowflake/blob/master/snowflake_sheme.png"  align="left" height="710" width="888"></a>

View of the top side of PCB

<a href="https://github.com/Shoorup4eg/glowing-snowflake/blob/master/top-view.png"><img src="https://github.com/Shoorup4eg/glowing-snowflake/blob/master/top-view.png"></a>


## COMPONENTS
Option 1

1) Module esp-07 or esp-12e or esp-12f 1pcs
2) LED ws2812b ws2812 ws2811 SK6812 68pcs
3) smd capacitor 1206 or smd 0805 or 0603 with a nominal value of 47 to 220nF 68pcs (you can not install)
4) smd resistor 1206 or smd 0805 nominal from 10 to 100 Ohm 1pc
5) resistor smd 1206 or smd 0805 nominal from 4.7 to 10 kOhm 5pcs
6) ldo stabilizer lm1117-3.3 or similar 1pc
7) Capacitor C1 any electrolytic or tantalum with a capacity of 100 to 470 microfarads and an operating voltage of at least 6.3V 1pcs
8) Capacitor C2 any tantalum or ceramic with a capacity of 10 to 220 microfarad and an operating voltage of at least 6.3V 1pc
9) dupont block for 5 contacts 2.54mm 1pc (soldering wires can be used)
10) 1pc dc-005 power connector (solder wires can be used)
11) Clock button, any suitable 1pc (you can not install) 1pc
Resistor R2 is not installed!

Option 2

1) Module wemos (lolin) d1 mini (any version) 1pc
2) LED ws2812b ws2812 ws2811 SK6812 68pcs
3) smd capacitor 1206 or smd 0805 or 0603 with a nominal value of 47 to 220nF 68pcs (you can not install)
4) smd resistor 1206 or smd 0805 nominal from 10 to 100 Ohm 1pc
5) smd resistor 1206 or smd 0805 with nominal 0 Ohm 1pc
6) Capacitor C1 any electrolytic or tantalum with a capacity of from 100 to 470 microfarad and operating voltage of at least 6.3V 1pc
7) Clock button any suitable 1pc (you can not install) 1pc
8) resistor smd 1206 or smd 0805 nominal from 4.7 to 10 kOhm 1pc
9) 1pc dc-005 power connector (can not be installed when powered by microUSB)

## TECHNICAL DETAILS
A 5v 2a (MINIMUM) power supply is required to power the device.

## BUILD RECOMMENDATIONS
First solder all the necessary smd resistors and capacitors in accordance with the selected option. Then solder the rest of the necessary elements and lastly solder the ws2812 LEDs.
