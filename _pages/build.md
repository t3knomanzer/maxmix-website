---
title: Build
subtitle: MaxMix has  been designed to be easy and fun to build. 
description: MaxMix device build instructions.
featured_image: /images/build/header.jpg
---

## Overview
The device is uses a combination of 3D printed parts and off the shelf electronic components.  
There are many ways to get your own MaxMix, pick the one that suits you best.

Follow the instructions to build it yourself or simply order it from the [store]().

## Part List

### Enclosure
The device is made up of a few 3D printed parts.  
The top of the enclosure, the bottom, the knob, the ring, the display and the MCU tabs.  

Part files and printing instructions can be downloaded from [Thingiverse](https://www.thingiverse.com/thing:4343186).
  
Additionally, you will need:
- 4x [M2 Countersink screws]()
- 4x [M3 screws]()
- 2x [M3 screws]()

<div class="gallery" data-columns="1">
    <img src="images/build/parts-all.jpg">
	<img src="images/build/parts-top.jpg">
	<img src="images/build/parts-bottom.jpg">
    <img src="images/build/parts-knob.jpg">
    <img src="images/build/parts-ring.jpg">
    <img src="images/build/parts-tab.jpg">
</div>


### Electronics
There are four electronic components needed that can easily be found online.
- [Arduino Pro Micro]()
- [OLED display]()
- [Rotary encoder]()
- [Power bus]()
- 11x [Female to Female Jumper Wires (10cm)](https://www.amazon.com/GenBasic-Piece-Female-Jumper-Wires/dp/B077N58HFK/ref=sr_1_4?dchild=1&keywords=female%2Bto%2Bfemale%2Bjumper%2Bwire&qid=1589242995&s=electronics&sr=1-4&th=1)

<div class="gallery" data-columns="1">
    <img src="images/build/elec-all.jpg">
	<img src="images/build/elec-mcu.jpg">
	<img src="images/build/elec-display.jpg">
    <img src="images/build/elec-rotary.jpg">
    <img src="images/build/elec-bus.jpg">
</div>

## Instructions
Once you have all the parts ready, it's time to put it together.

### 1. Display
1. Grab the top of the enclosure, the display, one of the tabs and a M3 screw.  
2. Place the display in the opening with the pins on the right.
3. Secure it using the tab and the screw.

![](images/build/ass-display.jpg)

### 2. Rotary encoder
1. Grab the bottom of the enclosure, the rotary encoder and 2 M4 screws.
2. Place the rotary encoder with the pins facing the back.
3. Secure it to the base using the 2 screws.

![](images/build/ass-rotary.jpg)

### 3. MCU
1. Grab the MCU, the remaining tab and a M3 screw.
2. Insert the USB connector of the MCU into the opening.
3. Secure it in place using the tab and screw.

![](images/build/ass-mcu.jpg)

### 4. Power bus
1. Grab the power splitter and 2 M3 screws.
2. Place the power splitter in the right location as shown below.
3. Secure in place using the screws.

![](images/build/ass-bus.jpg)

### 4. Wiring

**Warning:** _Connecting wires incorrectly will damage electronic components._

### 1. Power
Use the table below to connect the wires between the **MCU** and the **power bus**.

| Power bus             | MCU  |
|-----------------------|------|
|GND                    |GND   |
|+                      |5V    |


### 2. Rotary encoder
Use the table below to connect the wires between the **MCU**, **rotary encoder** and **power bus**.

| Rotary encoder        | Power bus | MCU |
|-----------------------|-----------|-----|
|GND                    |GND        |     |
|+                      |5V         |     |
|SW                     |           |D4   |
|DT                     |           |D3   |
|CLK                    |           |D2   |

### 3. Display
Use the table below to connect the wires between the **MCU**, **display** and **power bus**.
The pins of the display are numbered from top to bottom.

| Display               | Power bus  | MCU  |
|-----------------------|------------|------|
|(1) GND                |GND         |      |
|(2) VCC                |5V          |      |
|(3) SCL                |            |A5    |
|(4) SCA                |            |A4    |

![](images/build/wir-all.jpg)

## Assembly
1. Grab the ring and place it it on the top of the enclosure, aligning the notches on the sides and making sure that the extra notch is facing the display.
2. Bring the top and bottom parts together until they snap in place.
3. Slide the knob on the shaft of the rotary encoder.
4. Turn it upside down and use the 4 countersink screws to secure the two halves together.
5. Place the 4 rubber feet on top of the screw holes.

<div class="gallery" data-columns="1">
    <img src="images/build/ass-ring.jpg">
	<img src="images/build/ass-snap.jpg">
	<img src="images/build/ass-bottom.jpg">
    <img src="images/build/ass-feet.jpg">
</div>