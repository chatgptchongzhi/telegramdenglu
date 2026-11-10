# Telegram 文章发布规则

今后所有纸飞机、电报、Telegram 相关文章默认发布到 chatgptchongzhi/telegramdenglu 的 main 分支。现有其他仓库旧文章不自动迁移。

正文放 content/posts/*.md，使用 Front Matter；运行 node build.cjs 自动生成站点、content/index.json 和 Sitemap。保留正文，只修正排版；不显示文章编号。每篇独立英文 slug、唯一 H1、Canonical 和 BlogPosting；真实 date/updated，不虚构作者或图片。

桌面目录在右侧，手机折叠目录，表格横向滚动。文末浅紫圆角引导根据主题编写，按钮“前往蜗壳海外小铺 →”，Telegram 使用 https://wokee888.shop/；当次用户要求优先，不重复广告。无主图也可发布。

发布前检查重复文章、官方链接、相关教程、构建和 SEO；只提交本次文件。推送后确认 Pages 部署、HTTP200、Sitemap、robots、无 noindex；不把发布、请求索引、收录混为一谈。
