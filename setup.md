---
title: 快速开始
description: 如何连接你的 NAS 并开始播放
---

# 快速开始

## 准备工作

- 一台运行 **DSM 6.x / 7.x** 并已安装 **Audio Station** 的群晖 NAS
- 一个可用的群晖账号
- 一台 iOS / iPadOS 设备
- （可选）如果 NAS 使用自签名证书，准备好核对证书指纹

## 步骤一：下载 NASPlayer

前往 App Store 搜索 **NASPlayer** 下载安装。

## 步骤二：连接 NAS

打开 App 后会看到登录页：

1. 选择连接方式：
   - **QuickConnect**：输入你的 QuickConnect ID
   - **局域网 / IP**：输入 NAS 的 IP 地址与端口（默认 `5001`）
2. 输入群晖用户名和密码。
3. 点击「连接 NAS」。

如果使用 HTTPS 并遇到自签名证书，App 会显示证书 SHA-256 指纹，请先在 DSM 管理界面核对后再选择「核对后信任」。

## 步骤三：开始播放

1. 登录成功后进入「音乐库」。
2. 选择一个文件夹进入。
3. 点按歌曲，或使用「全部播放」按钮播放整个文件夹。

## 常见问题

### 无法连接 QuickConnect

- 确认 QuickConnect ID 拼写正确
- 确认 NAS 上已启用 QuickConnect
- 尝试切换到局域网 / IP 方式

### 连接后提示证书错误

- 在 DSM 中打开「控制面板 → 安全性 → 证书」查看当前证书指纹
- 与 App 中显示的 SHA-256 指纹逐位比对
- 只有在你确认这是你的 NAS 时才选择信任

### 播放时提示格式不支持

- DSD、APE、WMA 等格式 AVPlayer 不能原生播放
- 在播放设置中开启「尝试 DSD / APE 直通（实验）」，或切换为「高质量转码」
