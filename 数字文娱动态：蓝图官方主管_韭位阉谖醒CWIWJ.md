蓝图官方主管【Q-——333307——】蓝图官方主管【 辋芷《888yx●vip》 】
蓝图官方主管【Q-——333307——】蓝图官方主管【 辋芷《888yx●vip》 】

 从零到一：用 GitHub 搭建个人技术博客的完整指南

> 还在羡慕技术大牛的个人站点？其实，利用 GitHub Pages 和 Jekyll，你也能在半小时内拥有一个高颜值、免费且支持自定义域名的专属博客。本文将手把手带你完成从仓库创建到文章发布的全部流程。

为什么选择 GitHub Pages？  
对于开发者而言，GitHub 不仅是一个代码托管平台，更是一个绝佳的建站工具。它提供静态托管服务，支持绑定自定义域名，且完全免费。更重要的是，你所有的文章和配置都可以用 Git 进行版本管理，写文章就像提交代码一样自然。

 第一步：创建你的博客仓库

首先，你需要一个 GitHub 账号。登录后，点击右上角的 "New repository" 按钮。  
关键点：仓库名称必须设置为 `你的用户名.github.io`（例如 `zhangsan.github.io`）。这是 GitHub Pages 的硬性规则，否则无法启用页面服务。选择“Public”可见性，并勾选“Add a README file”。

 第二步：选择并启用 Jekyll 主题

GitHub 原生支持 Jekyll 静态站点生成器。最简单的激活方式：进入仓库的 Settings → Pages 页面，在“Source”下拉菜单中选择 `Deploy from a branch`，并将分支设为 `main`。保存后，GitHub 会自动为你的裸仓库生成一个默认的 Jekyll 站点。

想让博客更好看？在仓库根目录创建一个 `_config.yml` 文件，填入以下基础配置：

```yaml
title: 我的技术博客
description: 专注后端与云计算
theme: jekyll-theme-cayman
```

GitHub 会自动拉取对应的主题模板。你还可以在 `_config.yml` 中加入 `url` 和 `baseurl` 字段，以便在本地预览时同步路径。

 第三步：撰写你的第一篇文章

在仓库根目录新建 `_posts` 文件夹，文章命名规范为 `YYYY-MM-DD-标题.md`（例如 `2025-06-10-git-tips.md`）。每篇文章必须在顶部包含 YAML Front Matter 头信息，用于声明布局和标题：
```yaml
---
layout: post
title: "Git 的五个实用技巧"
date: 2025-06-10
categories: 教程
---
```

文章内容支持 Markdown 语法，代码块、图片展示、流程图都能完美渲染。写完 push 到 main 分支后，等待 1-2 分钟，访问 `你的用户名.github.io` 即可看到效果。

 进阶：绑定自定义域名

在仓库的 Settings → Pages 中，Custom domain 输入框里填入你的域名（如 `blog.example.com`），点击 Save。随后去你的域名服务商处，添加一条 CNAME 解析记录，指向 `你的用户名.github.io`，并开启 CDN 加速。域名生效后，GitHub 会自动为你的站点签发 HTTPS 证书。

---

互动引导：你在搭建博客的过程中遇到过哪些问题？是主题配置报错，还是域名解析卡壳？欢迎在评论区留言，我会第一时间为你解答。如果这篇文章对你有帮助，请点赞转发，让更多小伙伴告别繁琐的建站流程！

---

本文关键词：GitHub Pages、Jekyll 教程、个人博客搭建、自定义域名、静态站点生成。

相关推荐：

https://github.com/brownbarbara40/yzuprm/blob/main/2026%E6%9D%83%E5%A8%81%E7%83%AD%E6%A6%9C%EF%BC%9A%E8%93%9D%E5%9B%BE%E6%B3%A8%E5%86%8C%E5%BC%80%E6%88%B7_%E6%AD%A2%E8%8A%AD%E8%88%B7%E7%84%8A%E7%8F%8ALLFZU.md

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />

相关推荐：

https://github.com/brownbarbara40/yzuprm/commit/591635eb6c454f5310326131a8d06a9e6c97a8b4

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />
相关推荐：

https://github.com/stanleykrystal60/anipll/blob/main/2026%E7%A7%91%E6%8A%80%E4%B8%A5%E9%80%89%EF%BC%9A%E8%93%9D%E5%9B%BE%E6%B3%A8%E5%86%8C%E5%9C%B0%E5%9D%80_%E5%8F%B3%E5%AF%84%E5%93%A6%E9%85%9A%E8%83%83DXRFL.md

<img src="https://i.postimg.cc/kGjWYk5W/lantu-00006.png" />
相关推荐：

https://github.com/stanleykrystal60/anipll/commit/faabd6f29e109b225d5f8bc03e0351b889a1a7ca

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
