---
title:                    Use
subtitle:                 Let's get the party started.

width:                    expand        # Options: full, expand, small, xsmall

navbar:
    transparent:          true
    transparent_color:    light

header:
  layout:             center            # Options: left, center, 1-1, 1-2, 1-3 or 2-3. Left, right options display this pages title and subtitle. 1-1, 1-2, 1-3 or 2-3 options display content of block file/s.
  color:              light             # Content font color, Options: light, dark
  height:                               # Enable viewport height, Options: full
  header_size:        xlarge            # Only if height disabled
  heading_size:       medium            # Title size, Options: small, medium, large
  parallax:           false             # Enable content parallax, Options: true
  container:          small             # Content width, Options: expand, small, xsmall

  background_image:   use/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(252, 97, 97, 0.8) 0%, rgba(69, 69, 69, 0.8) 80%)"

sidebar:
    right:             use
---

# Quick Start (1.3.x)

You've built your controller and installed the software. It's time to start using it!

## Actions
The Maxmix controller supports 4 different actions, **tap**, **double tap**, **hold** and **rotate**.

**Tap** is when you press and release the button once.  
It is used to cycle through the different screens of the current mode.  

**Double tap**, when you **tap** the button twice quickly.   
It will perform a special action, specific to each mode.  

**Hold**, when you press the button and hold it down for 1 second.  
Used to cycle through the different modes available.  

**Rotate**, can be either clockwise or counter-clockwise.   
To increase or decrease the selected value.  

## Modes
Maxmix has a few different modes of operation, each mode is designed and optimized for a particular use case.  
The modes available as well as the current mode selected can be seen at the bottom of the screen.
{% include image.html 
    src="use/ui_modes_overlay_01.jpg"
    alt="Maxmix modes ui control"
    align="center"
    caption=""
%}

### Output Mode
Gives you full control over output devices such as headphones or speakers.
There are 2 screens available, select and edit.

In **edit screen**, **rotate** the knob to turn up and down the master volume of your pc or **double-tap** to mute/unmute.

{% include image.html 
    src="use/ui_out_edit.jpg"
    alt="Maxmix output mode edit"
    align="center"
    caption=""
%}

**Tap** once to enter the **selection screen**.  

Here you can **rotate** the knob to cycle through all output devices available and **tap** to swith your sound
to the selected device. i.e: switching your music from headphones to speakers.  

The hash symbol on the left hand side indicates the currently active device.  

{% include image.html 
    src="use/ui_out_select.jpg"
    alt="Maxmix output mode select"
    align="center"
    caption=""
%}

{% include image.html 
    src="use/ui_default_device_overlay.jpg"
    alt="Maxmix default device overlay"
    align="center"
    caption=""
%}

### Input Mode
Just like output mode, input mode allows you to switch, adjust volume and toggle mute of your input devices.

### Application Mode
This mode is built for those wanting more granular control, allowing you to adjust the volume of each application individually.

It consists of 2 screens, the select screen and the edit screen.

In the **select screen** you can **rotate** to cycle through all applications running on your pc.  
Once you find the application you'd like to edit, **tap** to go to the **edit screen**.

{% include image.html 
    src="use/ui_modes_app_select_01.jpg"
    alt="Maxmix app mode select screen"
    align="center"
    caption=""
%}

In the **edit screen**, **rotate** to adjust the volume of the application or **double tap** to mute/unmute.

{% include image.html 
    src="use/ui_modes_app_edit_01.jpg"
    alt="Maxmix app mode edit screen"
    align="center"
    caption=""
%}

### Mix Mode
Allows you to assign an application to each one of the 2 channels available. Once assigned, **rotating** will increase the volume of one while decreasing the other one at the same time.

It consists of 3 screens, **select screen a**, **select screen b** and **edit screen**.  
You can identify the current selection screen is indicated by the letter **A** or **B** on the left hand side of the screen.

{% include image.html 
    src="use/ui_modes_game_overlay_01.jpg"
    alt="Maxmix game mode select a screen"
    align="center"
    caption=""
%}

{% include image.html 
    src="use/ui_modes_game_overlay_02.jpg"
    alt="Maxmix game mode select a screen"
    align="center"
    caption=""
%}

Select application **A**, **tap**, select **B** and **tap** to enter the **edit screen**.  

Once you are in **edit screen**, **double tap** to set the volume of both applications to 50%. **Rotate** clockwise to increase application **A** while decreasing **B** or viceversa.

{% include image.html 
    src="use/ui_modes_game_edit_01.jpg"
    alt="Maxmix app mode edit screen"
    align="center"
    caption=""
%}