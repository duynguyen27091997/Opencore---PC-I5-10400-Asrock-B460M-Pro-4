# PC-I5-10400-Asrock-B460M-Pro-4

This build running on MacOs X

# System specification

```
  Main:  ASROCK B460M PRO4
  CPU:   Intel Core i5-10400
  Ethernet:  Intel® Gigabit LAN
  Ram:   16GB
  Graphic:   Intel UHD630 onboard
  Wifi, Bluetooth:   Intel Wifi 6 Card (I has bought after built this shit)
```

------------------------------------------------------------------------------
<ul>
  <li>Display: DisplayPort , HDMI: Ok</li>
  <li>Audio Realtek ALC1200: OK</li>
  <li>Ethernet: OK</li>
  <li>Sleep,Wake: OK</li>
  <li>All USB ports (Full 3.0 + 2.0 + type C): OK</li>
  <li>If you need Wifi please add <a href="https://github.com/OpenIntelWireless/itlwm">Itlwm</a></li>
</ul>

# Step to install

<ol>
  <li>Mount EFI partition </li>
  <li>Copy folder EFI to EFI partition</li>
  <li>Gen SMBIOS <a href="https://github.com/corpnewt/GenSMBIOS" target="_blank">Link</a></li>
  <li>Enjoy</li>
</ol>

# Gen SMBIOS

Please change MLB, SystemSerialNumber, SystemUUID as your desire.

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>xxxxxxxx</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac20,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```