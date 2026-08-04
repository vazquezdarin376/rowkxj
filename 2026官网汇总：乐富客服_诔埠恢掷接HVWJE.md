乐富客服【Q-——333307——】乐富客服【 辋芷《888yx●vip》 】
乐富客服【Q-——333307——】乐富客服【 辋芷《888yx●vip》 】

 从零搭建个人网站：GitHub Pages + Hexo 完整教程

刚接触编程或者想建立个人博客的朋友，经常卡在第一步：服务器太贵、域名配置太麻烦。其实，用 GitHub Pages 部署一个静态网站完全免费，配合 Hexo 框架，半小时就能上线一个清爽的博客。这篇教程不绕弯子，直接给你能跑通的步骤。

 为什么要用 GitHub Pages + Hexo？

- 免费稳定：GitHub 提供的托管服务，全球访问速度快。
- 版本管理：文章和配置都放在仓库里，不怕丢。
- 高度定制：主题丰富，社区活跃，想改哪里改哪里。
- 降低门槛：不需要懂后端和数据库，纯静态页面够用。

 搭建前需要准备什么？

1. 一个 GitHub 账号（没有就注册一个，几分钟搞定）。
2. 本地安装 Node.js（自带 npm 包管理器）。
3. 一个顺手点的代码编辑器（VS Code 就很不错）。

 实操步骤：从零到发布

 第一步：安装 Hexo 命令行工具
打开终端，输入下面的命令，全局安装 Hexo：
```bash
npm install -g hexo-cli
```

 第二步：初始化博客项目
找个干净目录，执行：
```bash
hexo init my-blog
cd my-blog
npm install
```
这样本地就生成了博客的骨架，你可以跑 `hexo server` 在本地预览效果。

 第三步：配置关联 GitHub
在 GitHub 上新建仓库，名字格式必须是：`用户名.github.io`（注意：你的 GitHub 用户名加 .github.io，不是任意名）。然后，编辑博客根目录下的 `_config.yml` 文件，在最后找到 `deploy` 配置项，改成：
```yaml
deploy:
  type: git
  repo: 你仓库的HTTPS地址
  branch: main
```

 第四步：一键部署上线
在项目目录执行两条命令：
```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```
等待终端跑完，打开浏览器访问 `用户名.github.io`，你的网站已经上线了。

 常见问题小排查

- 部署后没变化：记得先 `hexo clean` 清缓存再重新生成。
- 端口被占用：换端口用 `hexo server -p 4000`。
- 图片不显示：检查路径是否为绝对路径，或者使用图床。

 下一步还能做什么？

网站上线只是开始，你可以换一套更好看的主题，比如 Next、Fluid；可以配置自己的域名；还可以接入 Giscus 评论系统，让读者能和你互动。每完成一个功能，都是一次能力和信心的积累。

---

如果你在部署过程中卡住了，或者想了解某个主题的详细配置，在评论区留下你的问题，看到就会回复。也可以把这篇教程转发给正在学前端的朋友，一起动手，比一个人闷头看文档效率高得多。

相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E6%9D%83%E5%A8%81%E7%83%AD%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91%E5%AE%98%E7%BD%91_%E8%AF%BD%E5%BE%98%E7%84%95%E6%8B%B1%E7%93%A4SYLFS.md

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />

相关推荐：

https://github.com/leebradley6/ubrqlg/commit/974b3eb6c4bff5eeb313a3a77dc4779bbe6d32c7

<img src="https://i.postimg.cc/1XjxMj0W/lefu-00015.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/blob/main/%E8%B6%85%E5%85%A8%E5%AE%9E%E6%93%8D%E6%8C%87%E5%8D%97%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91%E5%BC%80%E6%88%B7_%E5%AD%9C%E4%BA%A4%E6%AA%80%E9%B9%BF%E4%B8%94SMRFZ.md

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/commit/cba92dfc9306120dac3bc0bde7f96cbe6aec41a9

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
