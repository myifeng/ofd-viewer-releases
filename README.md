# OFD 阅读器 · OFD Viewer

> 一款免费、纯本地、完全离线的跨平台 **OFD 阅读器（OFD 查看器）**
> A free, fully offline, cross-platform **OFD reader (OFD viewer)**

[中文](#中文) · [English](#english)

---

## 中文

**ofd-view** 是一款免费、纯本地、完全离线的 **OFD 阅读器**（也称 OFD 查看器 / OFD 阅读软件），用于打开、阅读、检索、打印、导出并验签国标 **OFD 文档（GB/T 33190-2016）**。适用于电子发票、数电票、公文、证照、票据等场景，支持 **Windows、macOS、Linux**。

本地解析、本地渲染：文件始终留在你的电脑上，全程不联网、不上传任何内容，隐私安全、可靠。

### 功能特性

| 分类 | 能力 |
| --- | --- |
| 打开 | 多选打开、拖拽打开、命令行/第二次启动唤起、最近文件、会话恢复、多标签、多窗口（Ctrl+N） |
| 阅读 | 连续滚动虚拟列表、单页/双页、翻页（首页/上一页/下一页/末页、页码跳转、PgUp/PgDn/Home/End） |
| 查找 | Ctrl+F 全文检索、命中高亮、上一个/下一个 |
| 文本 | 文档文本可选、可复制（按语义重建，去除逐字换行） |
| 视图 | 缩放 10%–500%（预设/滑块/适应宽度/适应页面/实际大小、Ctrl+滚轮）、左右旋转、全屏（F11） |
| 签章 | 点击印章查看验签信息（结果/提供者/算法/时间/机构/印章编号/有效期/证书数量） |
| 导出 | 打印、另存为 PDF、当前页导出 PNG / JPEG / WebP |
| 设置 | 主题（跟随系统/浅色/深色）、语言（中文/English）、会话恢复、窗口边界记忆 |
| 健壮性 | 解析错误分级提示；单页渲染失败自动降级占位，不白屏 |

### 性能

- 按需渲染 + 虚拟滚动 + 渲染缓存：只渲染可见页，大文档依旧流畅
- 常规 100 页发票/公文类 OFD 打开约 ≤ 2 秒，滚动 ≥ 30 fps
- 缩放与旋转只改变渲染比例与定位，无需重新解析

### 本地解析，安全可靠

- 纯本地、完全离线运行，绝不发起网络请求
- 文件内容不上传、不外泄，全程留在本机
- 解析、渲染与电子签章验签均在本地完成
- 严格的 CSP（`script-src 'self'`，无 `unsafe-eval`）

### 下载

前往 [Releases](https://github.com/myifeng/ofd-view-releases/releases/latest) 获取最新版本：

- Windows (x64)：`*setup.exe`
- macOS：`*x64.dmg`（Intel）· `*arm64.dmg`（Apple Silicon）
- Linux (x64)：`*.AppImage` · `*.deb`

### 适用场景

电子发票、数电票、税务票据、电子公文、电子证照、合同、标书及各类国标 OFD 文档的查看与打印。

### 关键词

OFD阅读器, OFD查看器, OFD阅读软件, OFD浏览器, 免费OFD, 打开OFD文件, OFD转PDF, OFD转图片, OFD打印, 电子发票阅读器, 数电票阅读器, 电子发票OFD, 国标OFD, GB/T 33190-2016, 电子签章验签, SM2验签, 跨平台, Windows, macOS, Linux, 离线, 本地解析, 隐私安全

---

## English

**ofd-view** is a free, fully offline, cross-platform **OFD reader** (OFD viewer) for opening, reading, searching, printing, exporting and signature-verifying Chinese national-standard **OFD documents (GB/T 33190-2016)**. It suits electronic invoices, e-invoices, official documents, certificates and tax receipts, with builds for **Windows, macOS and Linux**.

Everything is parsed and rendered locally: your files stay on your computer, with no network access and nothing ever uploaded.

### Features

| Area | Capability |
| --- | --- |
| Open | Multi-select open, drag & drop, command-line / second-instance, recent files, session restore, multi-tab, multi-window (Ctrl+N) |
| Reading | Continuous virtual-scroll list, single/double page, page navigation (first/prev/next/last, jump-to-page, PgUp/PgDn/Home/End) |
| Search | Ctrl+F full-text search with hit highlighting, previous/next |
| Text | Selectable, copyable document text (semantic reflow, no per-character line breaks) |
| View | Zoom 10%–500% (presets/slider/fit width/fit page/actual size, Ctrl+wheel), rotate left/right, fullscreen (F11) |
| Signature | Click a seal to view verification details (result/provider/algorithm/time/authority/seal no./validity/cert count) |
| Export | Print, Save as PDF, export current page to PNG / JPEG / WebP |
| Settings | Theme (system/light/dark), language (Chinese/English), session restore, window bounds memory |
| Robustness | Graded parse-error messages; failed page renders degrade to a placeholder instead of a blank screen |

### Performance

- On-demand rendering + virtual scrolling + render cache: only visible pages are rendered, keeping large documents smooth
- A typical 100-page invoice/official OFD opens in about ≤ 2s with ≥ 30 fps scrolling
- Zoom and rotation only change render scale and position — no re-parsing

### Local parsing, safe and reliable

- Fully offline, no network requests at all
- Files are never uploaded or leaked; everything stays on your machine
- Parsing, rendering and digital-signature verification all run locally
- Strict CSP (`script-src 'self'`, no `unsafe-eval`)

### Download

Get the latest build from [Releases](https://github.com/myifeng/ofd-view-releases/releases/latest):

- Windows (x64): `*setup.exe`
- macOS: `*x64.dmg` (Intel) · `*arm64.dmg` (Apple Silicon)
- Linux (x64): `*.AppImage` · `*.deb`

### Use cases

Viewing and printing of Chinese e-invoices, electronic invoices, tax receipts, official documents, certificates, contracts, tenders and other GB/T 33190-2016 OFD documents.

### Keywords

OFD reader, OFD viewer, OFD reader for Windows, open OFD file, free OFD reader, OFD to PDF, OFD to image, OFD printer, electronic invoice viewer, Chinese e-invoice reader, GB/T 33190-2016, digital signature verification, SM2, cross-platform, Windows, macOS, Linux, offline, local parsing, privacy
