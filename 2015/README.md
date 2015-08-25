##TonyBook 2015.

托尼托尼学习小组 2015期刊([Github地址](https://github.com/targetkiller/tonybook))

`少侠的学习热情那么高昂，吓得我都坐在了地上`

本项目以markdown贡献内容，最终以gitbook形式生成。

###使用方法
> 1.Github fork

到 [https://github.com/targetkiller/tonybook](https://github.com/targetkiller/tonybook) fork一份代码到自己的repo，然后`git clone`到本地，如：

```javascript
git clone https://github.com/targetkiller/tonybook.git
```

为了便于文章的管理和阶段性的收归，学习期刊以年份为节点，年刊里又分多期，例如第一期为Vol1。

> 2.畅快地使用markdown

 开写！

 要新开文章请进入到相应文件夹，例如`cd 2015/vol1/`进入第一期。
 
 然后新建md文件开写，命名规范是中划线&英文语义，例如`小啪教你svg`->`janily-teaching-svg.md`

 markdown语法多爽不用怎么介绍了，具体看看这个Github的[markdown规则](https://help.github.com/articles/github-flavored-markdown/)。
 
 可以选用各种markdown编辑器来编写，例如sublime+markdown插件、[MarkdownPad](http://markdownpad.com/)、[MOU](http://mouapp.com/)、Github Issue&Wiki也是可以的。
 
 当然，这里推荐使用Gitbook来编写，因为本刊最终使用Gitbook呈现，使用它可以直接预览最终效果，安装教程在文章后。
 
 尽情享受markdown带来的写作快感！

> 3.更新项目

fork下来后最好新建一个自己的git分支，之后更新只需要git fetch/pull主目录，然后跟自己的分支合并就行了。若增加了自己的改动，则可以pull request到主分支，收到后会尽快合并。

新手git的操作教程请点[这里](http://git-scm.com/book/zh/v2)，更详细戳[这里](http://git-scm.com/book/zh/v2)。

> 4.发布

![tonystudy_qrcode](http://storyincafe.com/tonystudy_qrcode.jpg)

发布后的文章会在[http://tonystudy.github.io](http://tonystudy.github.io)上看到（左边侧边栏是demo列表）。

每一期学习结束后才会更新上去，因此你要做的，就是用markdown写文章就好了！

##安装gitbook

该期刊最终以Gitbook形式发布，在本机装一个Gitbook无疑更加方便直观，它支持的动态服务器可以让你一边写一边看到改动，也十分爽。

ps:由于公司内网问题，各种代理&镜像都难以安装Gitbook，若staffWifi或家里网络则建议安装！

> 1.开始安装

[nodejs](http://nodejs.org/)和[npm](https://www.npmjs.com/)安装请看官网。

以上都安装后请继续关键的下一步，安装gitbook-cli。

```javascript
// mac和linux用户请自行sudo
npm install -g gitbook-cli
```
> 2.生成小书

先到2015目录，`cd 2015/`，然后安装依赖的Gitbook并编译：

```javascript
gitbook build
```

当然也可以自己安装gitbook，若公司安装失败一般都是代理问题。


```javascript
npm install -g gitbook
```

搞定，安装并编译成功后即可打开`_book/`里面查看静态的网页！

当然，也可以使用它自带的实时刷新服务器一边写一边预览：

```javascript
gitbook serve
```

其他建议或疑问，随时欢迎联系tqtan。


