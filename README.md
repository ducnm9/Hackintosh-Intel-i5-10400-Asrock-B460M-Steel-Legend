# Hackintosh-Intel-i5-10400-Asrock-B460M-Steel-Legend

# Info PC
```
Main: Asrock b460m steel legend
CPU: Intel® Core™ i5-10400
Ram: 32GB (2x16GB - 3000) Gskill
VGA: GIGABYTE AMD Radeon™ RX 5700 8GB
PSU: Super Flower Leadex III Gold 850W
SSD: Samsung 970 evo plus 256
Card Wifi + Blutooth: Card wifi Apple chipset Broadcom BCM94331CD + Bluetooth 4.0- PCI Express x 1 N dual band 5 Ghz 
Case: Case NZXT H500 MATTE (Mid Tower/White)
Fan CPU: Jonsbo CR-1000GT ARGB Sync
FAN Case: Fan Case Coolmoon X Led RGB Dual Ring Hub Music X4 Và Remote
```

# Guide Hackintosh + OpenCore
- https://dortania.github.io/OpenCore-Desktop-Guide


# Version Hackintosh + OpenCore (OpenCore 0.5.9 - macOS Catalina)
- [See more](/OpenCore_059_macOS_Catalina)

# [21/11/2020] Version Hackintosh + OpenCore (OpenCore 0.6.3 - macOS Big Sur)
- [See more](/OpenCore_063_macOS_Big_Sur)


# Everything Works
- Continuity:
    - Handoff
    - iMessage
    - Air Drop
- Sleep
- Wake
- Audio (select internal speakers)
- Ethernet
- Bluetooth
- WiFi
- All USB ports (Full 3.0 + 2.0 + type C)

Note: Realtek 8125 Ethernet card required to manually set to 100baseTx to work
![Realtek 8125 Ethernet](/images/net.png)

# Result
![Info](/images/infomac.png)

# Benchmarks
Geekbench 5.1

![Geek1](/images/penmax1.png)

![Geek2](/images/penmax1.png)

# Note For You
The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID into your code

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