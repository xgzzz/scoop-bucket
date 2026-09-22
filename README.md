# scoop-bucket

个人 Scoop bucket。

## 安装

```powershell
scoop bucket add xgzzz https://github.com/xgzzz/scoop-bucket
scoop install xgzzz/port-scan-rs
scoop install xgzzz/beardown
```

## 已收录

| 应用 | 说明 |
|---|---|
| [port-scan-rs](https://github.com/xgzzz/port-scan-rs) | 本地端口检测、网卡抓包与 pcap 分析工具（CLI + GUI） |
| [BearDown](https://github.com/xgzzz/BearDown) | 多线程断点续传下载器 + 深色 GUI（CLI + GUI，含 yt-dlp 视频源） |

安装后得到命令：

- `port-scan-rs` / `port-scan-rs-full` —— 端口工具（full 需 [Npcap](https://npcap.com/#download)）
- `beardown` —— 下载器 CLI；桌面快捷方式「BearDown」指向 `beardown-gui.exe`

## 更新

```powershell
scoop update
```

> 各 manifest 内置 `autoupdate` + `checkver`；仓库每日 03:23 UTC 定时任务
> （`.github/workflows/checkver.yml`）拉取上游最新 GitHub Release，自动更新
> version / url / hash 并提交。
