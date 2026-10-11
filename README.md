# ColorOSFacePass

[![Xposed](https://img.shields.io/badge/-Xposed-green?style=flat&logo=Android&logoColor=white)](#)
[![GitHub all releases](https://img.shields.io/github/downloads/Xposed-Modules-Repo/io.github.yukino1111.colorosfacepass/total?label=Downloads)](https://github.com/Xposed-Modules-Repo/io.github.yukino1111.colorosfacepass/releases)

本模块用于解决 ColorOS 下第三方应用无法使用人脸识别的问题，并跳过识别成功后的手动点击确认，同时支持按应用单独控制。

模块仅作自用分享。

## 测试环境

> ColorOS 16

## 使用方法

1. 在 Xposed 管理器 (如 LSPosed) 中激活模块
2. 勾选作用域
3. 重启设备
4. 打开应用勾选需要允许调用人脸识别的软件

## 免责声明

- 本模块在提升便利性的同时会降低安全性，**请谨慎启用并自行评估安全风险；强烈建议不要对涉及资金、支付、转账等敏感金融类应用开启本模块；**
- **本项目仅供个人学习、研究与自用分享**，因使用本模块造成的任何设备故障、数据丢失或安全损失，**作者概不承担责任**。

## 致谢

本模块基于以下开源项目借鉴与整合：  
[biometric-bypass](https://github.com/hxreborn/biometric-bypass)（起步 Commit: [`c710ac8`](https://github.com/hxreborn/biometric-bypass/commit/c710ac84dd65ae81a70475b03fd572e87a4045fd)）  
[FaceBiometricFix](https://github.com/WAYYYAW/FaceBiometricFix)（起步 Commit: [`6462515`](https://github.com/WAYYYAW/FaceBiometricFix/commit/64625153e66ac48369656c528168cf2821ee5d9d)）  
模块使用 [LibXposed](https://github.com/libxposed/api) 构建
