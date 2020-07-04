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

[part-conductive-glue]: https://www.aliexpress.com/item/4000805311240.html?spm=a2g0s.9042311.0.0.3c5d4c4dnGoHMw

# Soldering
Soldering has been kept down to a minimum but some is required.  
If you are unable to solder, you can try alternative methods such as [conductive glue](part-conductive-glue).

## 3. MCU
1. Locate the side that has pins D13 through VIN.
2. Insert a row of pins them from the top so shorter ends are poking through the back.
3. Solder the pins from below.
5. Use the needle nose pliers top break apart 5 pins from the remaining row.
6. Insert them in the MCU between pins D12 and D8.
7. Solder them from below.

{% include gallery.html 
  gallery="build/soldering/mcu/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 5. LED Ring (Optional)
1. Grab 3 of the jumper wires.
2. Using the wire cutters, cut the connectors from one end and strip the wires.
3. Use the soldering iron to tin the stripped ends.
4. Tin the pcb connections of the LED ring labeled **DI**, **5V** and **GND**.
5. Solder the wires to the pcb.

{% include gallery.html 
  gallery="build/soldering/led-ring/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}