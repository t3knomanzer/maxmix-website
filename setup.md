---
title: Setup
subtitle: Download, install, enjoy!
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
  parallax:           true              # Enable content parallax, Options: true
  container:          small             # Content width, Options: expand, small, xsmall

  background_image:   setup/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(218, 91, 197, 0.8) 0%,rgba(151, 27, 191, 0.8) 30%,rgba(2, 8, 212, 0.8) 80%)"

sidebar:
    right:             setup
---


# Overview
MaxMix is comprised of two pieces of software, the application running on your desktop computer and the firmware running on the device.
Installation is very straight forward but just in case, below are step by step instructions.

# Requirements
- A computer running **Windows 10**.
- An available USB 2.0 or greater port.
- A maxmix device.

# Desktop Application
{% include alert.html text="It is recommended that you install the desktop application before you plug-in your device for the first time." style="primary" %}

1. Download the latest version of the [desktop application](/maxmix/). 
2. Double click on the installer and follow the instructions on the screen.
3. Plug-in your device now and wait for Windows to recognize it.  
4. Launch the application either from the Windows start menu or the shortcut on your desktop.

The application should now be running and you should see the maxmix icon in the **windows taskbar**. 
You can double-click or right click on the icon to access the application.

# Firmware
{% include alert.html text="Make sure the maxmix device is plugged in." style="primary" %}

1. Launch the **Firmware Installer** from the shortcut on your desktop or in the Windows start menu.
2. Confirm that the COM port selected on the drop-down is the correct one.
3. Press install and wait for the installation to complete.


{% include faqs.html 
  multiple="false" 
  category="setup" 
  section_title="Troubleshoot" 
  section_size="large"
  section_background="default"
  section_container="xsmall"
  section_header_align="center"
%}

