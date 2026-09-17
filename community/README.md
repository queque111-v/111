# Community submission

游戏结算页会生成一段 JSON 投稿内容。

要使用与参考游戏类似的 GitHub Issues 投稿方式：
1. 把 `index.html` 里的 `SCORE_REPO` 改成 `你的账号/你的仓库`。
2. 玩家结算后点击“留言与提交成绩”，生成投稿内容。
3. 网页会打开仓库的 New Issue 页面，由玩家自己确认发布。
4. 可进一步使用 GitHub Actions 从开放 Issues 重建 `community.json`。

本提交包默认不绑定第三方仓库，避免把测试成绩误投到原项目。
