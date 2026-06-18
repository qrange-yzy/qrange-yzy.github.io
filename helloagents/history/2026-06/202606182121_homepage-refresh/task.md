# 任务清单: 首页中文博客化改版

目录: `helloagents/history/2026-06/202606182121_homepage-refresh/`

---

## 1. 首页内容
- [√] 1.1 在 `_pages/about.md` 中重写首页结构和中文文案，验证 why.md#需求-首页中文博客化改版-场景-首次进入首页

## 2. 公共视觉样式
- [√] 2.1 在 `_sass/_variables.scss` 中调整全局颜色、字体和基础视觉变量，验证 why.md#需求-首页中文博客化改版-场景-首次进入首页
- [√] 2.2 在 `_sass/_base.scss`、`_sass/_page.scss`、`_sass/_sidebar.scss`、`_sass/_masthead.scss` 中统一页面、导航和侧栏样式，验证 why.md#需求-首页中文博客化改版-场景-首次进入首页

## 3. 文案与配置补充
- [√] 3.1 在 `_config.yml` 和 `_includes/author-profile.html` 中补充中文化站点文案

## 4. 安全检查
- [√] 4.1 执行静态安全检查，确认未引入敏感信息、外部依赖或高风险操作

## 5. 文档更新
- [√] 5.1 建立 `helloagents/` 知识库并记录本次首页改版

## 6. 测试
- [X] 6.1 执行 `bundle exec jekyll build` 验证站点构建
  > 备注: 当前环境缺少 `ruby` / `bundler`，`bundle` 命令不存在，未能完成本机构建验证。
