[English](./README_EN.md)| [中文](./README.md) 

# OrangePi 3 LTS 镜像

## 项目简介
本项目旨在分享一些非官方的 OrangePi 3 LTS 可用镜像。这些镜像经过测试，适用于 OrangePi 3 LTS 开发板，帮助用户快速部署和使用。

## 特性
- 提供多种操作系统镜像，包括 Kali Linux 和 Raspberry Pi OS。
- 易于下载和使用。
- 持续更新，满足不同用户需求。

## 发布版本
### 最新版本
- **vx.1**: 更新 Kali Linux 镜像，适用于安全测试和开发。
- **vx.2**: 更新 Raspberry Pi OS 镜像，适用于通用开发和学习。
- **vx.2**：更新FnNAS的 镜像，适用于NAS设备

### 其他版本
- 更多版本信息请访问 [Releases 页面](https://github.com/FPS1024/OrangePi3LTS-images/releases)。

## 文件结构
```
LICENSE
README.md
dts/
    sun50i-h6-orangepi-3-lts.dtb
    sun50i-h6-orangepi-3-lts.dts
u-boot/
    u-boot-sunxi-with-spl.bin
```
- `dts/`: 包含设备树文件。
- `u-boot/`: 包含 U-Boot 引导加载程序。

## 使用方法
1. 下载所需的镜像文件。
2. 使用工具（如 `Etcher`）将镜像烧录到 SD 卡或 eMMC。
3. 将 SD 卡插入 OrangePi 3 LTS 开发板并启动。

## 许可证
本项目采用 [Unlicense](./LICENSE) 许可证，详情请查看 LICENSE 文件。

## 贡献
欢迎提交 Issue 或 Pull Request 来改进本项目。

## 联系方式
如有任何问题，请通过 GitHub Issues 联系我们。
