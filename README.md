# Hp_elitebook_840G3_EFI

Working EFI of MacOS 12 Monterey 12.7.6 for Elitebook 840G3 works well. it's updated again with all the sound tested channel for switching audio between internal speaker or headphone jack wiith working graphics native support which is in my case Intel HD 520 with 1536 vram with System Shared memory, Also works well the wifi card, Airdrop but partially

Warning: Don't use this EFI with another else matching laptop approx. This EFI is fully configured for Elitebook 840G3

# My Machine Specification
- CPU : Intel core i5 Dual core 6300U 2.50 GHz 
- GPU : Integrated Intel HD Graphics 520 1536mb VRAM with System Shared Memory
- Wifi/Bluetooth : Intel Wireless AC 8260
- Audio Codec : Conexant CX20724
- Memory : 16GB DDR4 2133 MHz
- SSD : MTFDDAV256TBN 256GB

# Supported MacOS versions 
- Catalina 10.15.7, BigSur 11.7.10, Monterey 12.7.6, Ventura, Sonoma Sequoia 15.0 and also this EFI supports the Latest MacOS 26 Tahoe BETA version 
- The EFI folder i uploaded is already configured for Catalina 10.15.7, Bigsur 11.7.10, and Monterey 12.7.6 
- If you want to use this folder with Ventura, Sonoma, Sequoia just add the AirportItlwm.kext for working Wifi
- use [proper-tree](https://https://github.com/corpnewt/ProperTree) to edit the config.plist or use the [opencore-configurator](https://github.com/notiflux/OpenCore-Configurator) as your wish and add the proper AirportItlwm.kext for the particular macos version. 

# Working 
- Graphics Acceleration
- Audio ( Internal speakers, Headphone jack, Mic) My alcid is 13. 
- WiFi and Bluetooth ( no need to use Heliport just use the proper AirportItlwm.kext according to the macos version. and it will work ntively but partially remember that it's not going to provide you complete native support.)
- DP and VGA (You can add external monitor).
- Keyboard with Backlit (works great.)
- Trackpad (workig well also support three finger gesture)
- Brightness key also working 
- Battery (works well and show the exact recharge cycle count)

# ScreenShots
- I provide you some screenshots 
![Screenshot](https://github.com/rahulsinghaspqwv/Hp_elitebook_840G3_EFI/blob/main/Screenshot%202025-07-02%20at%209.11.16%20PM.png)
![Screenshot](https://github.com/rahulsinghaspqwv/Hp_elitebook_840G3_EFI/blob/main/Screenshot%202025-07-02%20at%209.11.49%20PM.png)


# Build raw EFI
- Use [Opencore-Simplify](https://github.com/lzhoang2801/OpCore-Simplify) to build the raw EFI for your system if you familiar with ACPI tables and select or build the write patch for ACPI or Fake RTC SSDT.aml or fake ambient sensor and much more patches with the write kext format files. AND One important thing is choose the write SMBIOS for your machine so it works well.

or if you want to build EFI step by step go to [Opencore-Dortania](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites) website it will guide you step by step for your machine to turn into full Hackintosh. 

# Suggestion
- If you want to work on that machine with MacOS Hackintosh or you want stable performence then i recommend you to go for MacOS Monterey 12.7.6 version it gives you the stable performence.
- Don't go for higher versions because the CPU and GPU is not much powerfull to provide you a batter and stable performence with highter versions
- in my openion maximum version is ventura with this hardware configuration . Don't go for Sonoma or Sequoia if you want stability or better performence anotherwise you will face laggy and chopy experience. 

# Post Intallation
After Successfull Installation of macos use [MountEFI](https://github.com/corpnewt/MountEFI) github tool by CorpNewt to mount the EFI folder of your MacOS Disk where you installed on your machine and Copy this EFI folder to Mounted Disk otherwith your machine will not boot into MacOS without the installation media. 
This step is necessery to booting MacOS independently.

after this step ENJOY your MacOS.


# Credits 
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites) - Build the EFI with OpenCore guide
- [itlwm](https://github.com/openintelwireless/itlwm/releases) - Intel wifi | Bluetooth
- [Apple](https://apps.apple.com/us/app/macos-monterey/id1576738294?mt=12) - Downloading official MacOS
- [Opencore-Simplify](https://github.com/lzhoang2801/OpCore-Simplify) - for Easy build
- [CorpNewt](https://github.com/corpnewt/MountEFI) - for Independently Booting MacOS without Installation Media

