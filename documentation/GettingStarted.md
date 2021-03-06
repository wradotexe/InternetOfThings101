Getting Started
==

## Development Workstation

Operating System

- Windows* 64-bit
- Windows* 32-bit
- OS X*
- Linux*

## Intel® Edison

[Intel® Edison Board Get Started Guide](https://software.intel.com/en-us/iot/library/edison-getting-started)

### Community Guides

* [Sparkfun Edison Getting Started](https://learn.sparkfun.com/tutorials/edison-getting-started-guide)
* [Instructables A Comprehensive Intel Edison Getting Started Guide](http://www.instructables.com/id/A-Comprehensive-Intel-Edison-Getting-Started-Guide/)
* [Codefoster Setting up an Intel Edison](http://www.codefoster.com/edison-setup/)
* [Edison Mini Breakout: The Real Getting Started Guide](http://blog.microcasts.tv/2014/10/16/edison-mini-breakout-the-real-getting-started-guide)

## Intel® Galileo

* [Intel® Galileo Board Get Started Guide](https://software.intel.com/en-us/iot/library/galileo-getting-started)
* [Intel® Galileo Makers Getting Started](https://communities.intel.com/community/makers/galileo/getting-started)

## Flashing the Latest Software

### Edison

> Download drivers, installers, new firmware images, IDEs and components like cloud analytics and gateway software.

[Intel® Edison Board Software Downloads](https://software.intel.com/en-us/iot/hardware/edison/downloads)

In your Windows Development Workstation, download the latest Yocto Image, unzip its content, go from the terminal to the directory where the content has been unzipped and flash the image

    C:\Users\aarcemor\Downloads\edison-image-ww25.5-15>flashall.bat

It the Edison, connect both USB cables and wait for flashall.bat to start the flashing process

    U-Boot 2014.04 (Aug 20 2014 - 16:08:32)
       Watchdog enabled
    DRAM:  980.6 MiB
    MMC:   tangier_sdhci: 0
    In:    serial
    Out:   serial
    Err:   serial
    Hit any key to stop autoboot:  0
    boot > run do_ota
    reading ota_update.scr
    14747 bytes read in 31 ms (463.9 KiB/s)
    ## Executing script at 00100000
    ...

Finally, open your Serial Terminal

### Galileo

> Keep your development environment up-to-date with software downloads for the Intel® Galileo board.

- [Intel® Galileo Board Downloads](https://software.intel.com/en-us/iot/hardware/galileo/downloads)
- [Making a bootable micro SD Card with Windows*](https://software.intel.com/en-us/programming-blank-sd-card-with-yocto-linux-image-windows)
- [Win32DiskImager](http://sourceforge.net/projects/win32diskimager)

In your Windows Development Workstation, download the latest Yocto Image, unzip its content, open Win32DiskImager and flash the image, finally power cycle Galileo and open your Serial Terminal
