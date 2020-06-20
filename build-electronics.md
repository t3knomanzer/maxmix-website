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

# Electronics
Grab all the electronic components, the M2x5mm screws and a small philips head screw-driver.

## 1. Display
1. Grab the OLED display and the top part of the enclosure.
2. Insert the bottom of the display first and then push on the top until it is secured in place. If needed, push on the the front wall of the enclosure to help the display slide in.
3. Drop the P-shaped tab in place and secure it with the screw.

{% include gallery.html 
  gallery="build/electronics/display/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 2. Rotary encoder
1. Grab the rotary encoder and bottom part of the enclosure.
2. Place the encoder in the center, lining up the holes.
3. Secure it using the 2 screws.

{% include gallery.html 
  gallery="build/electronics/rotary/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 3. MCU
1. Grab the MCU and bottom part of the enclosure.
2. Insert the USB connector of the MCU into the opening at the back of the enclosure.
3. Drop the flat tab in place and secure it with a screw.

{% include gallery.html 
  gallery="build/electronics/mcu/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 4. Power bus
1. Grab the power-bus and the bottom part of the enclosure.
2. Place the power-bus on the right hand side, lining up the holes.
4. Secure it in place using the screws.

{% include gallery.html 
  gallery="build/electronics/power-bus/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 5. LED Ring (Optional)
{% include alert.html text="The fit of the parts is designed to be very tight. Some sanding of the PCB holes may be required." style="primary" %}

1. Grab the ring holder 3D printed part.
2. Line up the pegs with the holes of the PCB, making sure that the notch in the holder is facing away from the wires.
3. Apply some pressure to insert the pegs into the holes until it sits flush.

{% include gallery.html 
  gallery="build/electronics/led-ring/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}