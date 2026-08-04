蓝图官方登录【Q-——333307——】蓝图官方登录【 辋芷《888yx●vip》 】
蓝图官方登录【Q-——333307——】蓝图官方登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是否想过拥有一个完全属于自己的技术博客？无需购买服务器，不用备案，甚至不需要懂后端开发——GitHub Pages + Hexo 就是目前最流行的免费博客解决方案。本文将从零开始，手把手教你完成搭建与部署。

 为什么选择 Hexo + GitHub Pages？

- 完全免费：托管在 GitHub 上，无限流量
- 极速访问：全球 CDN 加速，国内访问体验良好
- SEO 友好：纯静态页面，天然适配搜索引擎收录
- Markdown 写作：专注内容，忽略排版

 第一步：环境准备（10分钟）

在开始之前，请确保你的电脑已安装：

- Node.js（推荐 v18+，官网下载长期支持版）
- Git（版本管理工具）
- GitHub 账号（没有的话先去注册）

> 互动提示：如果安装过程中遇到任何报错，欢迎在评论区留言，我会第一时间帮你排查！

 第二步：本地搭建 Hexo 博客

打开终端，执行以下命令：

```bash
 全局安装 hexo 脚手架
npm install -g hexo-cli

 初始化博客项目（文件夹名随意，如 myblog）
hexo init myblog
cd myblog
npm install

 启动本地预览
hexo server
```

现在浏览器访问 `http://localhost:4000`，如果你看到了默认的 Hexo 页面，恭喜你——本地博客已经跑起来了！

 第三步：配置主题与写作

Hexo 默认使用 `landscape` 主题，但我个人强烈推荐 NexT 主题——它更简洁、更适合技术博客。

```bash
git clone https://github.com/next-theme/hexo-theme-next themes/next
```

然后修改 `_config.yml` 配置文件：

```yaml
theme: next
title: 你的博客名称
author: 你的昵称
```

写作新文章只需执行：

```bash
hexo new post "我的第一篇博客"
```

然后编辑 `source/_posts/` 下的 Markdown 文件即可。

 第四步：部署到 GitHub Pages

1. 在 GitHub 上新建仓库，命名为 `你的用户名.github.io`
2. 修改 `_config.yml` 中的部署配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: master
```

3. 安装部署插件并推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

等待一分钟，访问 `https://你的用户名.github.io`，你的博客就正式上线啦！

 收录建议与 SEO 优化

为了让百度更快收录你的站点，请务必：

- 打开 `themes/next/_config.yml`，设置 `enable: true` 开启 sitemap 插件
- 在百度站长平台提交你的站点链接
- 每篇文章设置合理的 Title 和 Description（不要超过80字）

 结语：开启你的技术写作之旅

搭建博客只是起点，坚持输出才是关键。建议每周至少更新一篇技术笔记，哪怕只是记录一个小坑的解决方案，长期积累下来都是宝贵的财富。

> 好消息：现在很多开发者通过技术博客获得了大厂的面试机会，甚至拿到付费专栏的邀约。你的下一篇博客，可能就是改变你职业轨迹的转折点。

如果你在搭建过程中遇到任何问题，或者有更好的优化技巧，欢迎在评论区留言讨论。也可以分享你的博客链接，我会去参观学习！如果这篇教程对你有帮助，不妨点个 Star 或分享给需要的朋友，让更多人用上免费又强大的 GitHub Pages。

相关推荐：

https://github.com/klinegina28/bhjqeg/blob/main/2026%E5%AE%98%E6%96%B9%E5%B9%B2%E8%B4%A7%EF%BC%9A%E8%93%9D%E5%9B%BE%E6%B3%A8%E5%86%8C%E5%A8%B1%E4%B9%90_%E5%8B%92%E8%B6%BE%E7%B0%A7%E9%B8%A6%E5%88%B0SGSAV.md

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />

相关推荐：

https://github.com/klinegina28/bhjqeg/commit/d866ef26a8526fbccd299511978356d703f0a5c1

<img src="https://i.postimg.cc/ZnqdNVLn/lantu-00012.png" />
相关推荐：

https://github.com/benderjessica393/clipwq/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1_%E8%AE%B6%E7%9B%96%E5%90%A8%E9%A2%90%E5%8F%8DXRMML.md

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />
相关推荐：

https://github.com/benderjessica393/clipwq/commit/5d7d5fa2be527b91a64dfdc4e4bba02f121da7e7

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
