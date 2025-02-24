# LSPatch-ApkFactory
> [!TIP]
> 一个基于LSPatch的打包工具，自动为常见应用打LSPatch补丁的仓库<br>
包括 OPatch(ONPatch) / NPatch <br>
本项目所提及的OPatch均指代现在的ONPatch
本项目打包的任何应用都需要搭配对应的加载器来管理(仅打包本地模式)<br>
例如 `TikTok-35.3.2-398-lspatched.apk` 对应的加载器是 `LSPatch` , 因为文件名包含`lspatched`<br>
在此希望 LSPatch能恢复更新，且大一统，且多选项，且最新，（我可不想一个应用包得服务多个分支）

本仓库基于如下分支打包 请注意版本号不能低于这个表格内的
| 分支 | 版本 | 仓库地址 | 发布地址 | 状态 | 原因 |
| - | - | - | - | - | - |
| LSPatch | 0.6 | [GitHub](https://github.com/LSPosed/LSPatch) | [GitHub](https://github.com/LSPosed/LSPatch/releases/tag/v0.6) | √ |
| OPatch(ONPatch) | 0.0.7 | 无 | [Telegram](https://t.me/NPatch/286) | × | 需要pr对应的jar文件 |
| NPatch | 0.6.1(426) | 无 | [Telegram](https://t.me/NPatch/253) | × | 同上 |

本仓库自动打包的项目
| 软件名称 | 来源 | 版本 |
| - | - | - |
| 支付宝 | 豌豆荚 | latest |
| 微信 | 豌豆荚 | latest |
| Soul | 豌豆荚 | latest |
| 抖音 | 豌豆荚 | latest |
| 抖音极速版 | 豌豆荚 | latest |
| QQ | 豌豆荚 | latest |
| TikTok | ApkPure | latest |
