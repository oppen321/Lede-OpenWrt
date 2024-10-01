<p align="center">
<img src="https://cdn.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/OpenWrt.png">
</p>

<div align="center">
  
定制化 OpenWrt 固件，适配 x86 和 Rockchip 平台

[![](https://img.shields.io/badge/blog-@LedeOpenWrt.svg)](https://www.example.com)
[![](https://img.shields.io/github/v/release/oppen321/Lede-OpenWrt)](https://github.com/oppen321/Lede-OpenWrt/releases)
[![](https://img.shields.io/github/last-commit/oppen321/Lede-OpenWrt.svg)](https://github.com/oppen321/Lede-OpenWrt/commits/main)

</div>

***

🐧 欢迎来到 Lede-OpenWrt 仓库，专为用户提供高效、稳定的 OpenWrt 固件，支持多种设备。

## 开源说明

Lede-OpenWrt 是基于 [Lean's LEDE](https://github.com/coolsnowwolf/lede) 编译而成，所有代码和修改均开放源代码。确保您的数据安全，编译过程透明。

## 项目亮点

- **🌟 社区驱动**：欢迎开发者和用户交流 OpenWrt 经验与知识。
- **🔒 完全开源**：坚守自由软件理念，支持私有应用部署。
- **⚡ 高效性能**：优化固件以实现卓越的网络体验。

***

## 固件展示
![示例图1](https://fastly.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/02.png)
![示例图2](https://fastly.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/01.png)
***

## 定制固件 [![](https://img.shields.io/badge/-项目基本编译教程-FFFFFF.svg)](#定制固件-)
1. 首先要登录 Gihub 账号，然后 Fork 此项目到你自己的 Github 仓库
2. 修改 `configs` 目录对应文件添加或删除插件，或者上传自己的 `xx.config` 配置文件
3. 插件对应名称及功能请参考恩山网友帖子：[Applications 添加插件应用说明](https://www.right.com.cn/forum/thread-3682029-1-1.html)
4. 如需修改默认 IP、添加或删除插件包以及一些其他设置请在 `diy-script.sh` 文件内修改
5. 添加或修改 `xx.yml` 文件，最后点击 `Actions` 运行要编译的 `workflow` 即可开始编译
6. 编译大概需要3-5小时，编译完成后在仓库主页 [Releases](https://github.com/oppen321/Lede-OpenWrt/releases) 对应 Tag 标签内下载固件
