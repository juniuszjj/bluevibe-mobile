# 蓝调 · 手机版

公众号排版工具的**手机端页面**（iPhone Safari 用）。

打开：<https://juniuszjj.github.io/bluevibe-mobile/>

## 这是什么

- 写 Markdown → 选标题/字号/颜色 → **复制** → 粘到「订阅号助手」→ 手动插图；
- 排版引擎与电脑版扩展**同一份代码**（`themes.js` + `converter.js`）；
- 全部在本机浏览器里算，不上传任何内容。

## 怎么来的

由主仓库的 `tools/build_mobile.py` 打成**单个自包含 HTML** 后发布；
本仓库只放构建产物，**不要手改** `index.html`。
