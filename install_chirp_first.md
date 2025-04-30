---
title: Install CHIRP
parent: Get CHIRP First
nav_order: 1
---

# Install CHIRP

CHIRP supports the UV-K6 out of the box. If you want to use CHIRP with the *armel/uv-k5-firmware-custom* firmware you need to install a custom script in CHIRP first. This script gives you the ability to directly configure the radio for the changes that the firmware implements. Other firmwares may require their own scripts to be added to CHIRP for full support. Here are quick links for how to install CHRIP:

* [Basic CHIRP Download](https://chirpmyradio.com/projects/chirp/wiki/Download)
* [Specific CHIRP driver for armel/uv-k5-firmware-custom](https://github.com/armel/uv-k5-chirp-driver)

## Set up CHIRP to use your radio

Once CHIRP is installed you need to do a few things before you can program your radio.

1) Connect your programming cable to the computer and ensure that it registers as a valid device.
2) Start up CHIRP and ensure it can communicate with CHIRP. If step 1 completes, then this step probably is fine.
3) Plug the programming cable into your radio.
4) Configure CHIRP to use your radio.
   - With an unmodified UV-K6, Click *Radio > Download from Radio...* and the Communicate with radio dialog opens. The programming cable should show in the Port drop down, and from here you will select the Quanshang UV-K5
   - With a UV-K6 running the *armel/uv-k5-firmware-custom* firmware, you need to set CHIRP to use developer mode and install a Python module from the linked page. You then need to access the *Radio > Download from Radio...* menu, ensure your cable is visible to CHIRP and set it to use the modified radio profile. I'm sure there's a video I can link to here.
5) After step 3 completes, you'll be presented with the spreadsheet view of your radio's channel memories, and you can program and customize from here.

Getting through the above steps will make programming your radio so much easier than programing it with the radio's keypad. 