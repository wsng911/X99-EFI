以下是针对该硬件的 **`README.md`** 文档建议，采用清晰的结构和关键信息说明：

---

# X99-EFI for 精粤 X99M-H D4 + Xeon E5-2680 v4

**适用于黑苹果（macOS）的 OpenCore EFI 配置文件**
适配硬件：精粤 X99M-H D4 主板 + Intel Xeon E5-2680 v4（Broadwell-E架构）。

## 📌 硬件兼容性
| **组件**| **型号**|
|----------------|--------------------------------------------------------------------------|
| **CPU**| Intel Xeon E5-2680 v4 (14核28线程, Broadwell-E)|
| **主板**| 精粤 X99M-H D4 (芯片组: H81)|
| **内存**| 32GB DDR4 2400MHz (需确认兼容性，建议使用非ECC内存)|
| **显卡**| AMD Radeon RX 580 (需刷写 GOP 支持 UEFI 启动)|
| **存储**| NVMe/SATA SSD (需在 BIOS 中启用 AHCI)|
| **网络**| 有线: Realtek RTL8168 (需 [驱动](https://github.com/Mieze/RTL8168)) <br> 无线: Intel AX200 (需替换为博通卡或使用 [itlwm](https://github.com/OpenIntelWireless/itlwm)) |
| **声卡**| Realtek ALC897 (Layout-ID: `11` 或 `13`)|
