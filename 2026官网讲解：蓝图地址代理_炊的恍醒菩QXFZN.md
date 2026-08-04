蓝图地址代理【Q-——333307——】蓝图地址代理【 辋芷《888yx●vip》 】
蓝图地址代理【Q-——333307——】蓝图地址代理【 辋芷《888yx●vip》 】

 从零搭建个人博客：我用GitHub Pages + Hexo实现了自动化部署

你有没有想过，不需要购买服务器，也能拥有一个属于自己的技术博客？

今天分享我的实践方案：GitHub Pages + Hexo + GitHub Actions。这套组合不仅免费，还能实现自动化部署，非常适合开发者和技术写作爱好者。

 为什么选择GitHub Pages？

作为一个开发者，我把代码托管在GitHub上，GitHub Pages 直接集成在仓库中，支持自定义域名和HTTPS。更重要的是，它和Git工作流无缝衔接——`git push` 触发自动构建，部署效率大幅提升。

 搭建核心步骤

 1. 初始化Hexo项目

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

 2. 配置GitHub仓库

创建一个 `<你的用户名>.github.io` 的仓库，将本地Hexo项目关联远程仓库。

 3. 实现自动化部署

在项目根目录创建 `.github/workflows/deploy.yml`，利用 GitHub Actions 在每次push后自动执行部署脚本：

```yaml
name: Deploy
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: actions/setup-node@v2
      - run: npm install && hexo generate
      - uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./public
```

 你还需要知道的关键细节

- SEO优化：Hexo的 `hexo-generator-seo-friendly-sitemap` 插件能自动生成sitemap，百度收录更快。
- 访问速度：开启GitHub的CDN加速，国内访问体验明显改善。
- 域名绑定：在仓库Settings的Pages选项中绑定自己的域名，记得在DNS服务商处添加CNAME解析。

 写在最后

这套方案我已经稳定运行一年多，零成本、免维护。如果你也想搭建个人技术博客，不妨试试这个组合。

如果你在搭建过程中遇到问题，欢迎点赞、收藏本文，并在评论区留言交流。你的支持是我持续输出高质量技术文章的最大动力。

相关推荐：

https://github.com/benderjessica393/clipwq/blob/main/2026%E7%A7%91%E6%8A%80%E7%83%AD%E6%A2%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%B9%B3%E5%8F%B0%E5%BC%80%E5%8F%B7_%E5%87%B3%E9%80%80%E6%9F%BF%E7%BB%A6%E5%B9%BDYLZTT.md

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />

相关推荐：

https://github.com/benderjessica393/clipwq/commit/e650d1251465ace6b5e59b86384c58dbd56a787e

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C_%E8%AF%BE%E5%87%A1%E5%81%8C%E6%A1%88%E4%B8%B6RRFNF.md

<img src="https://i.postimg.cc/ZnqdNVLn/lantu-00012.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/commit/39fb32f32fb558a8dc17ba8303bb2b53b63908d8

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
