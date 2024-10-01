<p align="center">
<img src="https://cdn.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/OpenWrt.png">
</p>

<div align="center">
  

Customized OpenWrt firmware, adapted to x86 and Rockchip platforms

[![](https://img.shields.io/badge/x86-Download%20X86_64-blue)](https://github.com/oppen321/Lede-OpenWrt/releases/tag/X86_64)
[![](https://img.shields.io/badge/Rockchip-Download%20Rockchip-green)](https://github.com/oppen321/Lede-OpenWrt/releases/tag/Rockchip)


</div>

***

🐧 Welcome to the Lede-OpenWrt repository, which is designed to provide users with efficient and stable OpenWrt firmware, supporting a variety of devices.

## Open source instructions

Lede-OpenWrt is compiled based on [Lean's LEDE](https://github.com/coolsnowwolf/lede), and all codes and modifications are open source. Keep your data safe and the compilation process transparent.

## Project Highlights

- **🌟 community driven**：欢迎开发者和用户交流 OpenWrt 经验与知识。
- **🔒 Completely open source**：坚守自由软件理念，支持私有应用部署。
- **⚡ Efficient performance**：优化固件以实现卓越的网络体验。

***

## Firmware display
![Example diagram1](https://fastly.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/02.png)
![Example diagram2](https://fastly.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/01.png)


## Custom firmware
1. First log in to your Gihub account, then Fork this project to your own Github repository
2. Modify the corresponding files in the `configs` directory to add or delete plug-ins, or upload your own `xx.config` configuration file
3. For the corresponding name and function of the plug-in, please refer to Enshan netizen’s post.：[Applications add plugin app says](https://www.right.com.cn/forum/thread-3682029-1-1.html)
4. 如需修改默认 IP、添加或删除插件包以及一些其他设置请在 `diy-script.sh` 文件内修改
5. 添加或修改 `xx.yml` 文件，最后点击 `Actions` 运行要编译的 `workflow` 即可开始编译
6. 编译大概需要3-5小时，编译完成后在仓库主页 [Releases](https://github.com/oppen321/Lede-OpenWrt/releases) 对应 Tag 标签内下载固件

## 鸣谢

特别感谢以下项目对本项目的支持：

- [LEDE](https://github.com/coolsnowwolf)：提供稳定的源码支持。
- [haibo](https://github.com/haiibo)：提供有用的YAML编译模板。

### 贡献者
| [LEDE](https://github.com/coolsnowwolf) | [haibo](https://github.com/haiibo) |
| :-------------: | :-------------: |
| <img width="100" src="https://avatars.githubusercontent.com/u/31687149"/> | <img width="100" src="https://avatars.githubusercontent.com/u/85640068?v=4"/> |


