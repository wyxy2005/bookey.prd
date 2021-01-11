# Bookey

## 看板

[周计划](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%E5%91%A8%E8%AE%A1%E5%88%92)

### 需求 - [Create](#新需求)

- [v1.7](https://github.com/bookey-dev/bookey.requirement/projects/12)
- [v1.8](https://github.com/bookey-dev/bookey.requirement/projects/13)
- [v1.6](https://github.com/bookey-dev/bookey.requirement/projects/11)

- [未规划](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+no%3Amilestone)

### 任务 - [Create](#新任务)

- [UI](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Task%3A+UI%22)

- [API](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Task%3A+API%22)

- [IOS](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Task%3A+IOS%22)

- [Android](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Task%3A+Android%22)

- BUG
  - [IOS](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Bug%3A+IOS%22)
  - [Android](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Bug%3A+Android%22)

### 发版记录 - [Create](#新版本) - [流程规范](docs/process-specification.md#版本发布)

- [IOS](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aissue+label%3AReleases%EF%BC%9AIOS)
  - [测试版](https://www.pgyer.com/o9So) - `0910`
  - [TestFlight](https://apps.apple.com/cn/app/testflight/id899247664)
  - [App Store](https://apps.apple.com/cn/app/id1490069864)
- [Android](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aissue+label%3AReleases%EF%BC%9AAndroid+)
  - [测试版](https://www.pgyer.com/C5re) - `2021`
  - [Internaltest](https://play.google.com/apps/internaltest/4700196513230198982)
  - [Google Play](https://play.google.com/store/apps/details?id=app.bookey)

## 文档

### API

- [user](https://dev.bookey.app:8081/swagger-ui.html)
- [book](https://dev.bookey.app:8082/swagger-ui.html)
- [third party](https://dev.bookey.app:8083/swagger-ui.html)

### 规则

- [Analytics](https://github.com/bookey-dev/bookey.docs/wiki/Analytics)
- [DeepLink](https://github.com/bookey-dev/bookey.docs/wiki/DeepLink)
- [Pinpoint](https://github.com/bookey-dev/bookey.docs/wiki/Pinpoint)

### 链接

- [企业邮箱](https://exmail.qq.com/login)
- [UI 蓝湖](https://lanhuapp.com/web/#/item?tid=5a7e615e-5e48-4932-8c33-c7e5075107ea)
- [Bookey 开发后台](https://dev.bookey.app/sys/Home)
- [Firebase 控制台](https://console.firebase.google.com/project/helpful-topic-261709/overview)
- [Branch 控制台](https://dashboard.branch.io)
- [Cognito 控制台](https://us-west-2.console.aws.amazon.com/cognito/users/?region=us-west-2#)

## 模板

### [新需求](https://github.com/bookey-dev/bookey.requirement/issues/new/choose)

- 命名：`需求概述`
- 需求标签：`新需求`、`功能优化`...
- 任务标签：`Task: UI`、`Task: API`、`Task: IOS`、`Task: Android`
- 里程碑（milestone）：`v1.7`、`v1.8`...
- 内容模板（复制粘贴）：

  ```md
  ## 需求

  ### 描述

  ???

  ### 备注

  ???

  ## 评估

  ???

  ## 附件

  ???

  ```

### [新版本](https://github.com/bookey-dev/bookey.requirement/issues/new/choose)

- 命名：`v1.x.xxxx(xxx)`
- 标签：`Releases: IOS` 或 `Releases: Android`
- 内容模板（复制粘贴）：

   ```md
   描述

   - feat: 功能1
   - fix: 修复1
   - style: 样式调整1
   - docs: 文案调整1
   - refator: 重构1
   - chore: 其他1
   ```
