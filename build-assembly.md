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

# Assembly
1. Pass the shaft of the rotary encoder through the ring. Make sure that the little tab on the front of the encoder lines up with the notch on the bottom side of the ring and that it sits flush.
2. Pre-bend and organize the wires so they are out of the way.
3. Bring the top and bottom parts together until they snap in place.
4. Take a look at the ring from the top and make sure it sits flush with the top part of the enclosure. If needed, push on the bottom part of the enclosure until it fits in place.
5. Slide the knob on the shaft of the rotary encoder.
6. Turn it upside down and use the 4 countersink screws to secure the two halves together.
7. Place the silicon-bumpers on top of the the screws. 

{% include gallery.html 
  gallery="build/assembly/"
  grid="1-4"
  gutter="small"
  caption="true"
  lightbox="true"
%}

## Congratulations
Congratulations you have completed the build!

You now have your very own Maxmix controller.   
Go to the [install](/install/) section and follow the instructions to get the software setup.
