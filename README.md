# Hackintosh-OpenCore-B550M-TUF-PLUS-WIFI-MacOS-EFI

## 公告

因更换显卡，现最新为rx560分支，去掉了显卡定制，加了几个kexts，删去了启动项中为RX5000系列显卡使用的`agdpmod=pikera`。

没有定制usb，所以睡眠应该有问题，解决办法就是关闭睡眠（）

## 简介


|   | 当前 | 兼容 |
| - | - | - |
| CPU | AMD Ryzen7 3700X | Ryzen CPUs |
| MotherBoard | Asus TUF Gaming B550M-Plus (WI-FI) | A520 & B550 |
| GPU | SAPPHIRE RX5500XT 8GB | RX5000 Series |
| RAM | 32GB (4 x 8GB) Crucial C9BJZ @3800MHz C16 (OC) | All |
| Audio Chipset | ALCS-1200A | Many (Change boot-arg to compat) |
| NIC (Wireless) | Brcm DW1560 | Only This One |
| Ethernet | RTL8125 2.5GbE | Only This One |
| Drive | WD SN750 512GB | All |
| System | MacOS Big Sur 11.1 | MacOS Big Sur ~11.1 |

- [X] Sound
- [X] Ethernet
- [X] Wifi
- [X] Bluetooth
- [X] Airdrop
- [X] GPU Optimization
- [ ] Sleep
- [ ] Sidecar (Not checked)

## 安装和使用

待定

## 已知问题

待定

## 致谢

待定
