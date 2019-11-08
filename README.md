# Dell Latitude 7490 Hackintosh EFI

## Tested macOS Version
10.14: macOS Mojave 10.14.6

10.15: macOS Catalina 10.15.1

## System Configuration
- Intel i5 8350U
- Intel UHD 620
- Samsung SM961 256G
- DW1560 (BCM94352z)

## What's working
 - [x] Audio w/ headphone jack
 - [x] CPU Speedstep
 - [x] iGPU acceleration
 - [x] Battery Management
 - [x] Backlight
 - [x] Ethernet
 - [x] HDMI
 - [x] Sleep & Wake
 - [x] Smart Touchpad w/ Gestures (using I2C)
 - [x] WebCam
 - [x] USB 3.0
 - [x] Sleep From (Lid)
 - [x] WiFi (2.4 + 5GHz) & BT by using BCM94352z
 - [x] Handoff, Airdrop & Sidecar (Sidecar for Catalina)
 - [x] Native hotkey support w/ Fn keys
 - [x] USB-C charging

## What's not working(I have found)
- - Trackpad Keys
- - TrackPoint
- - Fingerprint sensor
- - WWAN card
- - Smart card reader

## What's not tested yet
- - Audio over HDMI
- - MicroSD card
- - USB-C Data transfer/DP-alt Mode/etc.
- - Thunderbolt


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
