# Maverick Storm 2 Profile

## Software Versions

[V1.250407 - Maverick Storm 2 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM2PROFILE/blob/27112430e25c08af4e80e87679493735e8bbb173/firmware/V1.250407.zip)
- Fix RDM failures
- Fix a USB bug error that will show up every now and then, even when no USB is plugged in.

[V1.250116 - Maverick Storm 2 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM2PROFILE/blob/9b65bb466937cc9eba36c6cc40b5f3934e229541/firmware/V1.250116.zip)
- Improve control of motor code, as there is some tolerance of the motors for prism rotation, in which there will be some noise when the prism is rotating at certain DMX values

[V1.24020 - Maverick Storm 2 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM2PROFILE/blob/0cc18e1001102225071e2481609de13c2aad61c4/firmware/V1.24020.zip)
- Changed control channel value for the TV fan modes
     * 216-217 = TV25
     * 218-220 = TV35

[V1.230713 - Maverick Storm 2 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM2PROFILE/blob/3df22259fc6231250e255a454cc6aad7fc625cd4/firmware/V1.230713.zip)
- Updated the CMY function to match the MK3 Profile

[V1.221215 - Maverick Storm 2 Profile](https://github.com/Chauvet-Pro/MAVERICKSTORM2PROFILE/blob/3df22259fc6231250e255a454cc6aad7fc625cd4/firmware/V1.221215.zip)
- Released initial software version

&nbsp;

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
