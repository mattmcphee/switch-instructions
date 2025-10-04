# Switch Instructions

## Launching the Homebrew Menu

- Hold R while launching a game to go into the homebrew menu

## Installing Games

- Use DBI to install games: launch DBI from homebrew menu -> run MTP responder -> copy downloaded game files into SD Card Install or NAND Install
- NAND games run on the Switch's flash memory so will be a tiny bit faster than games on SD card
- Download game files from nswtl.info telegram

## AutoRCM

- AutoRCM is an option in Hekate that corrupts the bootloader so it automatically goes into Recovery Mode
- AutoRCM should always be kept ON
- Turning off AutoRCM then rebooting the Switch means you'll need to use the physical jig to put the Switch in Recovery Mode to get back to custom firmware!

## Booting into Hekate

- Simply restart the Switch by holding the power button -> power options -> reboot
- On the splash page, press Vol Down to boot into Hekate

## Accessing the SD Card without removing it from the Switch

- DBI can be used to access the SD card but it's not as robust as Hekate - Hekate runs outside the firmware (pre-boot environment)
- Plug switch into PC -> reboot the switch -> press vol down on splash page to boot into Hekate -> Tools -> USB Tools -> SD Card
- You shouldn't really need to mess with the files on the SD card unless you know what you're doing or modding etc.
- The main stuff can be done all from inside the Switch or from Hekate

## Booting into Stock Official Firmware from Custom Firmware

- Reboot the switch -> press vol down on splash page to boot into Hekate -> Launch -> Full Stock

## Booting into Custom Firmware from Stock Official Firmware

- Reboot the switch -> the Switch will be in Recovery Mode (black screen nothing happening)
- Open TegraRCMGUI on your PC -> connect Switch to PC -> should say RCM OK -> inject the latest Hekate.bin
- The splash screen should appear -> press vol down on splash screen -> Launch -> Atmosphere

## Switch Firmware

- Some of the latest games or game updates require the latest Switch firmware to run
- Since we use SysNAND and emuNAND, we have two separate firmware versions

## Updating Switch Firmware on Custom Firmware

- Before we download the latest firmware, we need to update Kefir!
- What is Kefir? A modified Atmosphere to simplify the custom firmware process on Switch. It's made by rashkevsky from Ukraine.
- Hold R when launching a game to go into the Homebrew menu
- Launch Kefir updater -> press A on the latest Kefir version (780 as of 4-Oct-2025) -> Kefir should automatically update
- After Kefir updates, go into the Homebrew menu -> launch Kefir Updater again -> Download firmwares -> get the latest firmware version shown here
- The firmware will be downloaded automatically from <https://github.com/THZoria/NX_Firmware>
- After download you will be prompted to launch Daybreak -> press yes (Daybreak can be launched from the homebrew menu)
- Launch Daybreak -> find the downloaded firmware -> press Install -> press Reboot
- The Switch may reboot a couple of times but should end up back in custom firmware -> we're done!

## Updating Switch Firmware on Stock Firmware

- Reboot the Switch -> inject Hekate via TegraRCMGUI -> press Vol Down at splash page to boot into Hekate
- Launch -> Full Stock
- Once booted into full stock firmware -> connect to internet -> update the firmware via Nintendo's System Update in settings
- We can now update our legit games via Nintendo and play online on Nintendo servers etc.
- Get back into Custom Firmware by following the steps in the section above
