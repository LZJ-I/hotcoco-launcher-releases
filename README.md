# HotCoco 启动器

[下载最新启动器](https://github.com/LZJ-I/hotcoco-launcher-releases/releases/latest)

本仓库专门分发 Windows 启动器本体。每个正式 Release 提供：

- `HotCoco.exe`：启动器。
- `hotcoco-launcher-update.json`：供启动器读取的签名更新清单。
- `SHA256SUMS.txt`：文件校验值。

26.6 起内置更新提示和下载进度，使用 [GH-Proxy](https://gh-proxy.com/) 的国内推荐加速通道；玩家无需配置 GitHub Key。下载后校验发布签名与文件，保留当前 EXE 文件名，更新完成后自动重启。

26.5 及更早版本需先手动替换一次 EXE。游戏、Mod、材质、光影和玩家设置继续使用各自现有流程，本仓库不分发这些文件。

HotCoco 基于 [HMCL](https://github.com/HMCL-dev/HMCL) 开发，遵循 GPL-3.0-or-later。
