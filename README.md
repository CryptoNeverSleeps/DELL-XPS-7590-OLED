# DELL-XPS-7590-OLED

Hackintosh - macOS Big Sur 11.1 - Open Core 0.6.5

## Hackintosh XPS 7590 OLED


## Sources:
https://dortania.github.io/OpenCore-Install-Guide/

https://github.com/stakeout55/Dell-XPS-7590-mac-OS-Big-Sur-11.1

https://github.com/geek5nan/Hackintosh-XPS7590

https://github.com/xxxzc/xps15-9570-macos

https://github.com/daliansky/XPS15-7590-Hackintosh

https://github.com/gorquan/OC-XPS-7590

https://github.com/romancin/Dell-XPS-7590-OpenCore


### Configuration

**OpenCore Version**: [0.6.5](https://github.com/acidanthera/OpenCorePkg/releases)

**macOS Version**: macOS Big Sur 11.1

### Specifications

| Key                    | Value                                                        |
| ---------------------- | ------------------------------------------------------------ |
| SKU                    | [XPS-7590]|                                                  |
| CPU                    | Intel Core i7 9750H                                          |
| GPU                    | Intel Graphics UHD 630                                       |
| Built-In Screen        | 15.6"  4K OLED                                               |
| RAM                    | Vengeance® Series 64GB (2 x 32GB) DDR4 SODIMM 2666MHz        |
| Internal SSD - Windows | 970 Evo Plus NVMe M.2 2TB                                    |
| Internal SSD - mac OS  | 970 Evo Plus NVMe M.2 2TB                                    |
| Audio                  | Realtek ALC298                                               |
| Wireless               | Dell Wireless DW1820A - Kapton Tape Method                   |
| ---------------------- | ------------------------------------------------------------ |


# What's Working: - Credit - https://github.com/geek5nan/Hackintosh-XPS7590

* iGPU：working.
* Wireless Card(**DW1820A**):  WiFi&BT working.
* Audio：spkear & mic working.
* Camera：working.
* Input：keyboard & touchpad working.
* HDMI Port：cold-plug working，hotplug half-working.
* USB port： Type-A port x 2 (Max 5 Gbps) and Type-C port x 1 (Max 10 Gbps)
* Brightness Controll: wokring on Non-OLED Screen.
* Sleep/Wake: working on Non-OLED Screen.


# What's Not Working: - Credit - https://github.com/geek5nan/Hackintosh-XPS7590
1. OLED Brightness Control

   * Brightless Slider shown & Brightless shortcut work but OLED brightness never changed

2. OLED Sleep & Wake
	 >  Seems like OLED brightness issues. not sure other screen is work or not.

   * Sleep is working, but built-in screen will be black screen when wake.


3. HDMI hot-plug 
   * Problem
     * Can't resume to single monitor mode when remove HDMI monitor, and virtual desktop in external monitor will be loss.
     * HDMI monitor will be black except mouse indicator when re-plug HDMI monitor.
   * Workaround
     1. Enable mirror mode in Preferences-Monitor-Arrangement **before** remove HDMI monitor to avoid virtual desktop loss in external monitor.
     2. Use built-in screen to toggle screen resolution in Preferences-Monitor **after** re-plug HDMI monitor. External screen will light soon.
	 
4. SDCard Reader not working - Need to test Sinetek-rtsx.kext

5. Fingerprint not working.




![About This Mac](Images/AboutThisMac.png)


