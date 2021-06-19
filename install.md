---
width:                    expand        # Options: full, expand, small, xsmall

navbar:
    transparent:          true
    transparent_color:    light

header:
  layout:             1-1               # Options: left, center, 1-1, 1-2, 1-3 or 2-3. Left, right options display this pages title and subtitle. 1-1, 1-2, 1-3 or 2-3 options display content of block file/s.
  color:              light             # Content font color, Options: light, dark
  height:                               # Enable viewport height, Options: full
  header_size:        large             # Only if height disabled
  heading_size:       medium            # Title size, Options: small, medium, large
  parallax:           false              # Enable content parallax, Options: true
  container:          small             # Content width, Options: expand, small, xsmall
  content:
    block:            install-header

  background_image:   install/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(252, 97, 97, 0.8) 0%, rgba(69, 69, 69, 0.8) 80%)"

sidebar:
    right:             install
---


# Overview
Installation of the software is very straight forward but we are providing step by step instructions just in case.

# Requirements
- A computer running **Windows 10**.
- An available USB 2.0 or greater port.
- A Maxmix device.

# Desktop Application
{% include alert.html text="It is recommended that you install the desktop application before you plug-in your device for the first time." %}

1. Download the latest version of the desktop application. 
2. Double click on the installer and follow the instructions on the screen.
3. Plug-in your device now and wait for Windows to recognize it.  
4. Launch the application either from the Windows start menu or the shortcut on your desktop.

The application should now be running and you should see the Maxmix icon in the **windows taskbar**. 
You can double-click or right click on the icon to access the application.

# Firmware
{% include alert.html text="Make sure the Maxmix device is plugged in and the Maxmix application is closed." %}

1. Launch the **Firmware Installer** from the shortcut on your desktop or in the Windows start menu.
2. Confirm that the COM port selected on the drop-down is the correct one.
3. Press install and wait for the installation to complete.

# Troubleshoot / USB Driver
If your device shows as unrecognized in **Windows Device Manager** with yellow a warning sign as shown in the picture below, the communication between the device and the computer won't work. You can try one of the following fixes.

{% include image.html 
    src="install/desk-device-ctrlpanel-nodriver.jpg"
    alt="desk-device-ctrlpanel-nodriver"
    align=""
    lightbox="false"
%}

### Attempt to automatically reinstall the USB driver.
1. In **Windows Device Manager** locate the device, right click on it and select **Uninstall device** then press **Uninstall** in the dialog.
2. Unplug the device and reboot your computer.
3. After Windows starts up, plug-in your device again and wait for it to be recognized. It should now show up in **Windows Device Manager** as **CH340**.

### Install the USB driver manually.
If your nano is still showing as an unrecognized device, it's probably because it uses a chinese clone of the FTDI USB chip which unfortunately does not work with the automatic driver finding functionality in Windows. So you will have to install the driver yourself.

1. Unplug the device. 
2. Download the [CH341SER.zip](/uploads/CH341SER.zip) archize, unzip it to a known location then double click on **SETUP.EXE**.
3. When prompted click **Install**. Once completed, close the installer. 
4. Open **Windows Device Manager**
5. Plug the device, it should now appears in Ports (COM & LPT) has **USB-SERIAL CH340**. If it's still undetected, try to reboot your computer and check again.
6. You can now delete the unzipped install folder.

{% include image.html 
    src="install/desk-device-ctrlpanel-driver.jpg"
    alt="desk-device-ctrlpanel-nodriver"
    align=""
    lightbox="false"
%}


