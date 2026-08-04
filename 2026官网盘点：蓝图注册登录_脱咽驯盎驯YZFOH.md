蓝图注册登录【Q-——333307——】蓝图注册登录【 辋芷《888yx●vip》 】
蓝图注册登录【Q-——333307——】蓝图注册登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是不是也想过拥有一个属于自己的技术博客？用 GitHub Pages 部署静态网站，不仅免费、稳定，还能绑定自定义域名，配合 Hexo 框架，十几分钟就能上线。

 为什么选择 GitHub Pages + Hexo

GitHub Pages 直接支持静态文件托管，无需服务器和数据库，天然适配 CDN 加速。Hexo 作为 Node.js 生态中最流行的博客框架，Markdown 写作、主题丰富、部署一条命令，对新手极其友好。

如果你熟悉 Vue 或 React，还可以用 VuePress 或 Docusaurus 替代，但 Hexo 的插件生态和教程数量目前仍是最充裕的。

 环境准备与初始化

1. 安装 Node.js：前往官网下载 LTS 版本，一路默认即可
2. 安装 Git：Windows 用户注意勾选“添加到 PATH”
3. 安装 Hexo CLI：
   ```bash
   npm install -g hexo-cli
   ```
4. 创建博客项目：
   ```bash
   hexo init my-blog
   cd my-blog
   npm install
   ```

 主题配置与文章发布

Hexo 默认主题简洁但功能有限，你可以在官网主题商店选择更现代的样式，比如 `NexT` 或 `Fluid`，下载后修改 `_config.yml` 中的 `theme` 字段即可。

写文章时，在 `source/_posts/` 下新建 `.md` 文件，填充内容后执行：

```bash
hexo clean && hexo g && hexo d
```

这会自动生成静态文件并推送至你的 GitHub 仓库，实现一键部署。

 进阶优化与常见问题

绑定自定义域名时，需要在仓库设置中启用 Pages 服务，并在 DNS 服务商处添加 CNAME 记录。想要更多互动功能，可以接入 Giscus 评论系统，基于 GitHub Discussions 实现，无第三方依赖。

遇到报错怎么办？ 90% 的问题是 Node 版本过低或网络问题，尝试切换 npm 镜像源即可解决：

```bash
npm config set registry https://registry.npmmirror.com
```

如果你在搭建过程中遇到任何问题，欢迎在评论区留言，我会定期回复。觉得本文有帮助的话，点个 Star 或分享给正在学前端的朋友，你的支持是我持续输出优质教程的最大动力。下一步我打算写一篇 Docusaurus 实战对比，想看的话在评论区扣个 1。

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E5%AE%98%E6%96%B9%E7%94%84%E9%80%89%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD_%E5%93%91%E5%82%A5%E9%B2%9C%E6%B6%9F%E5%86%80CWQQL.md

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/6902964feea4c74fcb53981c3cb2518066aaaba8

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/%E5%A8%B1%E4%B9%90%E5%9C%88%E6%96%B0%E8%B5%84%E8%AE%AF%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E4%BB%A3%E7%90%86_%E5%A3%AB%E7%9A%87%E8%80%98%E7%82%99%E5%8C%BBVWPEL.md

<img src="https://i.postimg.cc/kGjWYk5W/lantu-00006.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/a82987331b1023ec2e2c4ccbb33ef34e9696f29b

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
