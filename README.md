# Bookey

## 看板

[周计划](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%E5%91%A8%E8%AE%A1%E5%88%92)

### 需求 - [发布新需求](#发布新需求)

- [v1.7](https://github.com/bookey-dev/bookey.requirement/projects/12)
- [v1.8](https://github.com/bookey-dev/bookey.requirement/projects/13)
- [v1.6](https://github.com/bookey-dev/bookey.requirement/projects/11)

- [未规划](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+no%3Amilestone+-label%3A%E9%95%BF%E6%9C%9F%E4%BB%BB%E5%8A%A1+-label%3A%E6%97%A0%E6%95%88+-label%3A%E4%BB%BB%E5%8A%A1+-label%3A%22Bug%3A+Android%22+-label%3A%22Bug%3A+IOS%22+-label%3A%E5%91%A8%E8%AE%A1%E5%88%92+-label%3AReleases%EF%BC%9AAndroid+-label%3AReleases%EF%BC%9AIOS)

### 任务 - [创建新任务](#创建新任务)

- [UI: Hannah](https://github.com/bookey-dev/bookey.requirement/issues/assigned/Hannah960906)

- [API: Kim](https://github.com/bookey-dev/bookey.requirement/issues/assigned/itwangxiang)

- [IOS: Kayle](https://github.com/bookey-dev/bookey.requirement/issues/assigned/Coolll)

- [Android: Mason](https://github.com/bookey-dev/bookey.requirement/issues/assigned/dyz930509)

- [Test: Johnson](https://github.com/bookey-dev/bookey.requirement/issues/assigned/Johnsonkk2020)

- BUG
  - [IOS](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Bug%3A+IOS%22)
  - [Android](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aopen+is%3Aissue+label%3A%22Bug%3A+Android%22)

### 版本 - [发布新版本](#发布新版本) 

[IOS 发版记录](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aissue+label%3AReleases%EF%BC%9AIOS)

[Android 发版记录](https://github.com/bookey-dev/bookey.requirement/issues?q=is%3Aissue+label%3AReleases%EF%BC%9AAndroid+)

> [流程](docs/process-specification.md#版本发布)

### 崩溃

#### 数据来源

- Android
  - [Google Play](https://play.google.com/console/developers/8336602248191894610/app/4971990627291724079/vitals/crashes?installedFrom=PLAY_STORE&days=30)
  - [Firebase Crashlytics](https://console.firebase.google.com/project/helpful-topic-261709/crashlytics/app/android:app.bookey/issues?state=open&time=last-thirty-days&type=crash)

- IOS
  - [Firebase Crashlytics](https://console.firebase.google.com/project/helpful-topic-261709/crashlytics/app/ios:com.idea.bookey/issues?state=open&time=last-seven-days&type=crash)
 

#### 关注时间

每天早上或邮件通知

#### 崩溃类型

- 按严重程度
  - 紧急
  - 非紧急 
- 按修复时间
  - 耗时
  - 非耗时

#### 修复要求

- 立即修复
  - 紧急类崩溃
  - 非紧急且非耗时类崩溃

- 下个版本修复
  - 非紧急且耗时类的崩溃

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

- APP 下载链接
  - IOS
    - [测试版](https://www.pgyer.com/o9So) - `0910`
    - [TestFlight](https://apps.apple.com/cn/app/testflight/id899247664)
    - [App Store](https://apps.apple.com/cn/app/id1490069864)
  - Android
    - [测试版](https://www.pgyer.com/C5re) - `2021`
    - [Internaltest](https://play.google.com/apps/internaltest/4700196513230198982)
    - [Google Play](https://play.google.com/store/apps/details?id=app.bookey)

## 模板

### [发布新需求](https://github.com/bookey-dev/bookey.requirement/issues/new/choose)

- 命名：`需求概述`
- 需求标签：`新需求`、`功能优化`、`BUG`
- 里程碑（milestone）：`v1.7`、`v1.8`...
- 内容模板（复制粘贴）：

  ```md
  ## 需求

  ### 描述

  ???

  ### 备注

  ???

  ## 任务

  - [ ] UI
  - [ ] API
  - [ ] IOS
  - [ ] Android

  ```

### [创建新任务](https://github.com/bookey-dev/bookey.requirement/issues/new/choose)

- 命名：`任务名`
- 任务标签：`任务`
- 内容模板：

  ```md
  
  描述

  ```

### [发布新版本](https://github.com/bookey-dev/bookey.requirement/issues/new/choose)

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
