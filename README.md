![](http://images.0xffff.run/20200407211040.png)

## 硬件列表

| 名称 | 品牌型号 |
| --- | --- |
| CPU | Intel Core i5 9400 |
| 主板 | Asrock Z390 Phantom Gaming itx/ac |
| 内存 | AData DDR4 3200 16GB x 2 |
| 硬盘 | 西数 SN550 M.2 500G<br />Toshiba TR200 SATA 1T |
| 显卡 | Sapphire RX5500XT 8G D6 白金版OC |
| 无线网卡/蓝牙 | 博通 BCM94360CS2 + 转接卡 |
| 显示器 | LG 27UL550 4k HDR10 IPS |

## 当前系统版本

macOS Catalina 10.15.4

## 兼容情况

- [x] BIOS 版本
    - [x] 1.5
- [x] macOS 版本
    - [x] 10.15.4
- [x] 显卡
    - [x] AMD RX5700 XT
- [x] 声卡(Realtek ALC1220)
    - [x] 主板后置
    - [x] 机箱前置
    - [x] DisplayPort 声音输出
- [x] 睡眠/唤醒
- [x] 有线网卡
- [x] 无线 WiFi
- [x] 蓝牙
    - [x] 耳机
    - [x] Trackpad 2
    - [x] Airdrop
    - [x] Handoff
- [x] 所有 USB 插口

---

- [ ]  雷电 3 口 - 可充电无数据（可用不完美）
- [ ] Sidecar (未知)

## BIOS设置

开机 F2 进入 BIOS 再按 F6 切换高级模式，至少需要做如下修改具体情况还需要看硬件情况：

- 高级（Advanced） > 芯片配置（Chipset Configuration） > **VT-d** -> Disabled
- 高级（Advanced） > USB 配置（USB Configuration） > **XHCI Hand-off** -> Enabled

## 感谢大佬

- CLOVER：https://github.com/icyleaf/EFI-ASRock-Z390-Phantom-Gaming-ITX
- OpenCore：https://github.com/zanderzhng/EFI_Asrock_Z390_Phantom_ITX_OC
