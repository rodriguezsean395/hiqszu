蓝图娱乐平台【Q-——333307——】蓝图娱乐平台【 辋芷《888yx●vip》 】
蓝图娱乐平台【Q-——333307——】蓝图娱乐平台【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：GitHub Pages + Hexo 完整部署指南（2025最新）

> 你是否还在为搭建个人技术博客而烦恼？服务器贵、域名备案麻烦、维护成本高？今天教你用 GitHub Pages + Hexo 免费搭建一个高性能博客，支持 HTTPS、自定义域名、自动部署，全程只需 30 分钟。

---

 一、为什么选择 Hexo + GitHub Pages？

- 完全免费：无需购买服务器，GitHub Pages 提供无限流量静态托管。
- 极速访问：静态页面加载快，配合 CDN 全球加速。
- 版本管理：所有文章 Markdown 源文件存入 GitHub，历史版本可追溯。
- 生态丰富：5000+ 主题插件，支持 PWA、SEO、评论等高级功能。

---

 二、本地环境搭建（5分钟）

 1. 安装 Node.js 和 Git
- Node.js 16+：从官网下载 LTS 版本，一路 Next 即可。
- Git：Windows 用户安装时勾选 `Add to PATH`。

 2. 安装 Hexo 脚手架
```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo s   启动本地预览，浏览器访问 http://localhost:4000
```

---

 三、GitHub 仓库配置（5分钟）

 1. 创建远程仓库
- 登录 GitHub，点击 New repository。
- 仓库名必须为：`<你的用户名>.github.io`（例如 `zhangsan.github.io`）。

 2. 部署密钥
在本地终端执行：
```bash
ssh-keygen -t rsa -b 4096 -C "你的邮箱"
```
将生成的 `id_rsa.pub` 内容添加到 GitHub → Settings → SSH and GPG keys。

---

 四、自动部署脚本（10分钟）

 1. 安装部署插件
```bash
npm install hexo-deployer-git --save
```

 2. 修改 `_config.yml`
```yaml
deploy:
  type: git
  repo: git@github.com:<你的用户名>/<你的用户名>.github.io.git
  branch: master
```

 3. 一键发布
```bash
hexo clean && hexo generate && hexo deploy
```

---

 五、SEO 优化技巧（加分项）

- 安装 sitemap 插件：`npm install hexo-generator-sitemap`，自动生成百度/谷歌收录的 sitemap.xml。
- 配置关键词：在文章 Front-matter 中添加 `tags` 和 `categories`。
- 启用压缩：安装 `hexo-all-minifier` 压缩 HTML/CSS/JS，提升 Pagespeed 分数。

---

 六、常见问题排查

| 问题 | 解决方案 |
|------|----------|
| `Permission denied` | 检查 SSH key 是否绑定 GitHub 账号 |
| 部署后 404 | 确认仓库名是否精确匹配用户名 |
| 图片打不开 | 在 `_config.yml` 中设置 `post_asset_folder: true` |

---

 七、进阶玩法推荐

- 绑定自定义域名：在仓库 Settings → Pages 中填写域名，并添加 CNAME 解析。
- 自动化部署：使用 GitHub Actions，push 代码后自动触发 hexo deploy。
- 多设备写作：将源码推送到独立分支（如 `hexo`），换电脑时 `git clone` 即可。

---

如果你在搭建过程中遇到任何坑，欢迎在评论区留言讨论。觉得有用的话，点赞 + 收藏 支持我继续输出更多技术干货！

---

本文关键词：GitHub Pages教程、Hexo博客部署、静态博客搭建、免费个人网站、SEO优化、自动部署、2025最新教程

相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E7%A7%91%E6%8A%80%E7%88%86%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80_%E5%AE%88%E7%BC%86%E5%8F%B9%E6%B7%AE%E8%AF%BDMMLNV.md

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

相关推荐：

https://github.com/martinezkelly827/fwhecg/commit/ecf7efc786c5d978a7540bc74d1e712a66082fe6

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/blob/main/2026%E7%AC%AC%E4%B8%80%E6%95%99%E7%A8%8B%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%9F%A0%E5%8B%92%E6%BA%90%E6%B7%8C%E5%AF%A5IVJRR.md

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/commit/18ad5f396635adad84137fcfb0bf2aaef9e08353

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
