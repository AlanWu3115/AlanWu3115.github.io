---
title: "主页"
type: "docs"            # 使用 Docsy 的 docs 布局（会启用左侧导航/侧边栏）
weight: 1
draft: false
description: "AlanWu 的个人博客与技术笔记 — 教程、心得与工具使用经验汇总。"

# 把 /posts/** 下的页面当作 blog 类型处理（会让 Docsy 的 blog 布局可用）
cascade:
  - _target:
      path: "/posts/**"
    type: "blog"
---

{{< blocks/cover image_anchor="top" width="full" color="white" >}}
<h1 class="display-1 mt-0 mt-md-5 pb-4">AlanWu 的博客</h1>
<p class="lead">记录学习与实验 —— Node.js、Hugo、Linux 等技术笔记与实战心得。</p>
<p><a class="btn btn-primary btn-lg" href="/posts/">查看文章 / All posts</a></p>
{{< /blocks/cover >}}

欢迎来到我的博客！下面是一些快速入口和亮点内容。

## 快速入口
- 🗂️ <a href="/posts/">文章列表（Posts）</a>
- 📚 <a href="/docs/">文档 / Notes</a>
- 🔍 搜索（如果已启用）

{{% alert title="提示" color="primary" %}}
如果你希望把 `/posts/` 改成 `/blog/`，只需把文章移动到 `content/blog/`，或把 cascade 的 path 改为 `"/blog/**"` 并在 `content/blog/_index.md` 创建一页。  
{{% /alert %}}

## 特色摘要
<div class="row">
  <div class="col-md-4">
    <h4>最新教程</h4>
    <p>实用、可复现的教程 —— 从环境搭建到部署实践。</p>
    <p><a class="btn btn-outline-primary" href="/posts/">查看</a></p>
  </div>
  <div class="col-md-4">
    <h4>工具与技巧</h4>
    <p>高频命令、配置片段、调试小技巧。</p>
    <p><a class="btn btn-outline-primary" href="/posts/">查看</a></p>
  </div>
  <div class="col-md-4">
    <h4>关于本站</h4>
    <p>基于 Hugo + Docsy，主题默认样式、代码高亮一应俱全。</p>
    <p><a class="btn btn-outline-primary" href="/about/">了解更多</a></p>
  </div>
</div>

---

**说明：** 上面使用了 Docsy 的 `blocks/cover`（大 hero）短码和 `alert` 短码来快速搭建漂亮的首页块；同时把首页 `type` 设为 `"docs"`，这样 Docsy 会用 docs 布局（带左侧导航/侧边栏）。更详细的 Docsy 页面模块与短码文档参见官方指南。 :contentReference[oaicite:0]{index=0}

