<div align="center">
<img width="768" src="https://github.com/ysx88/ysx88/blob/main/assets/OpenWrt-logo.png"/>
</div>

<h4 align="center">访客数 :eyes:</h4>

<p align="center"><img src="https://profile-counter.glitch.me/ysx88/count.svg" alt="ysx88 :: Visitor's Count" /></p>

## Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

使用 GitHub Actions 构建 OpenWrt

[在我的博客中阅读详细信息（中文）](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## 用法

- 单击使用 [此模板](https://github.com/P3TERX/Actions-OpenWrt/generate) 按钮创建一个新的存储库.
- `.config` 使用 [Lean 的 OpenWrt](https://github.com/coolsnowwolf/lede) 源代码生成文件. ( 您可以通过工作流文件中的环境变量更改它. )
- 将文件 `.config` 推送到 GitHub 存储库.
- 在 `Build OpenWrt` “操作”页面上选择.
- 单击 `Run workflow` 按钮.
- 构建完成后，单击 `Artifacts` “操作”页面右上角的按钮下载二进制文件.

## 提示

- 创建 `.config` 文件和构建 OpenWrt 固件可能需要很长时间. 因此, 在创建存储库以构建您自己的固件之前, 您可以通过简单地在 GitHub 中搜索 [`Actions-Openwrt`](https://github.com/search?q=Actions-openwrt)来检查是否其他人已经构建了满足您需求的它.
- 将您构建的固件的一些元信息（例如固件体系结构和已安装的软件包）添加到您的存储库介绍中，这将节省其他人的时间.

## 鸣谢

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## 许可证

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © P3TERX
