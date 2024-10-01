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

- **🌟 community driven**：Developers and users are welcome to exchange OpenWrt experience and knowledge.
- **🔒 Completely open source**：Adhere to the concept of free software and support private application deployment.
- **⚡ Efficient performance**：Optimize firmware for a superior network experience.

***

## Firmware display
![Example diagram1](https://fastly.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/02.png)
![Example diagram2](https://fastly.jsdelivr.net/gh/oppen321/Lede-OpenWrt/images/01.png)


## Custom firmware
1. First log in to your Gihub account, then Fork this project to your own Github repository
2. Modify the corresponding files in the `configs` directory to add or delete plug-ins, or upload your own `xx.config` configuration file
3. For the corresponding name and function of the plug-in, please refer to Enshan netizen’s post.：[Applications add plugin app says](https://www.right.com.cn/forum/thread-3682029-1-1.html)
4. If you need to modify the default IP, add or delete plug-in packages and some other settings, please modify it in the `diy-script.sh` file
5. Add or modify the `xx.yml` file, and finally click `Actions` to run the `workflow` to be compiled to start compilation
6. Compilation takes about 3-5 hours. After the compilation is completed, download the firmware in the corresponding Tag tag on the warehouse homepage [Releases](https://github.com/oppen321/Lede-OpenWrt/releases)

## Acknowledgments

Special thanks to the following projects for their support of this project:

- [LEDE](https://github.com/coolsnowwolf)：Provide stable source code support.
- [haibo](https://github.com/haiibo)：Provides useful YAML compilation templates.

### Contributor
| [LEDE](https://github.com/coolsnowwolf) | [haibo](https://github.com/haiibo) |
| :-------------: | :-------------: |
| <img width="100" src="https://avatars.githubusercontent.com/u/31687149"/> | <img width="100" src="https://avatars.githubusercontent.com/u/85640068?v=4"/> |


