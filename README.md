# EFI-OpenCore-DELL-5577

基于[OpenCore-For-DELL-5577 20200709版本](https://github.com/wgggSg/OpenCore-For-DELL-5577)修改，升级到 `OpenCore 0.6.3`，从 `Catalina` 完美升级到 `Big Sur`。

## 硬件配置

 硬件类型|型号
 ---- | ----- 
 笔记本型号|Dell 5577 (Inspiron 15pr-R3648B)
 CPU|Intel Core i5-7300HQ（HD630）
 内存（扩容）|自带 + 金士顿DDR4 2400Mhz
 SSD（扩容）|SAMSUNG 860QVO SATA 3.0 1TB
 独显（***屏蔽***）|NVIDIA GTX1050 4G
 板载网卡|Realtek RTL8168H/8111H PCI Express Gigabit Ethernet
 无线网卡（更换）|DW 1820A/BCM94350ZAE NGFF 802.11ac Wireless Network Adapter
 声卡|Realtek ALC 256
 显示屏 | 原装

## 使用方法

直接复制 `Boot` 和 `OC` 文件夹到 `EFI` 目录，`EFI` 目录下其他多余的文件删除