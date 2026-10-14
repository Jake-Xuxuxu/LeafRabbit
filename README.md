# 拾页 · 私人日记

一个静态、无服务器的中文日记网页，可通过 GitHub Pages 发布。日记条目仅储存在打开网页的浏览器 `localStorage` 中，不会上传到 GitHub 或其他服务器。请定期使用页面右上角的导出按钮备份。

## 发布到 GitHub Pages

1. 将仓库设置为公开，上传此项目文件。
2. 在仓库 **Settings → Pages → Build and deployment** 中，将来源设为 **GitHub Actions**。
3. 推送到 `main` 分支后，工作流会自动发布。页面地址会显示在 **Settings → Pages**。

网页使用 Google Fonts 提供字体；无法连接时会自动回退到本机字体。

