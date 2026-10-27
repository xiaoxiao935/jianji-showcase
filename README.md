# 简记·记账簿

一个轻量、简洁的个人记账项目，集收支记录、预算管理、分类整理与统计回顾于一体。

**[打开网页试用](https://jianji1602-jianji-showcase-d7fwl86y2a46e651.webapps.tcloudbase.com/)** · [产品预览](#产品预览) · **[观看32秒演示](https://xiaoxiao935.github.io/jianji-showcase/)** · [设计思路](#设计思路) · [实现概览](#实现概览) · [项目设计说明](docs/PROJECT_BRIEF.md) · [常见问题](docs/FAQ.md)

本页用于展示项目成果、设计思路和实现概况。

## 项目概览

| 项目目标 | 主要内容 |
|---|---|
| 面向场景 | 学生和上班族的日常收支记录与回顾 |
| 核心路径 | 记录一笔 → 查看账单 → 预算与统计回顾 |
| 使用方式 | 直接打开网页试用；截图展示独立运行页面 |
| 展示范围 | 产品成果、设计取舍与实现概况；不提供业务源码 |

## 试用建议

建议按以下顺序体验，并使用虚构金额和备注：

1. 查看首页的收支与账单布局。
2. 尝试记录一笔支出，检查分类、金额和备注的填写方式。
3. 查看预算、统计、分类管理与速记等页面。

网页试用不要求下载源码、安装开发工具或自行配置云环境。详见 [网页试用路线](docs/TRY_IT.md)。

## 产品预览

| 账户首页 | 记一笔 | 统计 |
|:---:|:---:|:---:|
| <img src="https://xiaoxiao935.github.io/jianji-showcase/assets/screenshots/01-home.png" width="240" alt="账户首页"> | <img src="https://xiaoxiao935.github.io/jianji-showcase/assets/screenshots/02-add.png" width="240" alt="记一笔"> | <img src="https://xiaoxiao935.github.io/jianji-showcase/assets/screenshots/03-stats.png" width="240" alt="统计"> |

| 预算 | 分类管理 | 速记模板 |
|:---:|:---:|:---:|
| <img src="https://xiaoxiao935.github.io/jianji-showcase/assets/screenshots/04-budget.png" width="240" alt="预算"> | <img src="https://xiaoxiao935.github.io/jianji-showcase/assets/screenshots/05-categories.png" width="240" alt="分类管理"> | <img src="https://xiaoxiao935.github.io/jianji-showcase/assets/screenshots/06-quick.png" width="240" alt="速记模板"> |

截图来自微信开发者工具中的实际运行页面，账单与模板均为虚构演示数据；不代表真机或云端验收。


## 操作演示

[<img src="https://xiaoxiao935.github.io/jianji-showcase/assets/demo/jianji-demo-poster.jpg" width="320" alt="简记·记账簿操作演示封面，点击打开视频">](https://xiaoxiao935.github.io/jianji-showcase/)

**[查看32秒操作演示](https://xiaoxiao935.github.io/jianji-showcase/)** · [下载视频](https://raw.githubusercontent.com/xiaoxiao935/jianji-showcase/main/assets/demo/jianji-demo.webm)

实际操作关键帧剪辑，非连续录屏；全部使用隔离虚构数据。展示新增28元支出、保存后回顾账单，以及预算、统计与速记页面。模拟器画面不代表网页或小程序正式上线状态。

## 设计思路

- **记录更顺手**：围绕金额、分类与备注组织录入，常用收支可通过模板减少重复填写。
- **回顾更清楚**：首页呈现收支与账单，统计与预算承担进一步查看和管理的任务。
- **视觉更统一**：使用米白背景、青绿主色与清晰的文字层级，保持页面之间的布局一致。

更多背景和取舍见 [项目设计说明](docs/PROJECT_BRIEF.md) · [常见问题](docs/FAQ.md)。

## 实现概览

项目涵盖收支记录、分类管理、速记模板、预算管理与统计回顾。实现中涉及金额精度、跨页面刷新、图表渲染和本机数据管理；登录、反馈与云账本相关流程使用微信云开发。

这里说明实现范围，不提供源码下载或自建部署教程。网页试用不代表全部小程序能力已经上线。

## 验证与当前进度

- 六张截图来自隔离虚构数据的实际模拟器运行页面。
- 公开阶段版本的现有自动化测试在2026-10-27运行，40项通过；此数字不代表完整功能覆盖率。
- 小程序正式发布、逐页真机完整验收及云账本双端验收仍需继续完成。
- 手机号绑定、账号注销删除、内置拍照识别和微信定时通知尚未开放，不作为现有可用功能宣传。

## 反馈

可通过 [Issues](https://github.com/xiaoxiao935/jianji-showcase/issues) 反馈。欢迎描述试用中的页面、操作步骤、预期与实际结果；请勿上传真实账单、账号配置或个人资料。





