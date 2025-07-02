# Hp_elitebook_840G3_EFI

Working EFI of MacOS 12 Monterey 12.7.6 for Elitebook 840G3 works well. it's updated again with all the sound tested channel for switching auto between internal speaker or headphone jack wiith working graphics native support which is in my case INTEL HD 520 with 1536 vram and shared memory, Also work well wifi cards, Airdrop but partially

Warning: Don't use this EFI with another else matching laptop approx. This EFI is fully configured for Elitebook 840G3

# My Machine Specification
- CPU : Intel core i5 Dual core 6300U 2.50 GHz 
- GPU : Integrated Intel HD Graphics 520 1536mb VRAM with System Shared Memory
- Wifi/Bluetooth : Intel Wireless AC 8260
- Audio Codec : Conexant CX20724
- Memory : 16GB DDR4 2133 MHz

# Supported MacOS versions 
- Catalina 10.15.7, BigSur 11.7.10, Monterey 12.7.6, Ventura, Sonoma Sequoia 15.0 and also this EFI supports the Latest MacOS 26 Tahoe BETA version 
- The EFI folder i uploaded is already configured for Catalina 10.15.7, Bigsur 11.7.10, and Monterey 12.7.6 
- If you want to use this folder with Ventura, Sonoma, Sequoia just add the AirportItlwm.kext for working Wifi
- use [proper-tree](https://https://github.com/corpnewt/ProperTree) to edit the config.plist or use the [opencore-configurator](https://github.com/notiflux/OpenCore-Configurator) as your wish and add the proper AirportItlwm.kext for the particular macos version. 
