---
width:                    expand        # Options: full, expand, small, xsmall
section:                  large

navbar:
    transparent:          true
    transparent_color:    light

header:
  layout:             1-1            # Options: left, center, 1-1, 1-2, 1-3 or 2-3. Left, right options display this pages title and subtitle. 1-1, 1-2, 1-3 or 2-3 options display content of block file/s.
  color:              light             # Content font color, Options: light, dark
  height:                               # Enable viewport height, Options: full
  header_size:        large            # Only if height disabled
  heading_size:       medium            # Title size, Options: small, medium, large
  parallax:           false              # Enable content parallax, Options: true
  container:          small             # Content width, Options: expand, small, xsmall
  content:
    block:            build-header

  background_image:   build/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(252, 97, 97, 0.8) 0%, rgba(69, 69, 69, 0.8) 80%)"

sidebar:
    right:             build
---

# Wiring

{% include alert.html text="Connecting wires incorrectly will destroy electronic components." style="danger" %}

## MCU
Use the table below to connect the wires between the **MCU** and the **power bus**.

| MCU             | Power bus  |
|-----------------|------------|
|GND              |-           |
|5V               |+           |

{% include gallery.html 
  gallery="build/wiring/mcu"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## Rotary encoder
Use the table below to connect the wires between the **MCU**, **rotary encoder** and **power bus**.

| Rotary encoder        | Power bus | MCU |
|-----------------------|-----------|-----|
|GND                    |-          |     |
|+                      |+          |     |
|SW                     |           |A3   |
|DT                     |           |A2   |
|CLK                    |           |A1   |

{% include gallery.html 
  gallery="build/wiring/rotary"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## Display
Use the table below to connect the wires between the **MCU**, **display** and **power bus**. 
The pins of the display are numbered from top to bottom.

| Display               | Power bus  | MCU  |
|-----------------------|------------|------|
|(1) GND                |-           |      |
|(2) VCC                |+           |      |
|(3) SCK                |            |A5    |
|(4) SDA                |            |A4    |

{% include gallery.html 
  gallery="build/wiring/display"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## LED Ring (Optional)
Use the table below to connect the wires between the **LED ring**, **MCU** and **power bus**. 
The pins of the display are numbered from top to bottom.

| LED Ring              | Power bus  | MCU  |
|-----------------------|------------|------|
|GND                    |-           |      |
|VCC                    |+           |      |
|DI                     |            |D12   |

{% include gallery.html 
  gallery="build/wiring/led-ring"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}