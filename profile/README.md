<div align="center">

<img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-bookmarks.png" width="96" alt="科技智趣坊" />

# 科技智趣坊 · TechFunWay

**面向飞牛 fnOS / NAS 的开源自托管应用集合**

自部署 · 数据自主 · 开箱即用

[官网](https://techfunway.wycto.cn) ・ [应用全家福](#应用全家福) ・ [应用矩阵](#应用矩阵) ・ [界面预览](#界面预览) ・ [已发布情况](#已发布情况) ・ [哔哩哔哩](https://space.bilibili.com/1350401468) ・ [小红书](https://www.xiaohongshu.com/user/profile/612ebe7d000000000201e2a9) ・ [抖音](https://v.douyin.com/N2cDoBbom1Q/) ・ [Gitee](https://gitee.com/TechFunWay)

[![官网](https://img.shields.io/badge/官网-techfunway.wycto.cn-1f6feb?logo=googlechrome&logoColor=white)](https://techfunway.wycto.cn)
[![应用](https://img.shields.io/badge/自托管应用-13%20款-2ea44f)](#应用全家福)
[![GitHub](https://img.shields.io/badge/GitHub-TechFunWay-181717?logo=github&logoColor=white)](https://github.com/TechFunWay)
[![Gitee](https://img.shields.io/badge/Gitee-TechFunWay-c71d23?logo=gitee&logoColor=white)](https://gitee.com/TechFunWay)

</div>

---

## 关于我们

「科技智趣坊」专注泛科技与智慧生活的原创内容分享，同时把日常在 **飞牛 fnOS（NAS）** 上真实使用的应用陆续开源。

所有应用都遵循同一套设计前提：

- **自托管优先** —— 数据只落在自己的机器上，不依赖外部服务；
- **部署简单** —— 提供 Docker 镜像（amd64 / arm64 多平台）、飞牛 fnOS `fpk` 安装包与裸二进制三种形态；
- **手机能用** —— PC 与手机共用一套界面，窄屏不截断、一屏信息量足；
- **备份可恢复** —— 备份必须能还原，并支持上传本地备份文件换机迁移；

## 应用全家福

<p align="center">
  <a href="https://github.com/TechFunWay/bookmarks"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-bookmarks.png" width="64" alt="网址收藏夹" title="网址收藏夹"></a>
  <a href="https://github.com/TechFunWay/lottery"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-lottery.png" width="64" alt="彩彩助手" title="彩彩助手"></a>
  <a href="https://github.com/TechFunWay/sqlite-manage"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-sqlite-manage.png" width="64" alt="SQLite 管理工具" title="SQLite 管理工具"></a>
  <a href="https://github.com/TechFunWay/notepad"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-notepad.png" width="64" alt="记事本" title="记事本"></a>
  <a href="https://github.com/TechFunWay/memo"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-memo.png" width="64" alt="备忘录" title="备忘录"></a>
  <a href="https://github.com/TechFunWay/reminders"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-reminders.png" width="64" alt="提醒事项" title="提醒事项"></a>
  <a href="https://github.com/TechFunWay/bill"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-bill.png" width="64" alt="账单" title="账单"></a>
</p>
<p align="center">
  <a href="https://github.com/TechFunWay/brick-game"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-brick-game.png" width="64" alt="方块游戏机" title="方块游戏机"></a>
  <a href="https://github.com/TechFunWay/worklog"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-worklog.png" width="64" alt="工记" title="工记"></a>
  <a href="https://github.com/TechFunWay/rental"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-rental.png" width="64" alt="租房管理" title="租房管理"></a>
  <a href="https://github.com/TechFunWay/contract"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-contract.png" width="64" alt="合同管家" title="合同管家"></a>
  <a href="https://techfunway.wycto.cn/fnapp/collect"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-collect.png" width="64" alt="搜集通" title="搜集通"></a>
  <a href="https://techfunway.wycto.cn/fnapp/dsh-nas"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/icon-dsh-nas.png" width="64" alt="DSH NAS" title="DSH NAS"></a>
</p>

## 应用矩阵

> 版本徽章实时读取对应的 GitHub Release，点「Releases」即为该应用的下载页。

| 应用 | 说明 | 技术栈 | 版本 | 获取 |
|---|---|---|---|---|
| [**网址收藏夹**](https://github.com/TechFunWay/bookmarks) | 网址收藏管理，带死链清理、链接检查与浏览器扩展 | Go + 静态前端 | ![release](https://img.shields.io/github/v/release/TechFunWay/bookmarks?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/bookmarks/releases) · [Docker](https://hub.docker.com/r/techfunways/bookmarks) |
| [**彩彩助手**](https://github.com/TechFunWay/lottery) | 彩票购买记录、自动识别中奖与统计分析 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/lottery?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/lottery/releases) · [Docker](https://hub.docker.com/r/techfunways/lottery) |
| [**SQLite 管理工具**](https://github.com/TechFunWay/sqlite-manage) | SQLite 数据库 Web 管理工具，在线浏览、查询与编辑 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/sqlite-manage?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/sqlite-manage/releases) · [Docker](https://hub.docker.com/r/techfunways/sqlite-manage) |
| [**记事本**](https://github.com/TechFunWay/notepad) | 轻量多用户记事本，富文本、标签分类、暗色模式 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/notepad?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/notepad/releases) · [Docker](https://hub.docker.com/r/techfunways/notepad) |
| [**备忘录**](https://github.com/TechFunWay/memo) | 多用户备忘录，自适应 PC 与移动端，单文件部署 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/memo?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/memo/releases) · [Docker](https://hub.docker.com/r/techfunways/memo) |
| [**提醒事项**](https://github.com/TechFunWay/reminders) | 多渠道提醒：站内消息、电子邮件、短信、飞书机器人与 QQ 机器人 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/reminders?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/reminders/releases) · [Docker](https://hub.docker.com/r/techfunways/reminders) |
| [**账单**](https://github.com/TechFunWay/bill) | 个人与多人共享记账，灵活分摊（等额／比例／份额）与最少转账结算，支持微信、支付宝账单导入 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/bill?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/bill/releases) · [Docker](https://hub.docker.com/r/techfunways/bill) |
| [**方块游戏机**](https://github.com/TechFunWay/brick-game) | 经典 9999-in-1 掌机 HTML5 复刻，49 款小游戏，霓虹像素 + 8bit 芯片音乐，零依赖零构建 | 纯静态 + Go 静态服务 | ![release](https://img.shields.io/github/v/release/TechFunWay/brick-game?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/brick-game/releases) · [Docker](https://hub.docker.com/r/techfunways/brick-game) |
| [**工记**](https://github.com/TechFunWay/worklog) | 记工记账：按天／按时／计件记工，班组协作、考勤日历、借支结算与工资条导出 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/worklog?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/worklog/releases) · [Docker](https://hub.docker.com/r/techfunways/worklog) |
| [**租房管理**](https://github.com/TechFunWay/rental) | 房源、租约到期提醒、月度抄表账单、收款跟踪与收费单据 | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/rental?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/rental/releases) · [Docker](https://hub.docker.com/r/techfunways/rental) |
| [**合同管家**](https://github.com/TechFunWay/contract) | 自定义模板生成合同，占位符代入，打印导出 PDF | Go + Vue 3 | ![release](https://img.shields.io/github/v/release/TechFunWay/contract?sort=semver&label=%E7%89%88%E6%9C%AC&color=2ea44f) | [Releases](https://github.com/TechFunWay/contract/releases) · [Docker](https://hub.docker.com/r/techfunways/contract) |
| **搜集通** | 表单搜集与汇总：设计表单发链接、免登录填写带附件、判重控制、实时汇总导出 | Go + Vue 3 | ![fnos](https://img.shields.io/badge/%E9%A3%9E%E7%89%9B-fpk-00A9E0) | [应用介绍](https://techfunway.wycto.cn/fnapp/collect) |
| **DSH NAS** | DeepSeek dsh 网页版启动器，安装包内置 Node 运行时 | Go + Vue 3 | ![fnos](https://img.shields.io/badge/%E9%A3%9E%E7%89%9B-fpk-00A9E0) | [应用介绍](https://techfunway.wycto.cn/fnapp/dsh-nas) |

## 界面预览

<table>
  <tr>
    <td width="50%"><b>账单</b> —— 多人共享记账与分摊结算<br /><a href="https://github.com/TechFunWay/bill"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-bill.jpg" alt="账单" /></a></td>
    <td width="50%"><b>网址收藏夹</b> —— 自托管书签与死链清理<br /><a href="https://github.com/TechFunWay/bookmarks"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-bookmarks.jpg" alt="网址收藏夹" /></a></td>
  </tr>
  <tr>
    <td width="50%"><b>彩彩助手</b> —— 购彩记录与中奖统计<br /><a href="https://github.com/TechFunWay/lottery"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-lottery.png" alt="彩彩助手" /></a></td>
    <td width="50%"><b>SQLite 管理工具</b> —— 浏览器里管理数据库<br /><a href="https://github.com/TechFunWay/sqlite-manage"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-sqlite-manage.png" alt="SQLite 管理工具" /></a></td>
  </tr>
  <tr>
    <td width="50%"><b>记事本</b> —— 富文本写作与标签管理<br /><a href="https://github.com/TechFunWay/notepad"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-notepad.jpg" alt="记事本" /></a></td>
    <td width="50%"><b>备忘录</b> —— 文件夹归类与暗色模式<br /><a href="https://github.com/TechFunWay/memo"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-memo.png" alt="备忘录" /></a></td>
  </tr>
  <tr>
    <td width="50%"><b>提醒事项</b> —— 清单管理与多渠道通知<br /><a href="https://github.com/TechFunWay/reminders"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-reminders.jpg" alt="提醒事项" /></a></td>
    <td width="50%"><b>方块游戏机</b> —— 49 款小游戏的网页掌机<br /><a href="https://github.com/TechFunWay/brick-game"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-brick-game.jpg" alt="方块游戏机" /></a></td>
  </tr>
  <tr>
    <td width="50%"><b>工记</b> —— 记工记账与工资结算<br /><a href="https://github.com/TechFunWay/worklog"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-worklog.jpg" alt="工记" /></a></td>
    <td width="50%"><b>租房管理</b> —— 房源、抄表账单与收款跟踪<br /><a href="https://github.com/TechFunWay/rental"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-rental.jpg" alt="租房管理" /></a></td>
  </tr>
  <tr>
    <td width="50%"><b>合同管家</b> —— 模板生成合同并导出 PDF<br /><a href="https://github.com/TechFunWay/contract"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-contract.jpg" alt="合同管家" /></a></td>
    <td width="50%"><b>手机端</b> —— PC 与手机共用一套界面，窄屏不截断<br /><a href="https://techfunway.wycto.cn/fnapp/worklog"><img src="https://raw.githubusercontent.com/TechFunWay/.github/main/profile/assets/app-mobile.jpg" alt="手机端界面" /></a></td>
  </tr>
</table>

> 以上均为真机实拍界面，点图进入对应仓库。每个应用的完整截图集在各自仓库的 `docs/screenshots/`、`images/screenshots/` 与[官网介绍页](https://techfunway.wycto.cn)里。

## 已发布情况

| 应用 | 飞牛 fnOS `fpk` | Docker 镜像 | GitHub Releases | Gitee 发行版 | 官网介绍页 |
|---|---|---|---|---|---|
| 网址收藏夹 | ✅ | ✅ | ✅ | — | [查看](https://techfunway.wycto.cn/fnapp/bookmarks) |
| 彩彩助手 | ✅ | ✅ | ✅ | — | [查看](https://techfunway.wycto.cn/fnapp/lottery) |
| SQLite 管理工具 | ✅ | ✅ | ✅ | — | [查看](https://techfunway.wycto.cn/fnapp/sqlite-manage) |
| 记事本 | ✅ | ✅ | ✅ | ✅ | [查看](https://techfunway.wycto.cn/fnapp/notepad) |
| 备忘录 | ✅ | ✅ | ✅ | — | [查看](https://techfunway.wycto.cn/fnapp/memo) |
| 提醒事项 | ✅ | ✅ | ✅ | — | [查看](https://techfunway.wycto.cn/fnapp/reminders) |
| 账单 | ✅ | ✅ | ✅ | ✅ | [查看](https://techfunway.wycto.cn/fnapp/bill) |
| 方块游戏机 | ✅ | ✅ | ✅ | — | [查看](https://techfunway.wycto.cn/fnapp/brick-game) |
| 工记 | ✅ | ✅ | ✅ | ✅ | [查看](https://techfunway.wycto.cn/fnapp/worklog) |
| 租房管理 | ✅ | ✅ | ✅ | ✅ | [查看](https://techfunway.wycto.cn/fnapp/rental) |
| 合同管家 | ✅ | ✅ | ✅ | ✅ | [查看](https://techfunway.wycto.cn/fnapp/contract) |
| 搜集通 | ✅ | — | — | — | [查看](https://techfunway.wycto.cn/fnapp/collect) |
| DSH NAS | ✅ | — | — | — | [查看](https://techfunway.wycto.cn/fnapp/dsh-nas) |

- 「—」表示该渠道暂未发布：**搜集通、DSH NAS**目前只提供飞牛 fnOS 安装包，代码仓库尚未公开；**部分早期应用**（网址收藏夹、彩彩助手、SQLite 管理工具、备忘录、提醒事项、方块游戏机）已有 GitHub Release，Gitee 发行版还在陆续补齐。
- 国内访问 GitHub 不便时，请走 [Gitee 组织主页](https://gitee.com/TechFunWay) 或[官网](https://techfunway.wycto.cn)上的下载入口。

## 部署方式

```bash
# 1) Docker（以账单为例，amd64 / arm64 多平台镜像）
docker run -d --name bill \
  -p 8907:8907 \
  -v /your/data/bill:/data \
  --restart unless-stopped \
  techfunways/bill:latest

# 2) Docker Compose：各应用 Release 里都附带 docker-compose.yml
curl -fsSLO https://github.com/TechFunWay/bill/releases/latest/download/docker-compose.yml
docker compose up -d

# 3) 飞牛 fnOS：在应用中心手动安装对应版本的 .fpk 安装包
```

- 数据一律落在挂载目录（默认 SQLite 单文件），备份即拷贝，恢复支持上传本地备份文件；
- 端口在 `8900`–`8912` 家族内逐应用分配，各应用 README 与介绍页都标注了默认端口。

## 生态与架构

| 层 | 项目 | 说明 |
|---|---|---|
| 业务应用 | 13 款自建应用 | 统一交互与统一手机端布局，同一套设计规范 |
| 门户站点 | [**科技智趣坊**](https://techfunway.wycto.cn) | 全部应用的入口与介绍页，同时接收应用上报的匿名在线统计 |
| 内容 | **公众号文章库** | 介绍自建应用与 NAS 玩法，非可运行应用 |

技术选型：**Go**（标准库为主）+ **Vue 3 + Element Plus** + **SQLite**；打包为 Docker 多平台镜像、飞牛 `fpk` 安装包与裸二进制。

## 关注我们

| 平台 | 账号 |
|---|---|
| 官网 | <https://techfunway.wycto.cn> |
| Gitee | <https://gitee.com/TechFunWay> |
| 哔哩哔哩 | [科技智趣坊](https://space.bilibili.com/1350401468) |
| 小红书 | [科技智趣坊](https://www.xiaohongshu.com/user/profile/612ebe7d000000000201e2a9) |
| 抖音 | [科技智趣坊](https://v.douyin.com/N2cDoBbom1Q/) |

## 支持作者

应用全部免费、无广告、无功能限制。如果它们帮到了你，欢迎请作者喝杯咖啡——金额随意，1 元也是心意。

<p align="center">
  <img src="https://raw.githubusercontent.com/TechFunWay/bill/main/docs/wechat-qr.png" alt="微信收款码" width="240" />
</p>

支持完全自愿，不支付不影响任何功能。

---

<div align="center">
<sub>所有应用均为自用工具开源，欢迎提 Issue 交流使用体验。</sub>
</div>
