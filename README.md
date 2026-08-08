# Openwrt For Old PC/Laptop AMD/ATI

### ⚠️ Hardware Compatibility Note

This custom OpenWrt x86_64 firmware is specifically optimized for legacy PCs and laptops equipped with older AMD/ATI IDE interfaces, such as the **Advanced Micro Devices, Inc. [AMD/ATI] IXP SB4x0 IDE Controller (rev 80)**.

Standard OpenWrt images often fail to boot on this hardware (stuck at "waiting for root device") because they lack the necessary built-in ATA/PATA drivers. This repository patches the kernel to include these essential drivers natively (`=y`), ensuring a smooth and successful boot process on older machines.
