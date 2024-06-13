# ThinkPad X1 Carbon 2018 Hackintosh  
ThinkPad X1 Carbon 2018 Hackintosh EFI Files based on Opencore. Tested for macOS Monterey 12 &amp; Ventura 13

**[中文版](https://github.com/EraserCN/B450M-Hackintosh/blob/master/中文版.md)**
![Screenshot 2024-06-13 at 23.00.44](assets/Screenshot%202024-06-13%20at%2023.00.44.png)


![Screenshot 2024-06-13 at 23.01.54](assets/Screenshot%202024-06-13%20at%2023.01.54.png)


![Screenshot 2024-06-13 at 23.02.38](assets/Screenshot%202024-06-13%20at%2023.02.38.png)
![Screenshot 2024-06-13 at 23.06.13](assets/Screenshot%202024-06-13%20at%2023.06.13.png)

# My Hardware  
Components | Specifications  
------------ | -------------  
**Laptop Model** | ThinkPad X1 Carbon 6th Gen (20KG)  
**CPU** | Intel Core i5 8350U 
**WiFi** | Intel AX200  
**Ethernet** | Built-in
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
- AirDrop iDevice Discovery(can't actually transfer files though)

# What's Not Working?  
- AirDrop, SideCar (Requires a Broadcom WiFi Card)  
- Handoff from hackintosh to iDevice
- Thunderbolt 3 (Removed to save battery because I don't need TB support)

# Important Notice, Read before You Download the EFI Files⚠️⚠️⚠️

### **1.** Regenerate the SMBIOS config to fix Apple Services

You **MUST** regenerate the SMBIOS config to make Apple Services work. We recommend using the MacBookPro16,3 SMBIOS.
![截屏2024-06-13 下午11.12.32](assets/%E6%88%AA%E5%B1%8F2024-06-13%20%E4%B8%8B%E5%8D%8811.12.32.png)

