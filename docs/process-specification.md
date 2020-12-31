# 流程规范

## 版本发布

1. 发布测试版
   - [IOS - TestFlight](https://apps.apple.com/cn/app/testflight/id899247664)
   - [Android - Internaltest](https://play.google.com/apps/internaltest/4700196513230198982)
1. 创建 `Issue` - [Create Link](https://github.com/bookey-dev/bookey.requirement/issues/new/choose)
   - 命名：`v1.x.xxxx(xxx)`
   - 标签：`Releases: IOS` 或 `Releases: Android`
   - 内容：

      ```md
      描述

      - feat: 功能1
      - fix: 修复1
      - style: 样式调整1
      - docs: 文案调整1
      - refator: 重构1
      - chore: 其他1

      文案

      ?
      ```

1. 自测
   - 自测通过
     - 将该 `Issue` 打 `Reviewed: SelfTest` 标签
     - 将该 `Issue` Assignees 给 `Johnsonkk2020` 并通知
1. 提测 - @Johnson
   - 测试内容
      - 发版内容
      - 订阅
   - 测试通过
      - 对该 `Issue` 打 `Reviewed: Test` 标签
      - 将该 `Issue` Assignees 给 `Hannah960906` 并通知
1. UI 审查 - @Hannah
   - 审查内容
      - UI
      - 文案
   - 审查通过
      - 对该 `Issue` 打 `Reviewed: UI` 标签
      - 将该 `Issue` Assignees 给 `Coolll` 或 `dyz930509` 并通知
1. 推正式版
   - 版本说明（默认）

      ```text
      Thanks for using Bookey!  We update the App every week to improve your experience.  

      Send us feedback, suggestions, and ideas to support@bookey.app
      We'll get in touch with you soon. What do you want to see in our app? Tell us!
      ```

   - 版本说明（新功能）- 由 @Banson 或 @Johnson 提供

      ```text
      Thanks for using Bookey!  We update the App every week to improve your experience.  

      add xxxx
      update xxxx

      Send us feedback, suggestions, and ideas to support@bookey.app
      We'll get in touch with you soon. What do you want to see in our app? Tell us!
      ```

   - 发布平台
      - [Apple Store](https://apps.apple.com/cn/app/id1490069864)
      - [Google play](https://play.google.com/store/apps/details?id=app.bookey)
