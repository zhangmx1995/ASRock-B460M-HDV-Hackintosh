# ASRock-B460M-HDV-Hackintosh
## open core version:0.6.2

## Detail of my computer

| Specifications |                     Detail                     |
| -------------- | :--------------------------------------------: |
| M/B            |                ASRock-B460M-HDV                |
| System         | macOS Catalina 10.15.x / macOS Big Sur 11 Beta |
| CPU            |          Intel Core i5 - 10400(6C12T)          |
| Memory         |               2*8GB DDR4 2666MHz               |
| SSD            |                 WD-SN550 500G                  |
| Graphics       |  AMD Radeon RX590 8G / Intel UHD Graphics 630  |
| Audio          |         Realtek ALC887 AppleALC ID=12          |
| Wireless Card  |                  BCM94360CS2                   |


![](https://pic.downk.cc/item/5fa517121cd1bbb86ba890e3.png "")



## What works:

- Intel UHD Graphins 630
- AMD Radeon RX590
- Wi-Fi and Bluetooth（using `BCM94360CS2`）
- USB
- Audio
- Intel I219V12 PCI Express Gigabit Ethernet
- NVRAM

## What not woks

- Any other issues you may have can be feed back to me in Issues



Please change MLB, SystemSerialNumber, SystemUUID into your code:

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>ESIzRFVm</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac19,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```
