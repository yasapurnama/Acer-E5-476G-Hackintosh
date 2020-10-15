# Acer E5-476G Hackintosh

## Specifications

| Accessories | Specifications | Working Status |
| :------: | :---------------------------: | :------: |
| Model | Acer E5-476G | ✅ |
| Processor | Intel Core i3-6006U @2.0GHz | ✅ |
| HD Graphics | Intel UHD Graphics 520 | ✅ |
| Discrete Graphics | NVIDIA GeForce MX130 | ❌ |
| RAM | 8GB ADATA 4GB 2400Mhz | ✅ |
| RAM | 8GB Corsair VENGEANCE DDR4 2400Mhz | ✅ |
| Solid State Drive | WD M.2 2280 240GB | ✅ |
| Mechanical Hard Drive | WD10SPZX 1TB | ✅ |
| Sound Card | Realtek ALC255 | ✅ |
| Keyboard | PS2 Keyboard | ✅ |
| Touchpad | ELAN0501 I2C | ✅ |
| Wired LAN | Realtek RTL8111 | ✅ |
| Wireless LAN | Broadcom BCM94360CS2 (Swapped) | ✅ |
| OS Version | macOS 10.15.7 Catalina | ✅ |
| SMBIOS | MacBookPro13,1 | ✅ |
| Bootloader | OpenCore 0.6.2 | ✅ |

## Configuration & Patches

- Standard OpenCore Config for SkyLake [https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/skylake.html](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/skylake.html)
- ACPI Patch via SSDTTime [https://github.com/corpnewt/SSDTTime](https://github.com/corpnewt/SSDTTime)
- Disable Unsupported GPU NVIDIA GeForce MX130
- Fix Trackpad XOSI Rename [https://dortania.github.io/Getting-Started-With-ACPI/Laptops/trackpad-methods/prebuilt.html](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/trackpad-methods/prebuilt.html)
- \*Fix ComboJack Noise (Manual Install binary needed) [https://github.com/hackintosh-stuff/ComboJack.git](https://github.com/hackintosh-stuff/ComboJack.git)
- Fix FN+Arrows Brightness Hotkey 
- \*Generate SMBIOS (Manual Generate Uniqie SMBIOS) [https://github.com/corpnewt/GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

## Working

- Intel HD Graphics 520
- Ethernet RTL8111
- Wireless, Airdrop, Instant Hotspot, Bluetooth (BCM94360CS2)
- Trackpad & Gestures
- Brightness (Controll with FN + Arrow Keys)
- VGA Port
- HDMI Port + HDMI Audio out
- USB 3.0
- Speaker + Combo Jack
- Power Management, idle @500-800MHz
- Shutdown, Restart, Sleep

## Not Working

- SD Card Reader Not Supported
- NVIDIA GeForce MX130 (Optimus)

## Credits

- dortania [https://github.com/dortania/OpenCore-Install-Guide](https://github.com/dortania/OpenCore-Install-Guide)
- acidanthera [https://github.com/acidanthera](https://github.com/acidanthera)
- CorpNewt [https://github.com/corpnewt](https://github.com/corpnewt)
- hackintosh-stuff [https://github.com/hackintosh-stuff](https://github.com/hackintosh-stuff)
- rockavoldy [https://github.com/rockavoldy/Acer-E5-476G-Hackintosh](https://github.com/rockavoldy/Acer-E5-476G-Hackintosh)
- reyzafany [https://github.com/reyzafany/Acer-E5-476G-Hackintosh](https://github.com/reyzafany/Acer-E5-476G-Hackintosh)