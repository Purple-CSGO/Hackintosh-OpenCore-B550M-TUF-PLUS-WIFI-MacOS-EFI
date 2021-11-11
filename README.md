# Hackintosh-OpenCore-B550M-TUF-PLUS-WIFI-MacOS-EFI

## 简介


|                | Current                                        | Compatible                                     |
| ---------------- | ------------------------------------------------ | ------------------------------------------------ |
| CPU            | AMD Ryzen7 5800X                               | Ryzen CPUs (tweak according to cpu core count) |
| MotherBoard    | Asus TUF Gaming B550M-Plus (WI-FI)             | A520 & B550                                    |
| GPU            | SAPPHIRE RX6600XT 8GB                          | RX5000 Series + RX6600XT + RX6800/XT + RX6900  |
| RAM            | 32GB (4 x 8GB) Crucial C9BJZ @3800MHz C16 (OC) | All                                            |
| Audio Chipset  | ALCS-1200A                                     | Many (Change boot-arg to be compatible)        |
| NIC (Wireless) | Brcm DW1560                                    | Only This One                                  |
| Ethernet       | RTL8125 2.5GbE                                 | Only This One                                  |
| Drive          | WD SN750 512GB                                 | All (not with pm981 etc)                       |
| System         | MacOS Monterey 12.1 Beta                       | untested                                       |

- [X] Sound
- [X] Ethernet
- [X] Wifi
- [X] Bluetooth
- [X] Airdrop
- [X] GPU Optimization
- [ ] Sleep
- [ ] Sidecar (Not checked)

## 安装和使用

### CPU修改

Kernel -> Patch 中 0、1、2的Replace项要根据CPU核心数量调整，第3、4个16进制位=核心数，5600x -> `06` 5800x -> `08` 5900x -> `0C` 5950x `10`

当前为5800x，如果使用5900x

`B8080000 0000` -> `B80C0000 0000`

### 睡眠

没有定制usb，所以睡眠应该有问题，解决办法就是关闭睡眠（

## 已知问题

待定

## 致谢

待定
