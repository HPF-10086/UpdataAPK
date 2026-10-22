# BTC.VIP Android 安装包（原 WalletHot）

本仓库仅提供 BTC.VIP Android APK、SHA-256 校验文件和版本说明，不包含源码、签名密钥或钱包数据。

[下载最新主网版本](https://github.com/HPF-10086/UpdataAPK/releases/latest) · [查看全部版本](https://github.com/HPF-10086/UpdataAPK/releases)

当前主网版：[BTC.VIP 0.8.13](https://github.com/HPF-10086/UpdataAPK/releases/tag/v0.8.13-mainnet)。本次修复 TRON 余额刷新遇到 429 时反复请求的问题，增加自动退避、减少重复校验并合并同一地址查询；失败保留上次余额，不把查询失败显示成零。原蓝紫色主题统一调整为黑金配色，交易前安全校验保留。附件名称保留 `WalletHot-Mainnet` 前缀，以兼容已有应用的更新识别；安装后显示 BTC.VIP。

- 名称包含 `Mainnet` 的安装包连接真实主网，不能当作无真实价值的 Shasta 测试包使用。具体支持范围以对应版本说明为准。
- 普通 Android 手机通常选择 `arm64.apk`；x64 用于相应模拟器和兼容设备。
- 升级原主网版应选择同一包名和签名、版本码更高的主网 APK，直接覆盖安装；不要先卸载、清除数据或降级。
- 历史 Shasta 测试版与主网版包名、数据及更新渠道独立，不能用主网版覆盖 Shasta 数据。
- 下载后可使用该版本附带的 `SHA256SUMS.txt` 核对文件。系统兼容性和实体设备验收范围请阅读具体版本说明。
