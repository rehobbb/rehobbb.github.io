# 结构工程学习与工具站

网址：https://rehobbb.github.io/

纯静态站点，GitHub Pages 直接发布 `main` 分支根目录，无构建步骤。每个页面是一个独立 HTML 文件，所有计算在浏览器内完成。

## 目录

| 路径 | 内容 |
|---|---|
| `index.html` | 首页目录（页面清单在文件内 `VOLS` 数组中登记） |
| `la/` | 线性代数预备 00–05 |
| `rs/` | 振型分解反应谱法 |
| `tools/` | 计算工具 |
| `tables/` | 指标速查表 |
| `assets/mathjax/` | MathJax 3.2.2（tex-svg-full），本地加载 |

## 新增页面

1. 把 HTML 放入对应目录；公式脚本引用 `../assets/mathjax/tex-svg-full.js`，返回首页链接用 `../index.html`。
2. 在 `index.html` 的 `VOLS` 中登记编号、名称、相对路径、简介、日期。
3. 提交并推送到 `main`，约 1 分钟后生效。
