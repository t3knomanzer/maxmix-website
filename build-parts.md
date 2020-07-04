---
title:                    Build Parts
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

[part-power-bus]:https://www.aliexpress.com/item/33007031908.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA

[part-display]:https://www.aliexpress.com/item/32861875681.html?spm=a2g0o.productlist.0.0.40103137cSuJWL&algo_pvid=72a2cf65-9a42-4ea4-acc1-12d0c207044d&algo_expid=72a2cf65-9a42-4ea4-acc1-12d0c207044d-3&btsid=0ab6d59515893349825181599eeff5&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

[part-mcu]:https://www.aliexpress.com/item/32856118319.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA

[part-rotary]:https://www.aliexpress.com/item/1000001872933.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA

[part-m2x5mm]:https://www.aliexpress.com/item/32975410255.html?spm=a2g0o.detail.0.0.496572dbSutw9Y&gps-id=pcDetailCartBuyAlsoBuy&scm=1007.12908.131176.0&scm_id=1007.12908.131176.0&scm-url=1007.12908.131176.0&pvid=ff23c9a7-d73c-454f-a4c6-322a121bd814&_t=gps-id:pcDetailCartBuyAlsoBuy,scm-url:1007.12908.131176.0,pvid:ff23c9a7-d73c-454f-a4c6-322a121bd814,tpp_buckets:668%230%23131923%2319_668%23808%235965%23251_668%23888%233325%2311_668%232846%238111%23466_668%232717%237566%23817

[part-m2x10mm]:https://www.aliexpress.com/item/33043091484.html?spm=a2g0o.productlist.0.0.767f4a08gAx7Oc&s=p&ad_pvid=2020051218463417005721656175370016165454_11&algo_pvid=9e1a1b86-9322-441f-b087-ef567c376f63&algo_expid=9e1a1b86-9322-441f-b087-ef567c376f63-10&btsid=0ab6d69f15893343947923488e699c&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

[part-wires]:https://www.aliexpress.com/item/33007698478.html?spm=a2g0o.productlist.0.0.44b248d7kcLfV9&algo_pvid=b0a90a38-c903-4828-9cf3-0073b86684ae&algo_expid=b0a90a38-c903-4828-9cf3-0073b86684ae-6&btsid=0ab6d67915893355772902177e0543&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

[part-bumpers]:https://www.aliexpress.com/item/32289191938.html?spm=a2g0o.productlist.0.0.20513e1cJD6rV0&s=p&ad_pvid=2020051219254812188693811548200016292927_1&algo_pvid=f58a6173-19a8-4de7-9dbb-819984df4870&algo_expid=f58a6173-19a8-4de7-9dbb-819984df4870-0&btsid=0ab50f6115893367485698071ebd11&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

[part-led-ring]:https://www.aliexpress.com/item/32758176722.html

# Parts
All parts for the maxmix controller can be found and purchased online.  
Links to the parts are provided below but feel free to purchase them elsewhere.  
When looking for alternatives, just make sure the part specifications match to avoid any issues.

## 3D Print
The enclosure for the controller is made of a couple of 3D printed parts and can be downloaded from [Thingiverse](https://www.thingiverse.com/thing:4343186).

If you don't have a 3D printer, I recommend using a community printing service such as [Treatstock](https://www.treatstock.com/), it is the most cost effective method.

{% include gallery.html 
  gallery="build/parts/enclosure/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## Hardware
Below are the rest of parts needed to complete the project.

- 4x [M2 10mm Countersink screws][part-m2x10mm]
- 6x [M2 5mm Screws][part-m2x5mm]
- 4x [Silicon bumper 2x8mm][part-bumpers]
- 1x [Arduino Nano 328P CH340][part-mcu]
- 1x [128x32 I2C OLED display][part-display]
- 1x [Rotary encoder][part-rotary]
- 1x [Power bus][part-power-bus]
- 11x [10cm Female to female jumper wires][part-wires]
- 1x [WS2812 5050 LED Ring 8-bit (Optional)][part-led-ring]

{% include gallery.html 
  gallery="build/parts/hardware/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}


## Tools
Here are the tools you are going to need.

- Small philips screwdriver
- Soldering iron (or alternative such as conductive silver epoxy)
- Needle nose pliers
- Wire cutting pliers
- Wire stripper (Optional)
- Third hand (Optional)

{% include gallery.html 
  gallery="build/parts/tools/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}
