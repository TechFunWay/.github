<div align="center">

# 科技智趣坊 · TechFunWay

**面向飞牛 fnOS / NAS 的开源自托管应用集合**

自部署 · 数据自主 · 开箱即用

[官网](https://techfunway.wycto.cn) ・ [哔哩哔哩](https://space.bilibili.com/1350401468) ・ [小红书](https://www.xiaohongshu.com/user/profile/612ebe7d000000000201e2a9) ・ [抖音](https://v.douyin.com/N2cDoBbom1Q/) ・ [Gitee](https://gitee.com/TechFunWay)

</div>

---

## 关于我们

「科技智趣坊」专注泛科技与智慧生活的原创内容分享，同时把日常在 **飞牛 fnOS（NAS）** 上真实使用的应用陆续开源。

所有应用都遵循同一套设计前提：

- **自托管优先** —— 数据只落在自己的机器上，不依赖外部服务；
- **部署简单** —— 提供 Docker 镜像（amd64 / arm64 多平台）、飞牛 fnOS `fpk` 安装包与裸二进制；
- **手机能用** —— PC 与手机共用一套界面，窄屏不截断、一屏信息量足；
- **备份可恢复** —— 备份必须能还原，并支持上传本地备份文件换机迁移；
- **统一底座** —— 多数业务应用由 SmallGo 框架搭建，登录、权限、备份、审计等能力开箱即用。

## 应用全景

### 公共底座

| 应用 | 说明 |
|---|---|
| **SmallGo 框架** | 全部自建应用的公共框架与脚手架：登录认证、用户权限、系统配置、备份恢复、审计日志、匿名统计、实时通道，并提供一键生成新应用的脚本 |

### 业务应用

| 应用 | 说明 | 技术栈 |
|---|---|---|
| [**网址收藏夹**](https://github.com/TechFunWay/bookmarks) | 网址收藏管理，带死链清理、链接检查与浏览器扩展 | Go + 静态前端 |
| [**彩彩助手**](https://github.com/TechFunWay/lottery) | 彩票购买记录、自动识别中奖与统计分析 | Go + Vue 3 |
| [**SQLite 管理工具**](https://github.com/TechFunWay/sqlite-manage) | SQLite 数据库 Web 管理工具，在线浏览与编辑 | Go + Vue 3 |
| [**记事本**](https://github.com/TechFunWay/notepad) | 轻量多用户记事本，富文本、标签分类、暗色模式 | Go + Vue 3 |
| [**备忘录**](https://github.com/TechFunWay/memo) | 多用户备忘录，自适应 PC 与移动端，单文件部署 | Go + Vue 3 |
| [**提醒事项**](https://github.com/TechFunWay/reminders) | 多渠道提醒：站内消息、电子邮件、短信、飞书机器人与 QQ 机器人 | Go + Vue 3 |
| [**账单**](https://github.com/TechFunWay/bill) | 个人与多人共享记账，灵活分摊（等额／比例／份额）与最少转账结算，支持微信、支付宝账单导入 | Go + Vue 3 |
| [**方块游戏机**](https://github.com/TechFunWay/brick-game) | 经典 9999-in-1 掌机 HTML5 复刻，49 款小游戏，零依赖零构建 | 纯静态 + Go 静态服务 |
| [**租房管理**](https://github.com/TechFunWay/rental) | 房源、租约到期提醒、月度抄表账单、收款跟踪与收费单据 | Go + Vue 3 |
| **工记** | 记工记账：按天／按时／计件记工，工资自动计算 | SmallGo + Vue 3 |
| **合同管家** | 自定义模板生成合同，占位符代入，打印导出 PDF | SmallGo + Vue 3 |
| **搜集通** | 表单搜集与汇总：设计表单发链接、免登录填写带附件、判重控制、实时汇总导出 | SmallGo + Vue 3 |
| **DSH NAS** | DeepSeek dsh 网页版启动器，安装包内置 Node 运行时 | SmallGo + Vue 3 |

### 门户与内容

| 项目 | 说明 |
|---|---|
| **科技智趣坊门户** | <https://techfunway.wycto.cn> —— 全部应用的入口与介绍，并接收应用的匿名在线统计 |
| **公众号文章库** | 公众号文章内容库，介绍自建应用与 NAS 玩法，非可运行应用 |

## 技术栈

| 层 | 选型 |
|---|---|
| 后端 | Go（标准库 + 少量依赖），门户站点使用 ThinkPHP 8 |
| 前端 | Vue 3 + Element Plus，部分应用为无构建的静态前端 |
| 数据 | SQLite —— 单文件、零运维，随应用一起备份与恢复 |
| 打包 | Docker（amd64 / arm64 多平台镜像）、飞牛 fnOS `fpk` 安装包、裸二进制 |

## 关注我们

| 平台 | 账号 |
|---|---|
| 官网 | <https://techfunway.wycto.cn> |
| 哔哩哔哩 | [科技智趣坊](https://space.bilibili.com/1350401468) |
| 小红书 | [科技智趣坊](https://www.xiaohongshu.com/user/profile/612ebe7d000000000201e2a9) |
| 抖音 | [科技智趣坊](https://v.douyin.com/N2cDoBbom1Q/) |
| Gitee | <https://gitee.com/TechFunWay> |

---

<div align="center">
<sub>应用均为自用工具开源，欢迎提 Issue 交流使用体验。</sub>
</div>
