# Friday

Friday macOS 客户端的公开下载与更新仓库。源码保存在独立仓库，这里只提供安装包、更新文件和版本说明。

- [下载最新版本](https://github.com/pubinfo-labs/friday-release/releases/latest)
- [查看所有版本](https://github.com/pubinfo-labs/friday-release/releases)
- [加入 Friday 内测](https://friday-server.preview.tencent-zeabur.cn/waitlist)

## 安装与登录

选择适合电脑的 DMG：Apple Silicon（M 系列）使用 `arm64`，Intel 使用 `x64`。将 Friday 拖入 Applications，再打开应用。

账号和初始密码由管理员发放；加入 waitlist 不会自动创建账号。

当前版本用于内测。每个版本的签名与 Apple 公证状态以 Release 说明为准。

## 版本与更新

每个版本对应一个 `vX.Y.Z` tag 和 GitHub Release。DMG 用于首次安装，ZIP 和 `latest-mac.yml` 用于客户端更新；保留旧版本便于下载历史安装包。

带更新功能的客户端会检查此仓库的新版本，确认后下载安装。此前未包含更新配置的客户端需要手动安装一次新版本。

Friday 基于 [Cumora](https://github.com/yetone/cumora) 开发。
