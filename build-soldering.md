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

[part-conductive-glue]: https://www.aliexpress.com/item/4000805311240.html?spm=a2g0s.9042311.0.0.3c5d4c4dnGoHMw

# Soldering
Soldering has been kept down to a minimum but some is required.  
If you are unable to solder, you can try alternative methods such as [conductive glue](part-conductive-glue).

## 3. MCU
1. Take one of the long strip of pins that came with the MCU.
2. Insert the first pin in D13 and last in VIN, with the longer sides are pointing up.
3. Take the remaining strip of pins and break apart 5 of them.
4. Insert it on the opposite side so the first pin is in D12 and last in D8.
5. Turn the MCU with the pins upside down and solder the pins from the bottom.

{% include gallery.html 
  gallery="build/soldering/mcu/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 5. LED Ring (Optional)
1. Take 3 of the jumper wires.
2. Using the wire cutters, cut the connectors from one end and strip the wires.
3. Use the soldering iron to tin the stripped ends of the wires.
4. On the LED ring, tin the pcb connections labeled **DI**, **5V** and **GND**.
5. Solder the wires to the pcb.

{% include gallery.html 
  gallery="build/soldering/led-ring/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}