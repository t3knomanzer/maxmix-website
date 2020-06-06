---
title: Unrecognized device
categories: [setup]
---

If you plugged-in the device before installing the application, your device will show as unrecognized in **Windows Device Manager**, like in the picture below.

{% include image.html 
    src="/setup/desk-device-ctrlpanel-nodriver.jpg"
    alt="desk-device-ctrlpanel-nodriver"
    align=""
    lightbox="false"
%}

To fix it follow these easy steps:
1. Right click on it and select **Uninstall device** then press **Uninstall** in the dialog.
2. Unplug the device and reboot your computer.
3. After Windows starts up, plug-in your device again and wait for it to be recognized. It should now  show up in **Windows Device Manager** as **CH340**, like in the picure below.

{% include image.html 
    src="/setup/desk-device-ctrlpanel-driver.jpg"
    alt="desk-device-ctrlpanel-driver"
    align=""
    lightbox="false"
%}