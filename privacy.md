---
title: 隐私
description: NASPlayer 隐私政策
---

# 隐私政策

NASPlayer 把隐私作为设计前提：所有私人数据都只保存在你的设备上。

## 我们收集什么

**我们不收集任何用户数据。** NASPlayer 没有账号系统，没有分析服务，也没有第三方追踪 SDK。

## 本地存储的数据

以下数据只保存在你的设备上：

- **播放记录**：曲目、时间、进度、是否完成，保存在 `Application Support/PlaybackHistory.jsonl`
- **收藏与私人歌单**：保存在 `Application Support/NASPlayerLibrary/PersonalMusicLibrary.json`
- **播放位置与播放队列**：保存在 `Application Support` 目录
- **曲库索引**：按 NAS 身份隔离，保存在 `Application Support/LibraryIndexes`
- **搜索历史**：按 NAS 身份隔离，保存在 `UserDefaults`
- **受信任的证书指纹**：保存在 `UserDefaults`
- **连接凭据**：保存在系统 Keychain（仅当前设备可读）

这些数据都可以通过卸载应用清除。

## 网络流量

NASPlayer 只与以下服务通信：

- **你的 NAS**：用于认证、浏览文件夹、获取封面、播放音乐流
- **群晖 QuickConnect 服务**（`quickconnect.to` / `quickconnect.cn`）：仅在你选择 QuickConnect 时，用于发现 NAS 的可达端点

NASPlayer 不会把任何数据发送给开发者或第三方服务器。

## 证书信任

如果你的 NAS 使用自签名证书，NASPlayer 会在首次连接时显示证书 SHA-256 指纹，并要求你确认。信任仅对**该地址和端口**生效，可以随时在「受信任的 NAS 证书」中撤销。

## 数据备份

NASPlayer 保存在设备上的数据会随 iCloud / iTunes 备份一起备份。可以在系统设置中关闭对 NASPlayer 的备份。

## 更新

如果本政策发生变化，我们会更新本页面。
