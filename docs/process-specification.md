# 流程规范

- [流程规范](#流程规范)
  - [版本发布](#版本发布)
    - [1. 发布测试版](#1-发布测试版)
    - [2. 创建 `Issue` - Create Link](#2-创建-issue---create-link)
    - [3. 自测](#3-自测)
    - [4. UI 审查 - @Hannah](#4-ui-审查---hannah)
    - [5. 发布内测版](#5-发布内测版)
    - [6. 提测 - @Johnson](#6-提测---johnson)
    - [7. 推正式版 - 并关闭该 `Issue`](#7-推正式版---并关闭该-issue)

## 版本发布

### 1. 发布测试版

- [IOS - 蒲公英](https://www.pgyer.com/o9So)
- Android - 蒲公英

### 2. 创建 `Issue` - [Create Link](https://github.com/bookey-dev/bookey.requirement/issues/new/choose)

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

### 3. 自测

- 测试内容
  - 代码改过
  - 发版内容
  - 核心功能
- 自测通过
  - 将该 `Issue` 打 `Reviewed: SelfTest` 标签
  - 将该 `Issue` Assignees 给 `Hannah960906` 并通知
    - 无 UI、文案变动时,直接走 [第5步](#5-发布内测版)

### 4. UI 审查 - @Hannah

- 审查内容
  - UI
  - 文案
- 审查通过
  - 对该 `Issue` 打 `Reviewed: UI` 标签
  - 将该 `Issue` Assignees 给 `Coolll` 或 `dyz930509` 并通知
- 审查不通过 - **重走流程**
  - 将问题反馈评论到该 `Issue`
  - 将该 `Issue` Assignees 给 `Coolll` 或 `dyz930509` 并通知

### 5. 发布内测版

- 发布完，将该 `Issue` Assignees 给 `Johnsonkk2020` 并通知
- 平台链接
  - [IOS - TestFlight](https://apps.apple.com/cn/app/testflight/id899247664)
  - [Android - Internaltest](https://play.google.com/apps/internaltest/4700196513230198982)

### 6. 提测 - @Johnson

- 测试内容
  - 发版内容
  - 核心功能
- 测试通过
  - 对该 `Issue` 打 `Reviewed: Test` 标签
  - 将该 `Issue` Assignees 给 `Coolll` 或 `dyz930509` 并通知

### 7. 推正式版 - 并关闭该 `Issue`

- 版本说明（默认）

   ```text
   Thanks for using Bookey!  We update the App every week to improve your experience.  

   Bugs fixes and performance improvements.
   Added more book summary, booknotes, ebooks, audiobooks.

   Send us feedback, suggestions, and ideas to support@bookey.app
   We'll get in touch with you soon. What do you want to see in our app? Tell us!
   ```

- 版本说明（新功能）- 由 @Banson 或 @Johnson 提供

   ```text
   Thanks for using Bookey!  We update the App every week to improve your experience.  

   add xxxx
   update xxxx

   Bugs fixes and performance improvements.
   Added more book summary, booknotes, ebooks, audiobooks.

   Send us feedback, suggestions, and ideas to support@bookey.app
   We'll get in touch with you soon. What do you want to see in our app? Tell us!
   ```

- 发布平台
  - [Apple Store](https://apps.apple.com/cn/app/id1490069864)
  - [Google play](https://play.google.com/store/apps/details?id=app.bookey)
