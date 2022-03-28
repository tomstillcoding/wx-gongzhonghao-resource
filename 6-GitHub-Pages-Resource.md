# 视频中的详细步骤

## 搭建博客的步骤

1、首先你需要登录github，假设你的账号名是tomlovescode，去我的github页面（tomstillcoding），找到这个tomstillcoding.github.io的仓库

2、然后点击fork，结束后进入你fork的仓库

3、进入settings设置界面，更改仓库名为：你的github账号名.github.io，比如你的github账号名是ponyma，那这里就要填ponyma.github.io

4、再进入Settings，选择左边的Pages页面，进去后把Source这里选择为gh-pages，点击保存（Save），上面会显示你的博客地址了，但是现在这个博客是打不开的，因为github还没有帮你配置完成。

5、点击上面的Action，等待最新的黄色图标变绿，你可以想象github正在帮你生成你的博客界面

6、变绿后，进入你的博客地址，点击第一篇文章，你会发现，你的博客搭建成功了

7、结束了

## 写文章的步骤

1、你需要git clone下来你的博客，如果你不会用命令行，可以直接用Github Desktop，桌面版，也就是把你博客的所有代码全部都下载到你的电脑上，放上文章之后，再push到github上，github会自动帮你配置文章。

1.1、下载下来后，你一定要选择，如何使用这个fork仓库，你一定要选for my own purpose，也就是你之后的commit不要push到我的仓库去了，而是应该push到你自己的仓库去。

1.2 然后你打开本地的目录，就能看到你的仓库了，这里面就是你博客的所有代码

2、这里你需要下载一个markdown编辑器，来写博客，我用的是typora，就以这个为例子了，当然你要用vscode写也是可以，不过typora插入图片很方便。点开_post页面，这里就是你的全部文章放的地方

3、在_post目录下面，创建markdown文件，文件名要用2021-03-30-xxx.md的形式，也就是时间加上文件名的形式

4、用我给你们的示例文章里面的格式，文章的抬头要包括title, date, categories, tags, author信息

4.1 我们来写一篇文章，就把我这里的hello world示例复制一份，然后改一下文件名叫第一篇po文，把标题改一下，时间改一下，删掉标题图片。

4.2 记得一定要有typora-root-url（如果找不到这个，可以自己编写，或者点击typora上面的格式-图像-设置图片根目录，选择最外层的文件夹：即ponyma.github.io这个文件夹），删掉原来的图片。

4.3 然后设置一下typora的图片插入方式，点击设置里面左边的“图片”，像我一样配置好。然后我们插入一张图片，确定创建目录，因为以后我们的图片都会放在同一个目录下，方便整理。进入我们的文件夹，你就可以看到对应路径下面，已经保存了我们的图片

5、然后文章就是正常的markdown编写方式

6、随后我们把我们的更改push到github上，github desktop版会简单很多。

7、然后等待Action里面最新的一项pages build and deployment变成绿色，这个页面有缓存，所以有的时候内容不一定是最新的，要强制刷新一下，等他变绿了就可以了，你的博客会自动更新内容。回到博客，强制刷新，你会发现最新已经有文章了，点进去，图片、代码片段也都是正常显示的。

这就是写文章的全部了。系统会自动帮你配置好标签、存档、分类里面显示的内容。

# GitHub Pages 免费搭建博客的资源

## GitHub Pages

是GitHub提供的一个网页寄存服务，于2008年推出。可以用于存放静态网页，包括博客、项目文档甚至整本书。

[GitHub Pages 搭建教程](https://sspai.com/post/54608 )

GitHub Pages 可以用Hexo或Jekyll等方式，生成静态博客。你可以选择Hexo或Jekyll或其他的生成工具，下面是各种生成工具配合GitHub Pages的教程。

## Jekyll

Jekyll软件可以用于将文档转换成静态网页，该软件提供了将网页上传到GitHub Pages的功能。

[什么是Jekyll](https://jekyllcn.com/docs/home/)

[Github Pages + jekyll 全面介绍极简搭建个人网站和博客](https://zhuanlan.zhihu.com/p/51240503)

[使用 Jekyll 设置 GitHub Pages 站点](https://docs.github.com/cn/pages/setting-up-a-github-pages-site-with-jekyll)

[jekyll主题选择](http://jekyllthemes.org/)

[jekyll主题的配置](https://jekyllcn.com/docs/themes/)

## Hexo

Hexo 是一个快速、简洁且高效的博客框架。Hexo 使用 [Markdown](http://daringfireball.net/projects/markdown/)（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。

[超详细Hexo+Github Page搭建技术博客教程【持续更新】](https://segmentfault.com/a/1190000017986794)
