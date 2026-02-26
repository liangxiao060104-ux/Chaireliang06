# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

这是一个基于纯 HTML、CSS、JavaScript 的个人动漫主题静态网站，采用苹果风格（清新简约）的响应式设计。

## 开发命令

无需构建命令。直接用浏览器打开 HTML 文件即可预览：

```bash
# 本地开发
# 直接在浏览器中打开 index.html
```

部署到 Vercel：推送到 GitHub 仓库后，Vercel 会自动部署。

## 项目结构

```
├── index.html          # 首页 - 英雄区域 + 推荐动漫网格
├── about.html          # 关于我 - 个人介绍 + 动漫观看时间线
├── collection.html     # 动漫收藏 - 卡片展示 + 筛选功能
├── merchandise.html    # 周边商品 - 手工艺品/收藏品展示
├── blog.html           # 博客 - 文章列表 + 侧边栏
├── contact.html        # 联系页面 - 表单 + 社交链接
├── todo-list.html      # 待办清单 - localStorage 持久化
├── vercel.json         # Vercel 部署配置
└── README.md           # 项目文档
```

## 技术栈

- 纯 HTML5 + CSS3 + JavaScript（无框架）
- 响应式设计（适配手机/桌面）
- localStorage 用于待办清单数据持久化
- Vercel 静态部署

## 设计风格

- 配色：淡粉色、薄荷绿、浅蓝色
- 布局：响应式网格 + 卡片式设计
- 交互：平滑过渡动画 + 悬停效果

## vercel.json 配置

输出目录为当前目录，所有路由重写到 index.html（SPA 模式）。
