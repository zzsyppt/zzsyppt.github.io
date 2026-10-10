# zzsyppt.github.io

个人学术主页，基于 [AcadHomepage 原始模板](https://github.com/RayeRen/acad-homepage.github.io)。
模板来源版本：`2cc1577eeaf2f74dede6d016a70722dbd409ea2f`。保留原始 MIT 许可证。

网站地址：https://zzsyppt.github.io/

## 替换占位内容

- `_config.yml`：姓名、职位、机构、地址、邮箱和社交链接。
- `_pages/about.md`：个人简介、研究方向、News、Publications、Teaching、Services 和 Alumni。
- `_data/navigation.yml`：顶部导航；链接要与正文的 HTML `id` 一致。
- `images/avatar-placeholder.svg`：头像占位图。上传照片后修改 `_config.yml` 的 `author.avatar`。
- `_includes/head/custom.html`：网站图标。

空邮箱与 Scholar 链接目前显示“to be added”。填写 `_config.yml` 后会自动显示真实链接。
不需要的栏目可以从 `about.md` 及 `navigation.yml` 同时删除。

## 发布

在仓库 **Settings → Pages** 中选择 **Deploy from a branch**，分支为 `main`，目录为 `/ (root)`，保存。
GitHub Pages 使用 Jekyll 构建；后续提交到 `main` 会自动更新网站。

## 本地运行

安装 Ruby、Bundler 和 Jekyll 环境后：

```sh
bundle install
bundle exec jekyll serve
```

打开 http://127.0.0.1:4000 。

引用统计与 Analytics 默认未启用。添加实际 Scholar 信息后，可恢复原模板的引用爬虫及计划任务。

## Acknowledgments

- [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io), MIT License, Copyright (c) 2022 Yi Ren.
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes), MIT License.
- [Academic Pages](https://github.com/academicpages/academicpages.github.io), MIT License.
- Font Awesome, SIL OFL 1.1 and MIT License.
