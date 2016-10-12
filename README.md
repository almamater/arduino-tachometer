Arduino car tachometer
==============

Introduction
----
I'm currently driving an old Opel Astra without tachometer. I had a spare arduino and few LEDs, so I made a simple tachometer. I started by cut a 5cm x 1.5cm piece of an old credit cart, drilled 4 holes in it, painted it black and glued 4 LED diods to it. Then I soldered a 220ohm resistors to each positive LED pin and used a common ground. I connected them to arduino via 5x30cm jumpers and hid the arduino in a hole under the wheel. I connected the arduino data pin via voltage divider to the signal pin of the coil and used an old phone charger to power the arduino. In order to work I shared the phone charger and arduino's grounds.

Demo
----
To be included...

Schematic
----
![Schematic](https://raw.githubusercontent.com/deepsyx/arduino-tachometer/master/Schematic.png)

Code
----
Check out the `code.cpp` file.

Materials
----
- Arduino Uno
- 4x LEDs
- 5x 220ohm resistor
- 1x 160ohm resistor
- 10x 30cm jumpers
- Old car phone charger
- Longer wire to connect to coil
- 1amp fuse (not included in schematics)

Future plans
----
- Add more LEDs
- Log data (to phone or sd card) for analysis
- Connect to phone and draw a graphic
