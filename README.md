# Furina 的小角落

欢迎来到我的个人博客源代码仓库 —— 一个用 Hugo 搭建、部署在 GitHub Pages 上的简洁博客。这里记录着我的学习笔记、CTF 练习、随笔以及一些小工具和资源。

站点地址：https://furina-fukalos.github.io/

---

## 关于这个博客

- 由 Hugo 构建，使用主题：reimu（通过 submodule 管理）。
- 主要语言：简体中文。
- 内容以 Markdown 写作，放在 `content/` 目录下，常见页面包括：文章（`content/post/`）、关于（`content/about.md`）、友链（`content/friend.md`）等。

这是一个随写随记录的个人空间，欢迎浏览与交流。

---

## 本地运行（快速上手）

1. 克隆仓库并初始化子模块（主题）：

```bash
git clone https://github.com/Furina-Fukalos/furina-fukalos.github.io.git
cd furina-fukalos.github.io
git submodule update --init --recursive
```

2. 安装 Hugo（如果未安装，请参考 https://gohugo.io/getting-started/install/ ）。

3. 在本地预览：

```bash
hugo server -D
# 在浏览器打开 http://localhost:1313/
```

4. 构建静态站点：

```bash
hugo
# 生成文件位于 public/，可用于部署
```

---

## 写文章 / 维护

- 新文章放到 `content/post/`，使用 Markdown 编写。
- 页面与内容通过 front matter（YAML/TOML/JSON）配置元数据。
- 修改主题或样式时，请在 `themes/` 或 `layouts/` 中调整（如果使用 submodule，请谨慎更新主题以避免破坏自定义修改）。

---

## 部署

仓库设计用于配合 GitHub Pages 部署：
- 可手动将 `public/` 内容发布到 Pages 分支（如 gh-pages）或使用 GitHub Actions 自动构建并部署。 

---

## 致谢与资源

主题：hugo-theme-reimu（https://github.com/D-Sketon/hugo-theme-reimu）

---

## 许可

当前仓库未在根目录添加 LICENSE 文件；如果你希望开源或允许他人复用，请考虑添加合适的许可证（例如 MIT）。

---

## 联系我

- GitHub: https://github.com/Furina-Fukalos
- 站点: https://furina-fukalos.github.io/

如果你有建议或想交流的内容，欢迎以 Issue 或 PR 的方式联系我 😊
