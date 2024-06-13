# ThinkPad X1 Carbon 2018 Hackintosh  
ThinkPad X1 Carbon 2018 Hackintosh EFI Files based on Opencore. Tested for macOS Monterey 12 &amp; Ventura 13

**[中文版](https://github.com/EraserCN/B450M-Hackintosh/blob/master/中文版.md)**



![IMAGE 2024-04-24 14:57:47](https://github.com/EraserCN/B450M-Hackintosh/assets/79615365/2a1c7a2b-dd13-47c0-92f3-fb6befb98146)

# My Hardware  
Components | Specifications  
------------ | -------------  
**Laptop Model** | ThinkPad X1 Carbon 6th Gen (20KG)  
**CPU** | Intel Core i5 8350U 
**WiFi** | Intel AX200  
**Ethernet** | Untested
**Graphics** | Intel UHD Graphics 620  
**RAM** | 16GB LPDDR3 2133 MHz  
**Storage** | 512GB WD SN580 NVME SSD
**macOS** | 12.0-14.5 
  
# What's Working?  
- All USB Ports   
- WiFi  
- Sleep/Wake  
- Sound output via HDMI  
- Sound output via Laptop Speakers
- Integrated Graphics  
- HDMI Output  
- iMessage, FaceTime, Apple ID, iCloud, etc.  
- Metal3 acceleration  
- Display device location in FindMy
- Handoff from other devices to Hackintosh
- Cross-device clipboard

# What's Not Working?  
- AirDrop, SideCar (Requires a Broadcom WiFi Card)  
- Handoff from hackintosh to iDevice

# What's Untested?  
- Thunderbolt 3

# Important Notice, Read before You Download the EFI Files⚠️⚠️⚠️

### **1.** Regenerate the SMBIOS config to fix Apple Services

You **MUST** regenerate the SMBIOS config to make Apple Services work. We recommend using the MacBookPro15,2 SMBIOS.

