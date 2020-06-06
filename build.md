---
title:                    Build
subtitle:                 MaxMix has been designed to be easy and fun to build.
width:                    expand        # Options: full, expand, small, xsmall
section:                  large

navbar:
    transparent:          true
    transparent_color:    light

header:
  layout:             center            # Options: left, center, 1-1, 1-2, 1-3 or 2-3. Left, right options display this pages title and subtitle. 1-1, 1-2, 1-3 or 2-3 options display content of block file/s.
  color:              light             # Content font color, Options: light, dark
  height:                               # Enable viewport height, Options: full
  header_size:        xlarge            # Only if height disabled
  heading_size:       medium            # Title size, Options: small, medium, large
  parallax:           true              # Enable content parallax, Options: true
  container:          small             # Content width, Options: expand, small, xsmall

  # background_color: "#1B33BF"
  background_image:   build/header.jpg
  # background_align: center-center     # Image position, Options: center-center, top-center, bottom-center, center-right, center-left
  # background_video:   Working-Space.mp4
  background_overlay: "linear-gradient(to left top,rgba(218, 91, 197, 0.8) 0%,rgba(151, 27, 191, 0.8) 30%,rgba(2, 8, 212, 0.8) 80%)"

sidebar:
    right:             build
---

[power-bus]:https://www.aliexpress.com/item/33007031908.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA
[display]:https://www.aliexpress.com/item/32861875681.html?spm=a2g0o.productlist.0.0.40103137cSuJWL&algo_pvid=72a2cf65-9a42-4ea4-acc1-12d0c207044d&algo_expid=72a2cf65-9a42-4ea4-acc1-12d0c207044d-3&btsid=0ab6d59515893349825181599eeff5&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_
[mcu]:https://www.aliexpress.com/item/32856118319.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA
[rotary]:https://www.aliexpress.com/item/1000001872933.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA
[m2-5mm]:https://www.aliexpress.com/item/32975410255.html?spm=a2g0o.detail.0.0.496572dbSutw9Y&gps-id=pcDetailCartBuyAlsoBuy&scm=1007.12908.131176.0&scm_id=1007.12908.131176.0&scm-url=1007.12908.131176.0&pvid=ff23c9a7-d73c-454f-a4c6-322a121bd814&_t=gps-id:pcDetailCartBuyAlsoBuy,scm-url:1007.12908.131176.0,pvid:ff23c9a7-d73c-454f-a4c6-322a121bd814,tpp_buckets:668%230%23131923%2319_668%23808%235965%23251_668%23888%233325%2311_668%232846%238111%23466_668%232717%237566%23817
[m2-10mm]:https://www.aliexpress.com/item/33043091484.html?spm=a2g0o.productlist.0.0.767f4a08gAx7Oc&s=p&ad_pvid=2020051218463417005721656175370016165454_11&algo_pvid=9e1a1b86-9322-441f-b087-ef567c376f63&algo_expid=9e1a1b86-9322-441f-b087-ef567c376f63-10&btsid=0ab6d69f15893343947923488e699c&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_
[jumper-wires]:https://www.aliexpress.com/item/33007698478.html?spm=a2g0o.productlist.0.0.44b248d7kcLfV9&algo_pvid=b0a90a38-c903-4828-9cf3-0073b86684ae&algo_expid=b0a90a38-c903-4828-9cf3-0073b86684ae-6&btsid=0ab6d67915893355772902177e0543&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_
[bumpers]:https://www.aliexpress.com/item/32289191938.html?spm=a2g0o.productlist.0.0.20513e1cJD6rV0&s=p&ad_pvid=2020051219254812188693811548200016292927_1&algo_pvid=f58a6173-19a8-4de7-9dbb-819984df4870&algo_expid=f58a6173-19a8-4de7-9dbb-819984df4870-0&btsid=0ab50f6115893367485698071ebd11&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

## Overview
The device is uses a combination of 3D printed parts and off the shelf electronic components.  
There are many ways to get your own MaxMix, pick the one that suits you best.

Soldering is only required for the header pins of the MCU.

Follow the instructions to build it yourself or simply order it from the [store]().

## Part List
All links provided for the parts below are subject to availability. When looking for alternatives,  make sure the part specifications match.  

Total cost is about **$13.00 USD**.   
_Does not include 3D printed parts_.

### Enclosure
The device is made up of a few 3D printed parts.  
The top of the enclosure, the bottom, the knob, the ring, the display and the MCU tabs.  

Part files and printing instructions can be downloaded from [Thingiverse](https://www.thingiverse.com/thing:4343186).
  
Additionally, you will need:
- 4x [M2 10mm Countersink screws][m2-10mm]
- 6x [M2 5mm screws][m2-5mm]
- 4x [Silicon bumper 2mmx8mm][bumpers]

{% include gallery.html 
  gallery="build/parts/"
  grid="1-4"
  gutter="small"
  caption="true"
  lightbox="true"
%}


### Electronics
There are four electronic components needed that can easily be found online.
- 1x [Arduino Nano 328P CH340][mcu]
- 1x [128x32 I2C OLED display][display]
- 1x [Rotary encoder][rotary]
- 1x [Power bus][power-bus]
- 11x [Female to Female Jumper Wires (10cm)][jumper-wires]

{% include gallery.html 
  gallery="build/electronics/"
  grid="1-4"
  gutter="small"
  caption="true"
  lightbox="true"
%}

## Instructions
Once you have all the parts ready, it's time to put it together.

### 1. Display
1. Grab the top of the enclosure, the display, one of the tabs and a M3 screw.  
2. Place the display in the opening with the pins on the right.
3. Secure it using the tab and the screw.

{% include image.html 
	src="/build/assembly/ass-display.jpg"
    alt="Alt for image"
    align="right"
    caption="Caption example"
    lightbox="false"
%}

### 2. Rotary encoder
1. Grab the bottom of the enclosure, the rotary encoder and 2 M4 screws.
2. Place the rotary encoder with the pins facing the back.
3. Secure it to the base using the 2 screws.

{% include image.html 
	src="/build/assembly/ass-rotary.jpg"
    alt="Alt for image"
    align="right"
    caption="Caption example"
    lightbox="false"
%}

### 3. MCU
1. Grab the MCU, the remaining tab and a M3 screw.
2. Insert the USB connector of the MCU into the opening.
3. Secure it in place using the tab and screw.

{% include image.html 
	src="/build/assembly/ass-mcu.jpg"
    alt="Alt for image"
    align="right"
    caption="Caption example"
    lightbox="false"
%}

### 4. Power bus
1. Grab the power splitter and 2 M3 screws.
2. Place the power splitter in the right location as shown below.
3. Secure in place using the screws.

{% include image.html 
    src="/build/assembly/ass-bus.jpg"
    alt="Alt for image"
    align="right"
    caption="Caption example"
    lightbox="false"
%}

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

{% include image.html 
    src="/build/wiring/wir-all.jpg"
    alt="Alt for image"
    align="right"
    caption="Caption example"
    lightbox="false"
%}

## Assembly
1. Grab the ring and place it it on the top of the enclosure, aligning the notches on the sides and making sure that the extra notch is facing the display.
2. Bring the top and bottom parts together until they snap in place.
3. Slide the knob on the shaft of the rotary encoder.
4. Turn it upside down and use the 4 countersink screws to secure the two halves together.

{% include gallery.html 
  gallery="build/assembly/"
  grid="1-4"
  gutter="small"
  caption="true"
  lightbox="true"
%}