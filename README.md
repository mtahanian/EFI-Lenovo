# EFI-Lenovo
Lenovo Ideapad 320 15IKB (81BG Type) EFI

:information_source: **The current version is fully macOS compatible based on my laptop hardware.**
OpenCore, drivers, and kexts are always up to date!

:information_source: The EFI's have been tested on Moneterey, Ventura and Sonoma.

<br/>

:warning: **IMPORTANT**

This is not a guide, please refer to [Dortania](https://dortania.github.io/getting-started) before doing anything. I am not responsible for any damage. This OpenCore configuration is optimized for my specific hardware, so please use it only as a reference or if you happen to have the same or similar hardware.

<br/>


## Images:

|---------------|----------------------------------------|
| Sonoma        |  [Sonoma](/assets/sonoma.png)     |
| Ventura       |  [Ventura](/assets/ventura.png)   |
| Monterey      |  [Monterey](/assets/monterey.png) |
|--------------------------------------------------------|
    
## :computer: Hardware:

| **Category** | **Component**                         |
| ------------ | ------------------------------------- |
| **CPU**      | 1.6GHz Intel Core i5-8250U            |
| **GPU**      | Intel UHD 620                         |
| **RAM**      | 12GB (4GB non-removable) 2133MHz DDR4 |
| **SSD**      | 256GB SATA SSD (Samsung PRO 850)      |
| **Display**  | 15,6" 1080p LCD non-touch display     |
| **Wi-Fi/BT** | Intel Dual Band Wireless-AC 3165 + BT |
| **Ethernet** | Realtek RTL8111                       |
| **Audio**    | Realtek ALC230 (layout-id=20)         |
| **Input**    | PS2 Keyboard & Synptics TrackPad      |
| ---------------------------------------------------- |

## :white_check_mark: Working:

- [x] CPU power management.
- [x] Graphics acceleration.
- [x] Battery read-out.
- [x] Keyboard & trackpad with all macOS gestures.
- [x] Wi-Fi.
- [x] Bluetooth.
- [x] USB ports.
- [x] HDMI video & audio output.
- [x] Ethernet.
- [x] Audio (Internal speakers, 3.5mm headphone jack).
- [x] Internal microphone.
- [x] VGA WebCam.
- [ ] AirDrop & Handoff.
- [x] iCloud & App Store.
- [x] iMessage & FaceTime.

## :x: Not working:

Only AirDrop and Handoff are not working since the Intel card are not fully compatible with macOS. To make these things works you need to replace with a native card one, like the Fenvi cards.

For Wifi Connection you can install Heliport.Due to its faster connection and speed I've replaced it with Airport.

For Ethernet you can use USB Ethernets too!

## BIOS setup:

- Security / Intel Platform Trust Technology - Disabled
- Security / Intel SGX - Disabled
- Security / Secure Boot - Disabled
- Boot / Boot Mode - UEFI


## Credits:

[**Apple**](http://apple.com/)

[**Dortania**](https://dortania.github.io/getting-started/)

[**Milad Tahanian**](https://github.com/mtahanian)