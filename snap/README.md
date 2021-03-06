# Unofficial Snap Packaging for Universal Update Utility
<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
![(Placeholder) Icon of Universal Update Utility](gui/universal-update-utility.png "(Placeholder) Icon of Universal Update Utility")

**This is the unofficial snap for Universal Update Utility**, *"Freescale/NXP I.MX Chip image deploy tools"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![universal-update-utility](https://snapcraft.io//universal-update-utility/badge.svg)](https://snapcraft.io/universal-update-utility)

![Screenshot of the Snapped Application](local/screenshots/carbon-help.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Snap ownership transfer notice

This snap is now transferred to the upstream, please refer to [NXPmicro/mfgtools: Freescale/NXP I.MX Chip image deploy tools.](https://github.com/NXPmicro/mfgtools) for more info regarding the use of the snap package.

This page is now only serve for educational purposes.

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal
    # Install the snap #
    sudo snap install --channel=beta universal-update-utility
    #sudo snap install universal-update-utility

    sudo snap alias universal-update-utility uuu
    
    # Connect the snap to essential security confinement interfaces #
    ## Allow the snap to communicate to USB devices with custom protocol ##
    sudo snap connect universal-update-utility:raw-usb
    
    # Connect the snap to optional security confinement interfaces #
    ## Allow the snap to access files under /media ##
    sudo snap connect universal-update-utility:removable-media

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/universal-update-utility)

## What is Working
* Flashing compatible devices

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/Lin-Buo-Ren/uuu-snap/issues) for known issues.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/uuu-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>
