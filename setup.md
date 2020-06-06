---
title:                    Setup
subtitle:                 Download, install, enjoy.
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

  # background_color: "#1B33BF"
  background_image:   setup/header.jpg
  # background_align: center-center     # Image position, Options: center-center, top-center, bottom-center, center-right, center-left
  # background_video:   Working-Space.mp4
  background_overlay: "linear-gradient(to left top,rgba(218, 91, 197, 0.8) 0%,rgba(151, 27, 191, 0.8) 30%,rgba(2, 8, 212, 0.8) 80%)"

sidebar:
    right:             setup
---


# Overview
MaxMix is comprised of two pieces of software, the desktop application and the device firmware, you can download both of them below.

# Desktop app
_It is recommended that you install the desktop application before you plug-in your device for the first time since it will also install the necessary device drivers._

1. Download the application, run the downloaded executable and follow the instructions on the screen.  
2. Plug-in your device now and wait for Windows to recognize it.  
3. Launch the application either from the **start menu** or the **desktop shortcut**.

The application should now be running and in the **windows taskbar**. 

If you purchased the device from the store, it will come with the firmware already installed so you can start using it right away, if not, read below how to install it yourself.

# Firmware
Coming soon.

# Troubleshooting
## Unrecognized device
If you plugged-in the device before installing the application, your device will show as unrecognized in the **Device Manager**.

{% include image.html 
    src="/setup/desk-device-ctrlpanel-nodriver.jpg"
    alt="Alt for image"
    align="center"
    caption="Caption example"
    lightbox="false"
%}

Right click on it and select **Uninstall device** then press **Uninstall** in the dialog.

{% include image.html 
    src="/setup/desk-device-ctrlpanel-uninstall-01.jpg"
    alt="Alt for image"
    align="center"
    caption="Caption example"
    lightbox="false"
%}

{% include image.html 
    src="/setup/desk-device-ctrlpanel-uninstall-02.jpg"
    alt="Alt for image"
    align="center"
    caption="Caption example"
    lightbox="false"
%}

Unplug the device and reboot your computer.
After Windows starts up, plug-in your device again and wait for it to be recognized.
It should now  show up in the **Device Manager** under as **CH340**.

{% include image.html 
    src="/setup/desk-device-ctrlpanel-driver.jpg"
    alt="Alt for image"
    align="center"
    caption="Caption example"
    lightbox="false"
%}