---
width:                full              # Options: full, expand, small, xsmall

navbar:
    transparent:          true
    transparent_color:    light

header:
  layout:             1-1               # Options: left, center, 1-1, 1-2, 1-3 or 2-3. Left, right options display this pages title and subtitle. 1-1, 1-2, 1-3 or 2-3 options display content of block file/s.
  color:              light             # Content font color, Options: light, dark
  height:             full              # Enable viewport height, Options: full
  header_size:        large             # Only if height disabled
  heading_size:       medium            # Title size, Options: small, medium, large
  parallax:           true              # Enable content parallax, Options: true
  container:          small             # Content width, Options: expand, small, xsmall
  content:                              # Source block file for first column if layout set to 1-1, 1-2, 1-3 or 2-3
    block:            home-header       # Reference block file e.g. for _blocks/header-one.md enter header-one

  # background_video:   /home/header.mp4
  background_image:   /home/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(252, 97, 97, 0.8) 0%, rgba(69, 69, 69, 0.8) 80%)"
---

[comment]: # (This actually is the most platform independent comment)

{% if site.template == 'base' %}

  {% include cards.html     
    block="home-pillar" 
    grid="1-4"
    media="top"
    icon_color="#FC6161"
    gutter="large"
    card_style="default"
    section_background="default" 
    section_size="medium"
    section_title=""
    section_header_align="center"
    section_content_align="center"
  %}

  {% include cards.html 
    block="home-card-10" 
    media="left"
    section_size="small"
    section_background="default"
    card_style="default"
  %}

  {% include cards.html 
    block="home-card-20" 
    media="right"
    section_size="small"
    section_background="default"
    card_style="default"
  %}

  {% include cards.html 
    block="home-card-30" 
    media="left"
    section_size="small"
    section_background="default"
    card_style="default"
  %}

  {% include gallery.html 
    gallery="home/product/"
    grid="1-4"
    gutter="small"
    caption="false"
    lightbox="true"

    section_background="default" 
    section_size="small"
    section_title="" 
    section_header_align="center"
    section_content_align="center"
  %}

  {% include blog.html 
    grid="1-3"
    gutter="large"
    count="3"
    view_all="/blog/"

    section_background="default" 
    section_size="small"
    section_title="" 
    section_header_align="center"
    section_content_align="center"
  %}

{% else %}


{% endif %}