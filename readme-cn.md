
# ThinkPad X1 Carbon 2018 黑苹果

基于 Opencore 的 ThinkPad X1 Carbon 2018 黑苹果 EFI 文件。已测试 macOS Monterey 12 和 Ventura 13。

**[中文版](https://github.com/EraserCN/B450M-Hackintosh/blob/master/中文版.md)**

![截图 2024-06-13 23.00.44](assets/Screenshot%202024-06-13%20at%2023.00.44.png)

![截图 2024-06-13 23.01.54](assets/Screenshot%202024-06-13%20at%2023.01.54.png)

![截图 2024-06-13 23.02.38](assets/Screenshot%202024-06-13%20at%2023.02.38.png)
![截图 2024-06-13 23.06.13](assets/Screenshot%202024-06-13%20at%2023.06.13.png)

# 我的硬件

组件 | 规格
------------ | -------------
**笔记本型号** | ThinkPad X1 Carbon 第6代 (20KG)
**CPU** | Intel Core i5 8350U
**WiFi** | Intel AX200
**以太网** | 内置
**显卡** | Intel UHD Graphics 620
**内存** | 16GB LPDDR3 2133 MHz
**存储** | 512GB WD SN580 NVME SSD
**macOS** | 12.0-14.5

# 工作正常的部分

- 所有 USB 端口
- WiFi
- 睡眠/唤醒
- HDMI 声音输出
- 笔记本扬声器声音输出
- 集成显卡
- HDMI 输出
- iMessage, FaceTime, Apple ID, iCloud 等
- Metal3 加速
- 在 FindMy 中显示设备位置
- 从其他设备向黑苹果接力
- 跨设备剪贴板
- AirDrop 设备发现（但无法实际传输文件）

# 不工作的部分

- AirDrop, SideCar（需要 Broadcom WiFi 卡）
- 从黑苹果向 iDevice 接力
- Thunderbolt 3（为了省电移除了，因为不需要 TB 支持）

# 重要通知，请在下载 EFI 文件前阅读⚠️⚠️⚠️

### **1.** 重新生成 SMBIOS 配置以修复 Apple 服务

你**必须**重新生成 SMBIOS 配置以使 Apple 服务正常工作。我们建议使用 MacBookPro16,3 的 SMBIOS。

![截屏2024-06-13 下午11.12.32](assets/%E6%88%AA%E5%B1%8F2024-06-13%20%E4%B8%8B%E5%8D%8811.12.32.png)

---