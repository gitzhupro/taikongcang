## 如何更新网站内容

### 1. 更新基础信息
编辑 `data.json` 文件，修改：
- `siteConfig`: 网站标题、描述、关键词等
- `homePage`: 首页介绍文字、联系方式等
- `aboutPage`: 关于页面内容
- `navigation`: 导航菜单

### 2. 添加新文章
1. 在 `articles/` 目录下创建新文件夹，如 `new-article/`
2. 在文件夹内创建 `index.md` 文件，格式如下：

```markdown
---
title: 文章标题
subtitle: 文章副标题
cover: cover.jpg  # 封面图片文件名
publishTime: 2024-01-01 10:00  # 发布时间
---

# 文章标题

文章正文内容...

![图片描述](图片文件名.jpg)
