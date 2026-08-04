蓝图官网注册【Q-——333307——】蓝图官网注册【 辋芷《888yx●vip》 】
蓝图官网注册【Q-——333307——】蓝图官网注册【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在为搭建个人博客发愁？服务器贵、备案烦、维护难？GitHub Pages + Hexo 组合拳，帮你零成本搞定高颜值博客。本文基于最新版Hexo 7.0，手把手教你从初始化到部署上线，全文干货无废话。

 为什么选择Hexo？

- 免费托管：GitHub Pages 提供无限流量静态托管
- 极速构建：Node.js驱动，生成上千篇文章仅需数秒
- 主题丰富：Next、Fluid等300+主题随意切换
- SEO友好：纯静态HTML，百度收录速度快

 三步快速部署（小白版）

 第一步：环境准备
安装Node.js（建议v18+）和Git，Windows用户注意勾选“Add to PATH”。

 第二步：安装Hexo
```bash
npm install hexo-cli -g
hexo init my-blog
cd my-blog
npm install
```

 第三步：部署到GitHub
1. 创建仓库：`用户名.github.io`
2. 修改根目录`_config.yml`：
```yaml
deploy:
  type: git
  repo: https://github.com/用户名/用户名.github.io.git
```
3. 执行部署命令：
```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

 进阶优化：面向百度SEO的4个关键设置

1. 永久链接优化：将`permalink`改为`:year/:month/:day/:title/`结构
2. 自动提交sitemap：安装`hexo-generator-sitemap`插件
3. 开启HTTPS：在仓库Settings勾选Enforce HTTPS
4. 移动端适配：Fluid主题默认支持响应式布局

 遇到常见问题怎么办？

Q：部署时报错“Repository not found”？
A：检查仓库名是否完全匹配用户名，且是否已添加SSH key。

Q：百度不收录新文章？
A：在百度站长平台提交站点地图，并主动推送链接。

需要完整项目源码？评论区留言获取。关注我，后续更新《Hexo性能优化：从2s到0.5s加载时间实战》，帮你打造极致访问体验。

---

延伸阅读：想了解如何给博客添加评论系统、数据统计和自动化部署？点击下方链接获取进阶指南。

相关推荐：

https://github.com/sheppardrandall419/okbjfs/blob/main/2026%E5%AE%98%E7%BD%91%E6%95%99%E7%A8%8B%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%9C%B0%E5%9D%80_%E7%90%A2%E6%80%9D%E6%B3%BC%E7%84%89%E5%80%9CIIWPR.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />

相关推荐：

https://github.com/sheppardrandall419/okbjfs/commit/2df08a532d5fb8c5e5184147beb3733e6ca38f4b

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E7%A7%91%E6%8A%80%E7%A7%91%E6%99%AE%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7_%E5%BD%9D%E5%91%98%E9%83%9D%E5%B4%96%E7%98%B8GGNOB.md

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/commit/375b8922142a87a34a1390e5e501d2a4da7dfa14

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
