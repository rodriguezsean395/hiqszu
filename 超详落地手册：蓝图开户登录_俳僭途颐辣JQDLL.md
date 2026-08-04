蓝图开户登录【Q-——333307——】蓝图开户登录【 辋芷《888yx●vip》 】
蓝图开户登录【Q-——333307——】蓝图开户登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南（2025最新）

还在羡慕别人炫酷的技术博客？其实你也能在 10分钟 内拥有一个属于自己的独立博客，而且 完全免费。本教程将手把手教你使用 GitHub Pages 和 Hexo 框架，从零搭建一个高速、稳定、支持自定义域名的个人网站。

 为什么选择 Hexo + GitHub Pages？

- 零成本：GitHub 提供 1GB 免费静态空间，无需购买服务器
- 极速访问：静态页面加载速度堪比 CDN，国内访问也很快
- SEO 友好：纯静态 HTML，搜索引擎收录效果极佳
- 版本管理：所有文章存入 Git 仓库，历史版本一键回溯

 搭建前的准备工作

开始之前，请确保你已完成以下两步：

1. 注册 GitHub 账号（官网：github.com）
2. 安装 Node.js（版本不低于 12.0，可在官网下载 LTS 版本）

 三步快速部署网站

第一步：创建 GitHub 仓库
新建一个仓库，仓库名必须为 `你的用户名.github.io`（例如 `wangxiaoming.github.io`）。这个特殊命名会让 GitHub 自动为你启用 Pages 服务。

第二步：本地安装 Hexo 并生成网站
打开终端，依次执行以下命令：

```bash
npm install -g hexo-cli
hexo init blog
cd blog
npm install
hexo server
```

执行完最后一行代码后，浏览器访问 `localhost:4000`，你已经能看到默认博客页面了。

第三步：部署到 GitHub Pages
在博客根目录打开 `_config.yml` 文件，修改下列配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后执行 `npm install hexo-deployer-git --save` 和 `hexo d`，稍等一分钟，访问 `你的用户名.github.io`，你的博客就正式上线了！

 让文章更容易被搜索收录的小技巧

1. 关键词前置：标题中自然融入“GitHub Pages”、“Hexo教程”等核心词
2. 单页800字：每篇文章保证至少 800 字，提高原创评级
3. 内链矩阵：在文末添加其他文章链接，引导爬虫抓取更多页面

 踩坑提醒：新手最容易犯的 3 个错误

- 仓库名大小写错误：GitHub 用户名是 WANGXIAOMING，仓库名就必须是 `WANGXIAOMING.github.io`
- Node.js 版本过旧：请务必安装 12.0 以上版本，否则会报 `SyntaxError`
- 修改主题后没有清除缓存：换主题后执行 `hexo clean` 再重新部署

---

你的第一个 GitHub 博客项目已经启动了！ 如果在搭建过程中遇到任何报错，欢迎在评论区留言你的具体错误代码，我会 24 小时内帮你排查。也可以收藏本文，下次用得上时直接对照操作。实践出真知，动手试试吧，期待看到你的第一个线上作品🎉。

相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E6%9D%83%E5%A8%81%E6%94%BB%E7%95%A5%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%BC%80%E6%88%B7%E5%AE%98%E7%BD%91_%E9%86%87%E8%84%9A%E9%B2%81%E5%AD%9B%E8%B5%9DYFBXF.md

<img src="https://i.postimg.cc/ZnqdNVLn/lantu-00012.png" />

相关推荐：

https://github.com/martinezkelly827/fwhecg/commit/bdc21f58b421c0e5e2852336ef436a24dc37753e

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E6%9D%83%E5%A8%81%E7%88%86%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%BC%80%E6%88%B7%E5%B9%B3%E5%8F%B0_%E8%85%8B%E5%B1%95%E9%9D%A1%E7%86%AC%E8%8D%92NHBIP.md

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/78bf1369f87fb1d4a5d7b96c84182f74e19fe2dd

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
