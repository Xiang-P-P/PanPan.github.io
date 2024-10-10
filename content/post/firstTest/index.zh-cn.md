---
title: 第一篇yu-hugo-theme
description: 简单写一下
date: 2024-10-10
slug: test-chinese
image: test.jpg
categories:
    - 写作
---

## 正文
### 侧边优化滚动条失效的话将\assets\scss\partials\base.scss 的 line 20-23注释掉

在 `/assets/scss/custom.scss` 中加入以下代码：

```scss
//将滚动条修改为圆角样式
//菜单滚动条美化
.menu::-webkit-scrollbar {
  display: none;
}

// 全局滚动条美化
html {
  ::-webkit-scrollbar {
    width: 20px;
  }

  ::-webkit-scrollbar-track {
    background-color: transparent;
  }
```

### 评论区参考[https://waline.netlify.app/get-started.html#获取-app-id-和-app-key](https://waline.netlify.app/get-started.html#%E8%8E%B7%E5%8F%96-app-id-%E5%92%8C-app-key)

### 修改背景三角形hugo-test\layouts\partials\footer\custom.html

```jsx
<script src="https://npm.elemecdn.com/nprogress@0.2.0/nprogress.js" crossorigin="anonymous"></script>
<link rel="stylesheet" href="https://npm.elemecdn.com/nprogress@0.2.0/nprogress.css" crossorigin="anonymous" />
<script  color="255,182,193" opacity='1' zIndex="-1" count="100" src="https://cdn.bootcss.com/canvas-nest.js/2.0.4/canvas-nest.js" type="text/javascript"></script>
<!-- <script type="text/javascript" src="https://cdn.jsdelivr.net/gh/Ukenn2112/UkennWeb@3.0/index/web.js"></script> -->
```