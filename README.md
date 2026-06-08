# Avalon Kernel

Custom NetHunter-focused kernel for the Xiaomi Poco F4 GT (ingres).

Built for LineageOS 23.2 with KernelSU-Next integration, external USB WiFi adapter support, SDR support and Kali NetHunter compatibility.

## Disclaimer

I am not responsible for any damage caused to your device.

You are choosing to modify your device and assume full responsibility for anything that happens as a result.

## Features

* KernelSU-Next integrated
* Kali NetHunter support
* External USB WiFi adapter support
* Monitor mode capable chipset support
* SDR support
* Additional firmware support for NetHunter environments
* Built for LineageOS 23.2 (Android 16)

## Requirements

* Xiaomi Poco F4 GT (ingres)

* [LineageOS 23.2](https://xdaforums.com/t/development-lineageos-23-2-unofficial-for-ingres.4763102/)

* Unlocked bootloader

## Installation

1. Download the latest [Avalon Kernel release](https://github.com/ruik3z/avalon-ingres/releases)

2. Flash the provided boot image via fastboot

`fastboot flash boot boot.img`

3. Reboot

`fastboot reboot`

4. Install [KernelSU-Next](https://github.com/KernelSU-Next/KernelSU-Next) and verify KernelSU support is functioning correctly

5. Setup Kali NetHunter and install Avalon Firmware module as stated below

## Kali NetHunter

For complete NetHunter installation instructions, see [NetHunter Setup Guide](https://github.com/ruik3z/nethunter-guide)

## Firmware Module

To use supported external wireless adapters and SDR devices, install the [Avalon Firmware module](https://github.com/ruik3z/avalon-firmware)

## Source Code

[Kernel Source](https://github.com/ruik3z/kernel-ingres)

## Credits

### Base ROM

Huge thanks to itzparsaYC for bringing LineageOS 23.2 to ingres.

### Development & Testing

Special thanks to n08i40k for extensive testing and development support.

### Additional Credits

* ArianK16a for SM8450 sources
* KernelSU-Next developers
* Kali NetHunter developers
* LineageOS project
* All testers and contributors

## License

The kernel source code used by this project is licensed under GPLv2.

Corresponding source code is available in the kernel source repository.
