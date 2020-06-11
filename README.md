# Dell Latitude 7490 Hackintosh EFI

IF YOU ARE NEW HERE, CHECK OUT OTHER BRANCHES FOR WHAT YOU WANT.

## Tested macOS Version
10.14: macOS Mojave 10.14.6

10.15: macOS Catalina 10.15.3

## System Configuration
- Intel i5 8350U
- Intel UHD 620
- Samsung SM961 256G
- DW1560 (BCM94352z)

## What's working
 - [x] Audio 
  
 - [ ] & headphone jack (yeah it doesn't)

 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management

 - [x] Backlight

 - [x] Ethernet

 - [x] HDMI

 - [x] Sleep & Wake

 - [x] Smart Touchpad w/ Gestures (using I2C) *

 - [x] WebCam

 - [x] USB 3.0

 - [x] Sleep (Lid & Fn + Insert)

 - [x] WiFi (2.4 + 5GHz) & BT by using BCM94352z

 - [x] Handoff, Airdrop & Sidecar (Sidecar for Catalina)

 - [x] Native hotkey support w/ Fn keys

 - [x] USB-C charging

 - [x] USB-C DP-alt Mode
  
 - [x] FileVault 2 support for Catalina (Mojave one should work, but not tested)

 - [ ] USB-C Data transfer (2)
 
 (1) Physical buttons & TrackPoint doesn't work.

   (2) Partially working, needs to plug a device before boot in order that macOS could pick up USB-C controller, then it's plug-n-play and hot-plug&unpluggable in macOS. It may cause problems when lid closed or the system sleeps.

## TODO:
- Migrating to OpenCore
- Fix headphone jack
- Add SD card support
  `https://github.com/cholonam/Sinetek-rtsx`

## What's not working(I have found)
- Trackpad Keys
- TrackPoint
- Fingerprint sensor
- WWAN card
- Smart card reader

## What's not tested yet
- Audio over HDMI
- MicroSD card
- Thunderbolt


## Something you may want to apply

**Click by trackpad:**
System Preferences - Trackpad - Tap to click

**Drag by trackpad:**
System Preferences - Accessibility - Mouse & Trackpad - Trackpad Options... - Enable Dragging

**Change trackpad tracking speed**
System Preferences - Trackpad - Tracking Speed

**Enable HiDPI:**
Run the following command by terminal

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"`

## Key mapping

You can modify this in System Preference - Keyboard -Modifier Keys...
Ctrl - Control

Fn - Fn

Win - Option

Alt - Command



## Easter egg
Try Ctrl+Alt+Power Btn!

## Credit
xzhih/one-key-hidpi：https://github.com/xzhih/one-key-hidpi
