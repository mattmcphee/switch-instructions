# Switch Instructions

## General

- Hold R while launching a game to go into the homebrew menu
- Use DBI to install games: launch DBI from homebrew menu -> run MTP responder -> copy downloaded game files into SD Card Install or NAND Install
- Download game files from nswtl.info telegram

## AutoRCM

- AutoRCM is an option in Hekate that corrupts the bootloader so it automatically goes into Recovery Mode
- AutoRCM should always be kept ON
- Turning off AutoRCM then rebooting the Switch means you'll need to use the physical jig to put the Switch in Recovery Mode!

## Booting into Hekate

- Simply restart the Switch by holding the power button -> power options -> reboot
- On the splash page, press Vol Down to boot into Hekate

## Accessing the SD Card

- DBI can be used to access the SD card but it's not as robust as Hekate because Hekate runs outside the firmware (pre-boot environment)
- Plug switch into PC -> reboot the switch -> press vol down on splash page to boot into Hekate -> Tools -> USB -> SD Card

## Booting into Stock Official Firmware from Custom Firmware

- Reboot the switch -> press vol down on splash page to boot into Hekate -> Launch -> Stock

## Booting into Custom Firmware from Stock Official Firmware

- Reboot the switch -> the Switch will be in Recovery Mode (black screen nothing happening)
- Open TegraRCMGUI on your PC -> connect Switch to PC -> should say RCM OK -> inject the latest Hekate.bin
- The splash screen should appear -> press vol down on splash screen -> Launch -> Atmosphere

## Updating firmware
