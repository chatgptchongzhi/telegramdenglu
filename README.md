# 纸飞机 Telegram 中文教程

网站：https://chatgptchongzhi.github.io/telegramdenglu/

以后纸飞机、Telegram 相关文章统一在本仓库发布。文章源文件位于 `content/posts/`，采用 Markdown 和 Front Matter（title、description、slug、date、updated、category，值使用 JSON 双引号字符串）。

运行 `node build.cjs` 生成 `_site/` 和 `content/index.json`。推送 main 后 GitHub Actions 自动构建并部署 Pages。更新文章时只修改实际变动文章的 updated；不要批量刷新日期。
