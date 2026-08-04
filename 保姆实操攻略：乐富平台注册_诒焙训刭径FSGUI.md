乐富平台注册【Q-——333307——】乐富平台注册【 辋芷《888yx●vip》 】
乐富平台注册【Q-——333307——】乐富平台注册【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人的技术博客？其实利用GitHub Pages免费托管，半小时就能拥有自己的专属站点。今天这份Hexo部署指南，手把手带你完成从环境配置到域名绑定的全流程，哪怕你是零基础小白也能轻松跟上。

 为什么选择GitHub Pages + Hexo？

- 完全免费：无需购买服务器，GitHub自带CDN加速。
- 版本管理：文章即代码，天然支持Git回溯与协作。
- 极致速度：静态页面加载快，SEO表现优秀。
- 主题丰富：上千款Hexo主题，总有适合你的风格。

 第一步：环境准备与Node.js安装

Hexo基于Node.js，请先前往[nodejs.org](https://nodejs.org)下载LTS版本并安装。完成后打开终端验证：

```bash
node -v && npm -v
```

看到版本号即代表成功。国内用户建议同步配置npm淘宝镜像，后续安装依赖会快十倍：

```bash
npm config set registry https://registry.npmmirror.com
```

 第二步：安装Hexo并初始化项目

在终端执行以下核心命令，一键生成博客骨架：

```bash
npm install -g hexo-cli
hexo init my-blog && cd my-blog
npm install
```

随后本地预览效果：

```bash
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认页面即告成功。

 第三步：关联GitHub仓库与自动部署

1. 在GitHub新建仓库，命名格式必须为 `用户名.github.io`
2. 修改根目录 `_config.yml` 的deploy配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
```

3. 安装自动部署插件并推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

访问 `https://你的用户名.github.io` ，你的博客已全球可见！

 第四步：写作与日常维护技巧

新建文章只需一条指令：

```bash
hexo new "我的第一篇技术分享"
```

文章用Markdown书写，支持代码高亮与图文混排。建议在`_config.yml`中开启站点地图插件，对百度收录更友好：

```yaml
plugins:
  - hexo-generator-sitemap
```

 进阶优化：绑定自定义域名

购买域名后，在DNS解析中添加CNAME记录指向 `用户名.github.io`，并在`source/`目录新建CNAME文件写入你的域名即可。最后别忘了在GitHub仓库Settings的Pages选项中启用HTTPS。

 遇到问题怎么办？

常见报错如 `port 4000 already in use`，可执行 `hexo s -p 5000` 换端口。部署失败时先检查仓库名称是否完全匹配，再确认`_config.yml`中的`repo`地址是否含`.git`后缀。

如果你卡在某个步骤，欢迎在评论区附上报错截图，我会第一时间协助排查。

码字不易，如果这份教程帮你顺利上线了博客，请点个赞并分享给同样在折腾的朋友。 后续我会更新更多关于SEO优化、访问统计的进阶内容，关注我，咱们一起在技术写作的路上走得更远！

相关推荐：

https://github.com/vazquezdarin376/rowkxj/blob/main/2026%E7%A7%91%E6%8A%80%E8%A7%A3%E6%9E%90%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E6%B5%8B%E9%80%9F_%E7%93%B7%E7%86%AC%E9%9F%AD%E8%8B%8D%E8%BF%98IVWQK.md

<img src="https://i.postimg.cc/sf6RVMFw/lefu-00017.png" />

相关推荐：

https://github.com/vazquezdarin376/rowkxj/commit/3cbd568acaa29e39a4d82907ecf78451d2da6eb2

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />
相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E7%AC%AC%E4%B8%80%E7%94%84%E9%80%89%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%AE%98%E7%BD%91_%E7%BA%AA%E7%B4%AB%E9%98%82%E5%8D%B8%E6%98%A7CHNUO.md

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />
相关推荐：

https://github.com/martinezkelly827/fwhecg/commit/e6692fe54b836cfbbc1bfdfa4c03dba0acaa4526

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
