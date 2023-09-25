# 中文简体 | [English](https://github.com/DHDAXCW/NanoPi-R4S-2021/blob/main/EngLish.md) <img src="https://img.shields.io/github/downloads/DHDAXCW/NanoPi-R2S-rk3328/total.svg?style=for-the-badge&color=32C955"/>
# NanoPi-R2S-2021 每天自动更新插件和内核版本。
# 机场推荐 [ENET--IEPL内网专线接入](https://www.easy2023.com/#/register?code=Ut7iWMrk)
## 👉使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！👈
## 未经许可不得用于任何商用用途。

### 源代码地址
- lede https://github.com/DHDAXCW/lede-rockchip
- Luci https://github.com/DHDAXCW/luci
- packages https://github.com/DHDAXCW/packages

### 固件分类 在[releases](https://github.com/DHDAXCW/NanoPi-R2S-rk3328/releases)有备注关键词
- 正式版（含超频）对折腾的，可以选择，电压一定要考虑。超频都是升压的，会造成不稳定的。比如跑cpu测试容易升压等。
- Docker版 含Docker插件，会导致udp转发失效 慎用哦，只要别开passwall的udp，啥都不影响使用！
- 稳定版 含有日常使用插件
- 此版本取消了精简版，改为稳定版
- 风扇链接 [点击进入](https://s.click.taobao.com/t?e=m%3D2%26s%3Dd8Ack0Lbx8McQipKwQzePOeEDrYVVa64LKpWJ%2Bin0XJRAdhuF14FMXpyNmcFd6mT8sviUM61dt2T0mcOGN1M6FAj1gqltKaEfKzCcEr0EW0YuhTK3FPxiHMT7yc3NZrQKSOkJV8harV3phaPbavinqGCwVfdcN0wcSpj5qSCmbA%3D)  建议用这种风扇

### 固件格式
- **ext4:** 固件文件名中带有 ext4 字样的文件为搭载 ext4 文件系统固件ext4 格式的固件更适合熟悉 Linux 系统的用户使用，在 Linux 下可以比较方便地调整 ext4 分区的大小;
- **squashfs:** 固件文件名中带有 squashfs 字样的文件为搭载 squashfs 文件系统固件而 squashfs 格式的固件适用于“不折腾” 的用户，其优点是可以比较方便地进行系统还原哪怕你一不小心玩坏固件，只要还能进入控制面板或 SSH就可以很方便地进行“系统还原操作”。

### 注：不要用恢复备份。。不保证某个插件是否正常运行。。。建议重新设置贼好！


### 默认编译  

- 电报群：https://t.me/DHDAXCW
# 在线升级
- 复制以下代码，在TTYD终端执行，过程中不得离开，否则还得重新下载，请刷ext4格式明天再升级

# 插件展示
 ![Alt text](data/20.jpg?raw=true "Title")

## 鸣谢

特别感谢以下项目：

Openwrt 官方项目：

<https://github.com/openwrt/openwrt>

Lean 大的 Openwrt 项目：

<https://github.com/coolsnowwolf/lede>

immortalwrt 的 OpenWrt 项目：

<https://github.com/immortalwrt/immortalwrt>

P3TERX 大佬的 Actions-OpenWrt 项目：

<https://github.com/P3TERX/Actions-OpenWrt>

SuLingGG 大佬的 Actions 编译框架 项目：

https://github.com/SuLingGG/OpenWrt-Rpi
