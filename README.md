# 虚拟细胞：看不见的生命实验

这版不再是普通 Quiz，而是按参考项目的“图像推理故事”结构重构。

## 与参考游戏对齐的结构
- 10 个自由选择的章节
- 共 384 个短页
- 共 132 个计分推理节点
- 30 个需要玩家亲手打开的实验记录
- 20 组不计分的倾向/回望
- 20 则研究侧记
- 每页只推进一件事，只显示当前页
- 大幅原创插画 + 教学模拟科学图
- 答错解释 → 重新选择；提示不直接通关
- 线索本 + 调查笔记导出
- 故事模式 / 简洁阅读
- 浏览器 localStorage 保存进度
- 首次答对 / 纠错 / 提示后 100 / 60 / 30 计分
- 结算页、值得回看的推理、社区榜单、昵称/星级/评论
- GitHub Issues 投稿包生成（需部署者填自己的仓库名）

## 图像
`comic-art/` 为原创科研叙事插画。
`evidence/` 为教学模拟数据图，不代表真实实验测量。

## 运行
直接打开 `index.html` 即可。若浏览器对本地文件限制较多，可在目录中运行：

    python -m http.server 8000

然后访问本机 8000 端口。

## 部署
整个目录可以直接上传到 GitHub Pages / Netlify / Vercel 静态站点。
GitHub Pages 可从仓库根目录发布；`.nojekyll` 已提供。

## GitHub Issues 成绩投稿
在 `index.html` 中搜索：

    const SCORE_REPO="";

改成：

    const SCORE_REPO="你的GitHub账号/仓库名";

即可让“提交成绩”按钮打开你自己的 GitHub Issues 投稿页。

## 科学依据
章节主题参考 Arc Institute 2026 Virtual Cell Challenge、State，以及 CZI 对 multimodal / multiscale virtual-cell modeling 的公开资料。游戏中的数值、细胞图和实验结果均为教学模拟。
