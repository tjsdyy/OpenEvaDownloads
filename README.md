# OpenEva 下载 / Downloads

[官网 / Website](https://openeva.ai) · [版本 / Releases](https://github.com/tjsdyy/OpenEvaDownloads/releases)

这里发布 OpenEva 桌面安装包与安装说明。本仓库不包含应用源码、账户数据或服务端配置。

This repository hosts OpenEva desktop installers and installation notes. Application source, account data and server configuration are not included.

## macOS · Apple Silicon / ARM64

[下载 OpenEva 0.3.0](https://github.com/tjsdyy/OpenEvaDownloads/releases/download/v0.3.0/OpenEva_0.3.0_aarch64.dmg)

1. 下载并打开 `.dmg` 文件。
2. 将 `OpenEva.app` 拖到 `Applications`。
3. 从应用程序打开 OpenEva，选择本地文件夹，或在设置中登录云端。

1. Download and open the `.dmg` file.
2. Drag `OpenEva.app` into `Applications`.
3. Open OpenEva and choose a local folder, or sign in to the cloud from Settings.

这是 Apple Silicon 预览版；Intel Mac、Windows、Linux 安装包尚未发布。应用与安装镜像使用 Developer ID 签名，Apple 公证尚未完成，macOS 可能阻止首次打开。签名不代表已经通过 Apple 公证。

This is an Apple Silicon preview; Intel Mac, Windows and Linux installers are not yet published. The app and disk image are Developer ID signed but not Apple notarized. macOS may block the first launch. Signing does not imply notarization.

## 校验 / Verification

Release 附有 `SHA256SUMS.txt`。将其与安装包放在同一目录，在终端运行：

Each release includes `SHA256SUMS.txt`. Place it beside the installer, then run:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

许可与第三方声明见 [LICENSE](LICENSE) 与 [NOTICE](NOTICE)，应用内亦保留随附声明。
