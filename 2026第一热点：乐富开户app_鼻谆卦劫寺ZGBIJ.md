乐富开户app【Q-——333307——】乐富开户app【 辋芷《888yx●vip》 】
乐富开户app【Q-——333307——】乐富开户app【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕别人的技术博客？其实搭建一个属于自己的博客，只需要半小时。本文基于 GitHub Pages 和 Hexo 框架，手把手带你完成从环境配置到一键部署的全流程。全程免费，无需服务器，适合开发者、学生和写作爱好者。

 一、准备工作：你需要什么

开始之前，请确保你拥有：

- GitHub 账号（没有的话去 github.com 注册，免费）
- Node.js 环境（建议 v18 以上版本）
- 基础命令行知识（会打开终端即可）

> 如果你已经安装了 Git，那么环境基本齐了。不确定的可以直接往下看，遇到报错再排查。

 二、安装 Hexo 并初始化项目

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

这一步会生成博客的基础目录结构。别慌，你不需要理解每个文件，只需要知道 `source/_posts` 是放文章的地方。

 三、本地预览与写第一篇文章

执行 `hexo s`，浏览器访问 `http://localhost:4000`，你会看到默认主题。现在创建第一篇

```bash
hexo new "Hello World"
```

用任意编辑器打开 `source/_posts/` 下的 `.md` 文件，按照 Markdown 语法写内容。保存后刷新页面，实时预览你的新文章。

 四、部署到 GitHub Pages

这是最核心的一步。先创建一个公开仓库，命名为 `你的用户名.github.io`（必须严格一致）。

然后修改根目录下的 `_config.yml` 文件，填入你的仓库地址：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
```

最后执行：

```bash
npm install hexo-deployer-git --save
hexo g -d
```

部署完成！ 浏览器访问 `https://你的用户名.github.io`，你的博客已经上线。

 五、个性化配置与常见问题

 修改主题
Hexo 有大量免费主题，进入 `themes` 目录，克隆你喜欢的主题，并在 `_config.yml` 中切换 `theme` 字段即可。

 绑定自定义域名
在仓库设置有添加 CNAME 文件，指向你的域名，并在 DNS 服务商处配置解析即可。

 常见报错
- `port 4000 already in use`：换端口 `hexo s -p 5000`
- `deploy failed`：确认仓库地址无误，且已配置 SSH key

遇到其他问题，优先搜索终端报错关键词，基本都能找到答案。

 六、持续写作的心法

博客的价值在于持续输出。我的建议是：每周固定一个下午写一篇，不需要长篇大论，记录你本周踩过的坑、实现的功能，就是很好的内容。三个月后回头看，你会感谢现在的自己。

如果你在搭建过程中遇到任何问题，欢迎在评论区留言，我会逐一回复。也欢迎分享你搭建成功的链接，大家一起交流学习。你的第一步，就是现在。

相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E5%AE%98%E7%BD%91%E6%89%8B%E5%86%8C%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E6%8E%8F%E7%B2%9F%E6%B3%BB%E6%81%8D%E5%AE%A4FNBPQ.md

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />

相关推荐：

https://github.com/leebradley6/ubrqlg/commit/90b36ec47996564add37326b03cfd00fb3fee3b9

<img src="https://i.postimg.cc/XqJSfb5x/lefu-00014.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/2026%E6%9D%83%E5%A8%81%E7%9B%98%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C_%E5%97%9C%E9%86%8B%E5%A7%91%E6%98%BE%E5%A9%AAGGGNT.md

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/83fd066489b93d56078beae9be0f444490232052

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
