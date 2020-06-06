---
title:                    Contact Us
subtitle:                 What's on your mind?
width:                    xsmall          # Options: full, expand, small, xsmall
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
  background_image:   contact/header.jpg
  # background_align: center-center     # Image position, Options: center-center, top-center, bottom-center, center-right, center-left
  # background_video:   Working-Space.mp4
  background_overlay: "linear-gradient(to left top,rgba(218, 91, 197, 0.8) 0%,rgba(151, 27, 191, 0.8) 30%,rgba(2, 8, 212, 0.8) 80%)"
---


# Overview
{% include formspree.html email="my_name@gmail.com" redirect="/thanks/" name="true" subject="true" layout="horizontal" %}