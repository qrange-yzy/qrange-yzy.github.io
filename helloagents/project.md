# 项目技术约定

---

## 技术栈
- **站点生成:** Jekyll（GitHub Pages 兼容配置）
- **主题基础:** Minimal Mistakes 定制版本
- **样式体系:** Sass/SCSS
- **内容组织:** `_pages`、多内容集合（`_Notes`、`_Blogs`、`_Repositories` 等）

---

## 开发约定
- **页面入口:** 首页使用 `_pages/about.md` 作为 `/` 路由。
- **样式约定:** 全局样式放在 `_sass/`，由 `assets/css/main.scss` 统一导入。
- **内容原则:** 优先突出中文阅读体验、笔记与博客内容，其次再展示仓库和附属页面。

---

## 测试与流程
- **基础验证:** 修改样式或页面后优先执行 `bundle exec jekyll build`。
- **变更记录:** 重要页面改版需同步更新 `helloagents/` 知识库和历史方案包。
