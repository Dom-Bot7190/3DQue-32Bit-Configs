# 3DQue Firmware for the Ender 3 32 Bit Variants

This repository contains the source code we compile into the .bin files we have available for download on [our website](3dque.com). These files are available for download if you wish to edit them to work with your unique ender configuration.

Our firmware is based on [Marlin 2.0.x](https://github.com/MarlinFirmware/Marlin/) and is distributed under the terms of the [GNU GPL 3 license](LICENSE). We have made a few tweaks to the firmware to get the most out of your leveling configuration and stop bed drops when the printer is tilted on its side.

# Find Your Firmware

The main branch of this repository contains the marlin code that is compiled. Tailor it to your printer by finding the appropriate configuration files in the config folder. NP is for the stock endstop configuration (no leveling), IP is for inductive probes, and blt is for ~lunch sandwiches~ BLTouch probes. Move these files to the Marlin folder and rename them to Configuration.h and Configuration_adv.h respectively and you are ready to compile! 