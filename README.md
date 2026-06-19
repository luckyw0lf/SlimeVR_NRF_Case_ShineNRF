# SlimeVR_NRF_Case_ShineNRF


 Case for Shine Bright's 'ShineNRF' Smol slime design. [EasyEDA PCB source files](https://u.easyeda.com/account/user/projects/index/detail?project=545e99bf677c4318850288026fb6eac0&listType=all)

## Bill of Materials
|Amount         | Parts              | Link
|-----          | -----              | -----
|1x per tracker | Unpopulated PCB    |   [EasyEDA PCB source files](https://u.easyeda.com/account/user/projects/index/detail?project=545e99bf677c4318850288026fb6eac0&listType=all) or [production files](https://github.com/luckyw0lf/SlimeVR_NRF_Case_ShineNRF/blob/main/Gerber_ShineNRF_ShineNRF_2026-06-19.zip)
|1x per tracker | NRF52840 Pro micro |   https://nl.aliexpress.com/item/1005007383270623.html
|1x per tracker | IMU ICM45686*      |   https://shop.slimevr.dev/products/slimevr-mumo-breakout-module-v1-icm-45686-qmc6309
|1x per tracker | 303030 Battery     |   https://nl.aliexpress.com/item/32892030632.html
|1x per tracker | SK12D07 Switch 2mm |   https://nl.aliexpress.com/item/1005004401308665.html
|1x per tracker | 3x6x2.5mm button   |   https://nl.aliexpress.com/item/4000546059630.html
|1x in total    | Dongle**            |   https://nl.aliexpress.com/item/1005003055660073.html

> Note * You can use other IMUs supported by the SlimeVR NRF firmware. Here's the list: https://docs.slimevr.dev/smol-slimes/hardware/smol-tracker.html#tracker-parts

> Note ** The link reffers to a holyiot-21017 dongle. This is at the moment of writing the best option, you could also use another pro micro, but reception might be poor, for further reference, look here: https://docs.slimevr.dev/smol-slimes/hardware/smol-receiver.html?highlight=dongle#-usb-dongles

Please consider other shops too, these are just for reference and what I personally used.
If any of the links need updating, please make a github issue or contact me at mcluckyw0lf@gmail.com.

## Useful info<br>

* Firmware: https://docs.slimevr.dev/smol-slimes/firmware/smol-pre-compiled-firmware.html#normal-non-stacked
  * Above the firmware, there's explained which firmware suits your setup, I use a ICM45686 module from SlimeVR, I use the SPI + Clock + noSleep option, for this design the button firmware is needed.<br>
* Smol slime(nRF) docs: https://docs.slimevr.dev/smol-slimes/<br>
* This design was made to be soldered with a hotplate. Most parts are surface mount. I reccomend getting one for this project. I got a cheap one for about 20 euros which is USB C powered.
* PLA or PETG works fine for me, the tracker is mostly parametric, so you can change some tollerences if needed.

---

### Please be carefull when assembling the tracker!
Pay attention when putting in the battery and the tracker or when removing the electronics from the case! Tollerances are pretty tight, so be carefull not to puncture the battery.

<br>
<br>
Todo:<br>

* Make pictures of the trackers
* ✅ Add production files to make it not required to have a EasyEda account for manufactoring the pcb
* Maybe add some easy steps for ordering the PCB from JLCPCB
