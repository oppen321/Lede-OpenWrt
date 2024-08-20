# Lede-OpenWrt 在线编译项目

![Lede-OpenWrt](https://cdn.jsdelivr.net/gh/haiibo/OpenWrt/images/openwrt.png)

## 项目简介

Lede-OpenWrt 是一个用于在线编译 Lede-OpenWrt 固件的项目，支持多种设备。通过 GitHub Actions，可以轻松定制和生成适合你需求的固件，而无需复杂的本地编译环境。

## 功能特点

- 广泛的设备支持：支持多种设备型号，用户可以根据自身需求进行配置。
- 自动化构建：每次提交后，GitHub Actions 会自动触发编译流程，生成最新的固件版本。
- 插件与主题集成：集成了丰富的插件和主题，可自由选择，满足不同用户的个性化需求。
- 每日更新：通过自动化工作流，每日拉取最新代码并构建，确保固件的前沿性。

## 使用方法

### 1. Fork 仓库

点击页面右上角的 Fork 按钮，将此仓库 Fork 到你的 GitHub 账户中。

### 2. 配置文件

在 .config 文件中设置你需要编译的设备型号和所需的插件。如果有更多个性化需求，建议修改 config.seed 文件。

### 3. 手动启动编译

进入你 Fork 后的仓库页面，添加TOKEN仓库密钥，点击 Actions 标签页，选择 Build Lede-OpenWrt 工作流，点击 Run workflow 手动启动编译流程。

### 4. 下载编译好的固件

编译完成后，固件将被自动上传至 GitHub Releases 页面。你可以直接在 Releases 中下载所需的固件。

## 注意事项

- 首次编译：Fork 后需要进入 Actions 手动启动一次编译，以激活工作流。
- 配置调整：根据需要修改 .config 文件中的插件、主题等配置，个性化你的固件。
- 编译错误处理：如遇编译错误，可通过查看 Actions 日志找到问题所在，并进行修正。

## 常见问题

### 如何选择设备型号？

你可以在 .config 文件中找到支持的设备型号列表，选择适合你设备的型号进行编译。

### 如何添加自定义插件？

在 .config 文件中找到插件部分，按照格式添加你想要的插件名称即可。

## 致谢

感谢以下项目和开发者的贡献与支持：

- [lede](https://github.com/coolsnowwolf/lede): 是OpenWrt的分支，提供了较为丰富的插件支持。
- [OpenWrt](https://openwrt.org/): 基于 OpenWrt 的社区为用户提供了丰富的功能和插件支持。
- [haibo](https://github.com/haibo): 提供了 yml 模板参考和项目灵感。
- [QiuSimons](https://github.com/QiuSimons): 为 Lede-OpenWrt 项目提供了功能扩展。
- [ImmortalWrt](https://github.com/immortalwrt/immortalwrt): 面向中国大陆用户的开源 OpenWrt 分支。

感谢这些社区和开发者的辛勤付出，让这个项目得以顺利进行和持续发展！
