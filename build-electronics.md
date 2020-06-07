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

# Electronics
Grab all the electronic components, the M2x5mm screws and a small philips head screw-driver.

## 1. Display
1. Place the top side of the enclosure on the table so that you can see through the hole for the display.
2. Grab de display so that the pins are facing towards you and on the right hand side.
3. Insert the bottom of the display first and then push on the top until it is secured in place. The fit for the display is very tight, be careful not to crack the screen.
4. Drop the tab in place and secure it with the screw.

{% include gallery.html 
  gallery="build/electronics/display/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 2. Rotary encoder
1. Place the bottom of the enclosure on the table with the usb hole facing away from you.
2. Locate the 2 stands with holes in the center of the base.
3. Placew the rotary encoder with the pins facing away from you and line up the holes with the base.
4. Secure it using the 2 screws.

{% include gallery.html 
  gallery="build/electronics/rotary/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 3. MCU
1. Insert the USB connector of the MCU into the opening at the back of the bottom part of the enclosure.
2. Secure it in place using the remaining tab and screw.

{% include gallery.html 
  gallery="build/electronics/mcu/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## 4. Power bus
1. Locate the 2 stands with holes, on the right hand side of the bottom part of the enclosure.
2. Place the power splitter and line up the holes.
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
3. Apply some pressure to inser the pegs into the holes until it sits flush.

{% include gallery.html 
  gallery="build/electronics/led-ring/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}