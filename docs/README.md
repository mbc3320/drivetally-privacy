# DriveTally GitHub Pages

本目录用于部署车计 / DriveTally 的公开网页，满足 App Store Connect 所需的技术支持网站、隐私政策网站和版权信息展示。

## 页面入口

假设 GitHub Pages 根地址为：

```text
https://你的用户名.github.io/你的仓库名/
```

App Store Connect 可填写：

- 简体中文 - 技术支持网站 URL：`https://你的用户名.github.io/你的仓库名/support.html`
- 简体中文 - 隐私政策 URL：`https://你的用户名.github.io/你的仓库名/privacy.html`
- 英语（美国）- Support URL：`https://你的用户名.github.io/你的仓库名/en/support.html`
- 英语（美国）- Privacy Policy URL：`https://你的用户名.github.io/你的仓库名/en/privacy.html`
- 版权：`2026 DriveTally`

## 部署说明

如果仓库使用 GitHub Pages：

1. 将 `github-page` 目录内容发布为 Pages 根目录，或在 Pages 设置中选择对应目录。
2. 部署完成后，打开上述 URL 确认页面可访问。
3. 将最终 URL 填入 App Store Connect 对应语言的 App 信息和 App 隐私页面。

## 本地预览

可以在本目录运行：

```bash
python3 -m http.server 8765
```

然后访问：

```text
http://localhost:8765/
```
