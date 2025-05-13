# Xbox 360 Modding

## Methods
* [RGH3](./RGH3.md) Glitch exploit using only 2 wires, uses the southbridge to glitch instead of a glitch chip
* [Bad Update](./Bad%20Update.md) Non-persistent exploit using a USB

## Apps
You should download all these onto a USB
* [Aurora](http://phoenix.xboxunity.net) Pretty custom dashboard
* [DashLaunch](https://digiex.net/threads/dash-launch-3-21-for-jtag-rgh-xbox-360s-running-freeboot.11024/) Used to run the custom dashboard (Aurora) and apply some general tweaks on startup, such as custom boot animations, disabling Xbox Live and running plugins. Do NOT install this to your NAND if using BadUpdate, it will brick your console
* [XeXMenu](https://digiex.net/threads/xexmenu-1-1-download-xex-menu-iso-live-and-xex-file-manager-for-xbox-360.11096/) File manager and basic dashboard, mainly used during the setup process

## Useful links
* [Myrient](https://myrient.erista.me/files/Redump/Microsoft%20-%20Xbox%20360/) Game redumps, get your games here (or Internet Archive)
* [XM360](https://digiex.net/threads/xm360-2-0d-download-xbox-360-jtag-xbla-dlc-tu-content-organiser.7999/) Useful for unlocking XBLA games and DLC's (however this should be possible through Aurora and DashLaunch)
* [Iso2God](https://github.com/r4dius/Iso2God) Convert ISO files to GoD (Game on Demand), makes games compatible with stock dashboard and generally more reliable
* [UsbdSecPatch](https://github.com/InvoxiPlayGames/UsbdSecPatch) A DashLaunch plugin that bypasses authentication checks for devices (such as controllers), will be needed for OGX-Mini
* [OGX-Mini](https://github.com/wiredopposite/OGX-Mini) Raspberry Pi Pico firmware to use ANY controller, a ESP32 can also be added for bluetooth functionality
* [Horizon](https://www.wemod.com/horizon) Modding tool to modify save data, unlock achievements, etc
* [XBDM](https://digiex.net/threads/xbox-360-jtag-xbdm-download.9243/) A DashLaunch plugin that adds some Development Kit functions, needed for Xbox 360 SDK to work
* [Xbox 360 SDK](https://www.mediafire.com/file/l9786i9endh5w5e/XBOX360_SDK_21256.3.exe/file) Gives you some remote access (like Xbox 360 Neighborhood)
* [Proto](https://xbox360hub.com/xbox-live-stealth/) A DashLaunch plugin, free Xbox Live Stealth client to connect to Xbox Live without getting banned (there is still a risk)
* [FATXplorer](https://fatxplorer.eaton-works.com/download/) Useful for mounting and formatting Xbox 360 HDD's
* [Original Xbox emulator](https://fatxplorer.eaton-works.com/restoring-original-xbox-backwards-compatibility/) For installing either an original or modded OG Xbox for backwards compatibility
* [XellLaunch](https://digiex.net/threads/xell-launch-with-xell-reloaded-hdmi-support-and-a-quickboot-shortcut-download.9158/) An older version of the XellLaunch that is bundled with DashLaunch, I couldn't get Ubuntu to run with the newer version
* [Ubuntu Xenon](https://sourceforge.net/projects/free60/files/liveCDs/) A Linux distro based on Ubuntu 10.10 for the Xbox 360
* [extract-xiso](https://github.com/XboxDev/extract-xiso) For extracting .iso files (useful for extracting install disks)
* [Simple 360 NAND Flasher](https://www.consolemods.org/wiki/File:Simple_360_NAND_Flasher.7z) For dumping/writing NAND from the Xbox itself
