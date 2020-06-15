---
title:                    Contribute
subtitle:                 Let's build it together!
width:                    full        # Options: full, expand, small, xsmall
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

  background_image:   contribute/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(218, 91, 197, 0.8) 0%,rgba(151, 27, 191, 0.8) 30%,rgba(2, 8, 212, 0.8) 80%)"

---

{% include cards.html 
  block="contribute-area"
  grid="1-2"

  section_size="large"
  section_background="default"
  section_header_align="center"
  section_content_align="center"
%}