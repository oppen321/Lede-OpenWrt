<p align="center">
<img src="https://fastly.jsdelivr.net/gh/oppen321/static@main/images/Lede_OpenWrt_bannerlogo.jpg">
</p>

<p align="center">
<b>Lede-OpenWrt</b>
</p>

<div align="center">

定制化 OpenWrt 固件，适配 x86 和 Rockchip 平台

[安装指南](https://www.example.com/install) | [文档](https://www.example.com/docs) | [❤️ 支持我们](https://www.example.com/support)

[![](https://img.shields.io/badge/blog-@LedeOpenWrt.svg)](https://www.example.com)
[![](https://img.shields.io/github/v/release/oppen321/Lede-OpenWrt)](https://github.com/oppen321/Lede-OpenWrt/releases)
[![](https://img.shields.io/github/last-commit/oppen321/Lede-OpenWrt.svg)](https://github.com/oppen321/Lede-OpenWrt/commits/main)

</div>

***

🐧 欢迎来到 Lede-OpenWrt 仓库，这里是基于 Lede 源码编译的 OpenWrt 固件。固件支持多种设备，并经过优化，确保在各种网络环境下的稳定性。

## 项目

- **👍 社区驱动，欢迎开发者和用户积极交流 OpenWrt 知识**<br>

- **🪅 完全开源，拥抱自由软件，轻松部署私有应用**<br>

- **🆙 追求强大性能和可靠性，高效享用 OpenWrt**<br>

- **📦 使用 opkg 原生安装软件包，轻松开始你的 Linux 学习之旅...**<br>

***

## 开源

Lede-OpenWrt 是基于开源的 [Lean's LEDE](https://github.com/coolsnowwolf/lede) 仓库编译的 OpenWrt 发行版。项目遵循 [GPL2.0](https://github.com/oppen321/Lede-OpenWrt/blob/main/COPYING) 协议，二次开发需要标注出处。

固件中绝不含任何后门或监控软件，保证用户数据安全。编译过程透明，任何人都可以按照说明自行编译。

![示例图](https://fastly.jsdelivr.net/gh/oppen321/static@main/images/opensource.jpg)

***

## 软件源

**😍 使用 [LedeTools](https://www.example.com/tools) 快速配置软件源，无需繁琐配置。**

请确保在使用前执行 `opkg update`，如有必要，请先清除旧的索引文件：

```bash
rm -f /var/lock/opkg.lock
