乐富官方下载【Q-——333307——】乐富官方下载【 辋芷《888yx●vip》 】
乐富官方下载【Q-——333307——】乐富官方下载【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：GitHub Pages + Hexo 完整教程

> 想拥有一个完全属于自己的技术博客？不用买服务器，不用备案，用 GitHub Pages 就能免费搞定。这篇文章手把手带你从零开始，搭好就能用。

 为什么要用 GitHub Pages 写博客？

很多朋友问我，为什么不用现成的博客平台？我的答案很简单：可控性和学习价值。

- 免费托管：GitHub Pages 提供无限流量，绑定自定义域名也完全免费
- 版本管理：所有文章都是 Git 仓库里的 Markdown 文件，写错了随时回滚
- 高度定制：主题、样式、插件全部自己掌控，不被打扰
- SEO 友好：静态页面加载快，搜索引擎收录效果不错

 搭建前的准备工作

开始之前，你需要确认以下工具已经准备好：

1. GitHub 账号 —— 还没有？去注册一个，顺便把 SSH key 配置好
2. Node.js 环境 —— 推荐安装 LTS 版本，Hexo 依赖它运行
3. Git 客户端 —— 命令行工具，Windows 用户记得用 Git Bash

 三步完成博客搭建

 第一步：创建 GitHub 仓库

登录 GitHub 后，点击 `New repository`，仓库名必须是 `你的用户名.github.io` 格式。记住，一定要公开，这关系到 Pages 服务能否正常启动。

 第二步：本地安装 Hexo 并初始化

打开终端，输入以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

初始化完成后，你会看到 `source/_posts` 目录，以后的新文章就放在这里。执行 `hexo s` 启动本地服务，浏览器访问 `localhost:4000` 就能看到默认博客了。

 第三步：部署到 GitHub Pages

在 `_config.yml` 文件的 `deploy` 部分，填上你的仓库地址：

```yaml
deploy:
  type: git
  repo: git@github.com:你的用户名/你的用户名.github.io.git
  branch: main
```

然后安装部署插件，执行：

```bash
npm install hexo-deployer-git --save
hexo d
```

等待命令行输出 `Deploy done`，访问 `你的用户名.github.io`，大功告成！

 让博客更好用的几个建议

- 换主题：Hexo 官网有大量免费主题，挑一个合眼缘的，克隆到 `themes` 目录即可
- 配域名：在仓库的 `Settings > Pages` 里填上你的域名，再到域名商处加一条 CNAME 记录
- 写文章模板：修改 `scaffolds/post.md`，把标签、分类这些常用字段预设好，写起来更顺手

 总结

从注册 GitHub 到部署上线，整个过程不到半小时。搭建博客只是个开始，更重要的是持续输出。折腾的过程本身就是一种学习，遇到问题欢迎在评论区留言，也欢迎分享你搭建博客时踩过的坑。

如果这篇文章对你有帮助，点个赞让更多人看到，或者分享给你身边想建博客的朋友。想获取更多 Vim 配置、效率工具干货？关注我，更新不迷路。

相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E5%AE%98%E7%BD%91%E6%B1%87%E6%80%BB%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C_%E8%AF%B4%E7%A9%BA%E7%98%B8%E8%B0%B0%E5%8F%8BGTTTA.md

<img src="https://i.postimg.cc/50pWQ0XN/lefu-00012.png" />

相关推荐：

https://github.com/martinezkelly827/fwhecg/commit/7993748c38d8a99a432ce7ee1d51b811e640ee67

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E6%9D%83%E5%A8%81%E8%A7%A3%E6%9E%90%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E7%BD%91%E5%9D%80_%E6%83%BA%E9%99%85%E4%B8%80%E5%B1%B9%E4%BF%A3WWJJD.md

<img src="https://i.postimg.cc/XJx6BJpR/lefu-00011.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/ead851f9814530e8d3af5940ca988ae475bf7710

<img src="https://i.postimg.cc/xTBDzB1n/lefu-00020.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
