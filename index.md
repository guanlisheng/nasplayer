```markdown
---
title: 首页
description: NASPlayer —— 为群晖 NAS 打造的原生 iOS 音乐播放器
---

<section class="hero">
  <span class="pill">私有 · 无损 · 本地优先</span>
  <h1>把 NAS 上的音乐，<br>装回你的口袋。</h1>
  <p class="lead">NASPlayer 是一款为群晖（Synology）NAS 打造的原生 iOS 音乐播放器。QuickConnect 一键发现设备，支持 FLAC / ALAC / WAV / DSD / APE 等格式；播放记录、收藏与私人歌单都只保存在本机。</p>
  <div class="cta">
    <a class="btn primary" href="https://apps.apple.com/cn/app/id6823579551">App Store 下载</a>
    <a class="btn primary" href="https://testflight.apple.com/join/bT2vqAZZ">TestFlight 公开测试</a>
    <a class="btn" href="{{ '/features.html' | relative_url }}">查看全部功能 →</a>
  </div>
  <ul class="hero-meta">
    <li>🎧 后台播放 + AirPlay</li>
    <li>🔐 自签名证书指纹核对</li>
    <li>🚀 QuickConnect 自动发现</li>
    <li>📁 支持 Files 本机文件夹</li>
  </ul>
</section>

## 核心功能

<div class="features">
  <div class="card">
    <div class="card-icon">📡</div>
    <h3>QuickConnect 自动连接</h3>
    <p>一次输入 QuickConnect ID，自动发现内网直连、公网直连与中继端点，并按网络环境选择合适的连接路径。</p>
  </div>

  <div class="card">
    <div class="card-icon">🎼</div>
    <h3>完整 NAS 曲库</h3>
    <p>直接浏览群晖 Audio Station 音乐库，支持按文件夹、专辑、艺术家、流派、格式和年份探索自己的收藏。</p>
  </div>

  <div class="card">
    <div class="card-icon">🔊</div>
    <h3>无损与高解析音频</h3>
    <p>识别 FLAC、ALAC、WAV、AIFF、DSD 等音频格式，并显示实际码率与采样率；需要时可使用 NAS 端转码。</p>
  </div>

  <div class="card">
    <div class="card-icon">📁</div>
    <h3>本机文件夹与 Files</h3>
    <p>不想把所有音乐放进 NAS？可以直接选择 iPhone / iPad 上「文件」App 提供的文件夹播放，包括 iCloud Drive 和其他 File Provider。</p>
  </div>

  <div class="card">
    <div class="card-icon">▶️</div>
    <h3>统一播放器</h3>
    <p>NAS 和 Files 共用当前播放器与迷你播放器。切换来源不会让另一套来源的队列意外抢占当前播放。</p>
  </div>

  <div class="card">
    <div class="card-icon">🔁</div>
    <h3>播放队列与继续听</h3>
    <p>支持调整顺序、下一首播放、随机播放、循环播放，以及跨页面继续播放。NAS 和 Files 都可以在中断后回到之前的位置。</p>
  </div>

  <div class="card">
    <div class="card-icon">💜</div>
    <h3>收藏与私人歌单</h3>
    <p>收藏喜欢的歌曲，创建只保存在本机的私人歌单，并支持导出 / 恢复自己的歌单数据。</p>
  </div>

  <div class="card">
    <div class="card-icon">✨</div>
    <h3>重新发现你的音乐</h3>
    <p>根据本机播放历史，找回很久没听或从未播放过的歌曲。推荐基于自己的音乐习惯，不依赖第三方推荐服务。</p>
  </div>
</div>

## 两种音乐来源，一个播放器

NASPlayer 不要求所有音乐都必须放在 NAS 上。

<div class="features">
  <div class="card">
    <div class="card-icon">🗄️</div>
    <h3>你的 NAS</h3>
    <p>适合长期保存的大型私人曲库。连接群晖 NAS 后，可以建立本地索引，按专辑、艺术家、流派、格式和年份探索整个收藏。</p>
    <p>支持播放历史、收藏、私人歌单、重新发现、队列恢复等 NAS 专属功能。</p>
  </div>

  <div class="card">
    <div class="card-icon">📱</div>
    <h3>你的本机文件</h3>
    <p>直接从 iOS / iPadOS 的「文件」App 选择一个文件夹即可播放。适合临时下载的音乐、学习资料、儿童英语音频，以及不需要加入 NAS 曲库的内容。</p>
    <p>NASPlayer 保存文件夹的相对路径和播放进度，让你下次可以继续听。</p>
  </div>
</div>

### Files 支持什么？

Files 播放基于 Apple 的 File Provider / Files 系统。

因此除了「在我的 iPhone 上」之外，也可以使用设备上已经配置好的文件提供商，例如：

- iCloud Drive
- NAS 提供的 Files 文件夹
- 第三方云盘提供的文件
- 其他支持 iOS File Provider 的存储服务

NASPlayer 不需要把这些文件上传到自己的服务器。

> Files 中的文件仍由你选择的文件提供商负责保存和提供。NASPlayer 只在你授权的文件夹范围内访问文件。

## 支持的音频格式

<div class="formats">
  <span>FLAC</span><span>ALAC</span><span>WAV</span><span>AIFF</span>
  <span>MP3</span><span>AAC</span><span>M4A</span><span>OGG</span>
  <span>Opus</span><span>DSD</span><span>APE</span><span>WMA</span>
</div>

NAS 曲库中的 DSD / APE / WMA 等格式可以使用 NAS 端转码。

Files 中的文件则由 iOS 当前可用的音频能力以及 NASPlayer 对应的播放器能力处理。

## 只需四步，开始播放 NAS 音乐

1. 在 App Store 下载 **NASPlayer**。
2. 打开 App，选择 QuickConnect 或局域网 / IP。
3. 输入群晖用户名和密码完成登录。
4. 在音乐库中浏览 NAS 上的文件夹，点按即可播放。

> 需要在 NAS 上安装并启用 **Audio Station**，且曲库已建立索引。

## 不想登录 NAS？直接播放文件

NASPlayer 也可以作为一个本机 / Files 音频播放器使用。

1. 打开 NASPlayer 的 **Files**。
2. 选择「文件」App 中的一个文件夹。
3. 授权 NASPlayer 访问该文件夹。
4. 选择歌曲开始播放。
5. 下次进入 NASPlayer 时，可以从「继续听」恢复之前的位置。

Files 播放不要求登录 NAS。

文件夹授权失效、文件被移动或删除时，NASPlayer 会提示你重新选择原来的文件夹。

## 播放体验

无论音乐来自 NAS 还是 Files，都可以使用统一的播放器体验：

- 🎧 后台播放
- 🔒 锁屏播放控制
- ⏩ 15 秒跳转
- 🎵 上一首 / 下一首
- 📋 播放队列
- 🔀 随机播放
- 🔁 单曲 / 队列循环
- 📡 AirPlay
- 🎧 蓝牙耳机
- 🔊 系统音频输出切换
- ⏸️ 音频中断恢复
- 🎚️ 播放进度与当前曲目元数据

不同来源仍然保持自己的播放上下文。Files 播放不会把 NAS 队列自动恢复到当前会话中，反之亦然。

## 私人音乐库，留在你的设备上

NASPlayer 的设计目标不是再建立一个新的音乐云服务，而是帮助你更方便地使用自己已经拥有的音乐。

播放历史、收藏、私人歌单、续播位置和曲库索引都保存在设备本地。

NAS 音乐直接从你的 NAS 获取。

Files 音乐则直接从你授权的文件提供商获取。

NASPlayer 没有自己的音乐云端存储，也不要求把私人音乐上传给开发者。

详见[隐私政策]({{ '/privacy.html' | relative_url }})。
```
