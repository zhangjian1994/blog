---
title: hexo的入门
date: 2017-03-20 23:14:43
tags: hexo
---
## hexo的优点
1.依赖少（仅依赖node），易于安装
2.台湾人写的，不用担心对中文支持不好
3.对程序员友好，要是愿意折腾还是有的折腾的
基于以上原因，我最终选择了hexo作为维护博客的工具。

##安装

首先，我假设你的机器上已经安装了node。安装好node，就可以用强大的npm命令来安装其他东西。

调出命令行，执行下面命令安装hexo：
npm install hexo -g

安装完后就可以执行hexo命令，这个页面列出了所有的命令。

作为入门者，不用上来就学会所有的命令。只在关键路径上，有几个命令需要掌握，下面逐个讲解：
	hexo init 目录名
例如
	hexo init blog
上面这条命令会新建一个名为blog的文件夹，然后在里面创建一大堆文件。
![lizi](http://www.maintao.com/img/2014/hexo-beginner's-guide_hexo-init.jpg)
完成后进入这个文件夹，以后就都要在这里捣鼓了。

##写文章

文章指的就是组成博客的一篇篇post，一般用md格式，除非你的md原稿找不到了，html格式也认。

把写好的md文件放在source/_posts目录下，它将是你以后最常打交道的目录。该目录下的hello-world.md是一个文章的范例，打开它，看到下面内容：
![lizi2](http://www.maintao.com/img/2014/hexo-beginner's-guide_hello-world.jpg)
三条横线上面的部分是文章的元数据，见文知义没什么可说的。其中date还是要强调一下。因为经常要按时间排序、归档，所以hexo给每篇文章都打了一个时间戳。如果不显式指定时间，hexo默认会用md文件的创建时间。
##运行网站

在blog目录下，执行命令
	hexo server
用浏览器打开localhost:4000就可以看到你的博客网站了！
![lizi3](http://www.maintao.com/img/2014/hexo-beginner's-guide_run-on-port-4000.jpg)
##生成静态文件
注意，你刚刚看到的页面并不是静态的。若要得到静态文件，还需执行一条命令：
	hexo generate
该命令会创建一个目录public，并在public下生成所有的静态文件。有了这些静态文件，只要有一个web server(例如Nginx)就可以独立运行网站了，完全没有其他依赖，这是WordPress和ghost无法比拟的。
