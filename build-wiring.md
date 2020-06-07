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

  background_image:   build/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(218, 91, 197, 0.8) 0%,rgba(151, 27, 191, 0.8) 30%,rgba(2, 8, 212, 0.8) 80%)"

sidebar:
    right:             build
---

## Wiring

{% include alert.html text="Connecting wires incorrectly will destroy electronic components." style="danger" %}

### 1. Power
Use the table below to connect the wires between the **MCU** and the **power bus**.

| Power bus             | MCU  |
|-----------------------|------|
|-                      |GND   |
|+                      |5V    |


### 2. Rotary encoder
Use the table below to connect the wires between the **MCU**, **rotary encoder** and **power bus**.

| Rotary encoder        | Power bus | MCU |
|-----------------------|-----------|-----|
|GND                    |-          |     |
|+                      |+          |     |
|SW                     |           |A3   |
|DT                     |           |A2   |
|CLK                    |           |A1   |

### 3. Display
Use the table below to connect the wires between the **MCU**, **display** and **power bus**. 
The pins of the display are numbered from top to bottom.

| Display               | Power bus  | MCU  |
|-----------------------|------------|------|
|(1) GND                |-           |      |
|(2) VCC                |+           |      |
|(3) SCK                |            |A5    |
|(4) SDA                |            |A4    |

{% include gallery.html 
  gallery="build/wiring/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}