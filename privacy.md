---
title: 隐私
description: NASPlayer 隐私政策
---

# 隐私政策

NASPlayer 把隐私作为设计前提：**你的私人音乐数据默认留在你的设备、你的 NAS 或你自己选择的文件存储服务中。**

NASPlayer 不提供自己的音乐云存储，也不要求将私人音乐上传到开发者服务器。

## 我们收集什么

**我们不收集任何用户数据。**

NASPlayer 没有账号系统，没有分析服务，也没有第三方追踪 SDK。

## 本地存储的数据

以下数据只保存在你的设备上：

- **播放记录**：曲目、时间、进度、是否完成，保存在 `Application Support/PlaybackHistory.jsonl`
- **收藏与私人歌单**：保存在 `Application Support/NASPlayerLibrary/PersonalMusicLibrary.json`
- **播放位置与播放队列**：保存在 `Application Support` 目录
- **曲库索引**：按 NAS 身份隔离，保存在 `Application Support/LibraryIndexes`
- **搜索历史**：按 NAS 身份隔离，保存在 `UserDefaults`
- **受信任的证书指纹**：保存在 `UserDefaults`
- **NAS 连接凭据**：保存在系统 Keychain（仅当前设备可读）
- **Files 文件夹续播信息**：包括授权文件夹的相对路径、文件定位信息和本机播放进度

这些数据由 NASPlayer 在设备本地管理。

卸载应用后，应用沙盒中的这些数据会被系统删除。

## Files 中的文件

NASPlayer 支持 iOS / iPadOS 的 Files 和 File Provider。

例如你可以选择：

- iCloud Drive
- 在我的 iPhone / iPad 上
- NAS 提供的文件夹
- 第三方云盘
- 其他支持 File Provider 的存储服务

NASPlayer 不拥有这些文件，也不会把这些文件复制到自己的服务器。

文件仍由你选择的文件提供商负责保存和同步。

NASPlayer 只在你明确选择并授权的文件夹范围内访问文件。

## 网络流量

NASPlayer 只在实际使用相应功能时访问必要的服务。

### 你的 NAS

用于：

- NAS 身份认证
- 浏览文件夹
- 获取音乐信息
- 获取封面
- 建立曲库索引
- 获取音乐流
- 请求 NAS 端转码
- 使用 Audio Station API
- 控制远程播放器

### 群晖 QuickConnect

如果你选择 QuickConnect，NASPlayer 可能与群晖 QuickConnect 服务：

- `quickconnect.to`
- `quickconnect.cn`

通信，用于发现 NAS 的可达端点。

QuickConnect 服务用于连接发现；NASPlayer 不会将你的播放历史、私人歌单等个人音乐数据上传给开发者。

### Files / File Provider

如果你从 Files 选择文件夹，NASPlayer 会通过 Apple 提供的 Files / File Provider 系统访问该文件夹。

实际文件传输由对应的文件提供商负责。

例如：

- 使用 iCloud Drive 时，文件由 Apple 的 iCloud 服务提供
- 使用第三方云盘时，文件由该云盘服务提供
- 使用本机文件夹时，文件只存在于设备本地

NASPlayer 不会把这些文件再上传到 NASPlayer 自己的服务器。

## 我们不会做什么

NASPlayer：

- 不上传你的音乐文件到开发者服务器
- 不上传播放历史
- 不上传私人歌单
- 不上传收藏
- 不建立云端个人音乐库
- 不使用第三方广告 SDK
- 不使用第三方用户追踪 SDK
- 不通过开发者服务器代理你的音乐流

## 证书信任

如果你的 NAS 使用自签名证书，NASPlayer 会在首次连接时显示证书 SHA-256 指纹，并要求你确认。

信任仅对**该地址和端口**生效，可以随时在「受信任的 NAS 证书」中撤销。

## 数据备份

NASPlayer 保存在设备上的数据可能随 iCloud / iTunes 备份一起备份，具体取决于系统的应用备份设置。

私人歌单和播放记录等本地数据不会因为 NASPlayer 没有云端账号而自动同步到其他设备。

如果你希望迁移私人歌单，可以使用 App 提供的文件导出 / 恢复功能。

## 多 NAS 数据隔离

如果设备连接多个 NAS，NASPlayer 会根据稳定的 NAS 身份区分：

- 播放历史
- 收藏
- 私人歌单
- 续播位置
- 搜索历史
- 推荐
- 曲库索引

切换 NAS 不会将一个 NAS 的私人音乐数据误显示到另一个 NAS。

## 更新

如果本政策发生变化，我们会更新本页面。

最后更新：2026-11-12
