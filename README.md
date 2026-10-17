# xh Tool

xh Tool 是面向 PC 音游玩家的原生 Android 查分工具，作者为**鳕烩**。当前支持 **DJMAX RESPECT V**，需要 Android 8.0 及以上系统。

## 下载

- [CNB 下载](https://cnb.cool/linglin520/xh-tool/-/releases)
- [GitHub 下载](https://github.com/linglin520/xh-tool/releases/latest)

选择附件 `xh-Tool-0.1.0.apk` 安装。两站提供相同安装包；`SHA256SUMS.txt` 可用于核对文件摘要。此仓库用于发行 APK、更新资料和用户说明。

## 功能

- 使用 V-ARCHIVE 昵称或查询 Token 查看 4B / 5B / 6B / 8B 成绩、B70 / B30 / S10、DJ CLASS、Tier、统计、成长记录与吃分推荐。
- 浏览曲库、曲包和等级，搜索、筛选、收藏，查看谱面详情与雷达。
- 查看 Steam DLC 优惠、各区原币价格、价格历史、CLEAR PASS 档案和本地到期提醒。
- 支持演示模式、深浅主题、银白 / 金色 / 樱花粉外观和可调动效。

其他音游尚未接入；PLATiNA :: LAB 为开发中占位。不提供 PC 自动采集、OCR、云同步、多账号管理或旧应用数据导入。

## 开始使用

安装后打开“我的 → 查分玩家”，配置一个当前查询玩家。未配置账号也可浏览曲库；演示数据不代表真实玩家。历史从首次成功查询开始积累。

xh Tool 与原 DJMAX Tool 独立安装，不覆盖旧应用。若曾安装使用调试签名的 xh Tool 内部测试包，首次正式版可能需要卸载该测试包再安装，卸载会删除其本地数据；请先确认需要保留的资料。之后请使用本仓库的正式包升级。

## 0.1.0

- 减少成绩卡片和页面切换时的重复计算。
- 修复 DLC 详情连续返回时出现灰黑遮罩的问题。
- 返回手势松手后顺着手势方向平移并淡出，取消手势可恢复页面。
- DLC 优惠标题随列表滚动，屏幕顶部的状态栏模糊区域保持固定。

已在 Android 12 模拟器检查主要流程；不同手机的高刷新率、较新系统玻璃效果和系统手势仍需实机验证。

## 更新与数据

在应用内检查更新，默认 CNB，也可选择 GitHub。发现更新后由你主动下载，校验完成后交给系统确认安装。不会下载旧 DJMAX Tool 的安装包。

数据与网络服务来自 V-ARCHIVE、EZ2PATTERN、Hangibot、Steam、小黑盒等，网络区域、账号权限和来源可用性会影响结果。应用内“关于”保留资料来源及许可说明。查询 Token 使用 Android Keystore 加密存储。作者头像只在打开关于页时检查缓存，不需要 QQ 登录。

xh Tool 是玩家工具，与游戏官方没有隶属关系。问题可通过 [GitHub Issues](https://github.com/linglin520/xh-tool/issues) 或 [CNB 宜休](https://cnb.cool/linglin520/xh-tool/-/issues) 反馈；请勿公开查询 Token 等私人资料。
