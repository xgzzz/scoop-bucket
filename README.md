# scoop-bucket

个人 Scoop bucket。

## 安装

```powershell
scoop bucket add xgzzz https://github.com/xgzzz/scoop-bucket
scoop install xgzzz/port-scan-rs
```

## 已收录

| 应用 | 说明 |
|---|---|
| [port-scan-rs](https://github.com/xgzzz/port-scan-rs) | 本地端口检测、网卡抓包与 pcap 分析工具（CLI + GUI） |

安装后得到两个命令：

- `port-scan-rs` —— 零依赖版本
- `port-scan-rs-full` —— 额外支持网卡抓包，需要自行安装 [Npcap](https://npcap.com/#download)

## 更新

```powershell
scoop update
```
