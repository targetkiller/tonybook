##TonyBook 2015.

托尼托尼学习小组学习总结小书([Github地址](https://github.com/isux/tonybook))

`少侠的学习热情那么高昂，吓得我都坐在了地上`

###使用方法
> 1.Github fork

到 [https://github.com/isux/tonybook](https://github.com/isux/tonybook) fork一份代码到自己的repo，然后`git clone`到本地，如：

```javascript
git clone https://github.com/targetkiller/tonybook.git
```

为了便于文章管理和阶段性书刊收归，以年份为节点。

> 2.安装gitbook

[nodejs](http://nodejs.org/)和[npm](https://www.npmjs.com/)安装请看官网。

以上都安装后请继续关键的下一步，安装[gitbook](https://www.npmjs.com/package/gitbook)。

```javascript
// mac和linux用户请自行sudo
npm install -g gitbook-cli
```
> 3.生成小书

先到2015目录，`cd 2015/`，然后安装依赖并编译：

```javascript
gitbook build
```

搞定，安装并编译成功后即可打开`_book/`里面查看静态的网页！

当然，也可以使用它自带的实时刷新服务器一边写一边预览：

```javascript
gitbook serve
```

> 4.畅快地使用markdown

 开写！
 markdown语法多爽不用怎么介绍了，具体看看这个[Github的markdown规则](https://help.github.com/articles/github-flavored-markdown/)。
 尽情享受markdown带来的写作快感！

###更新&发布

> 1.更新

最好新建一个git分支，写文后pull request到主库。
新手git的操作教程请点[这里](http://git-scm.com/book/zh/v2),更详细戳[这里](http://git-scm.com/book/zh/v2)。

> 2.发布

![tonystudy_qrcode](http://storyincafe.com/tonystudy_qrcode.jpg)

发布后的文章会到[http://tonystudy.github.io](http://tonystudy.github.io)。
每一期学习结束后才会更新上去。

右边侧边栏是demo列表，其他问题，随时联系tqtan。


