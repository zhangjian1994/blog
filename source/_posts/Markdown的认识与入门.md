---
title: Markdown的认识与入门
date: 2017-02-19 13:22:39
tags: Markdown
---
Markdown 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的HTML 标记语言来说，Markdown 可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。
# 认识Markdown
在刚才的导语里提到，Markdown 是一种用来写作的轻量级「标记语言」，它用简洁的语法代替排版，而不像一般我们用的字处理软件 Word 或 Pages 有大量的排版、字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。目前来看，支持 Markdown 语法的编辑器有很多，包括很多网站（例如简书）也支持了 Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出 HTML 格式的文件用来网站发布，也可以十分方便的导出 PDF 格式，这种格式写出的简历更能得到 HR 的好感。甚至可以利用 CloudApp 这种云服务工具直接上传至网页用来分享你的文章，全球最大的轻博客平台 Tumblr，也支持使用 Mou 这类 Markdown 工具进行编辑并直接上传。
## Markdown 官方文档
这里可以看到官方的 Markdown 语法规则文档，当然，后文我也会用自己的方式，阐述这些语法在实际使用中的用法。
[创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)
[Markdown 中文版语法说明](http://wowubuntu.com/markdown/#list)
### 使用 Markdown 的优点
* 专注你的文字内容而不是排版样式。
* 轻松的导出 HTML、PDF 和本身的 .md 文件。
* 纯文本内容，兼容所有的文本编辑器与字处理软件。
* 可读，直观。适合所有人的写作语言。
![Mou icon](http://mouapp.com/Mou_128.png)
# Markdown 语法的简要规则
### 标题
![1](http://cdn.sspai.com/attachment/thumbnail/2014/04/15/620e64aa6522f5eaeb788a8b5f1faa5c10f74_mw_800_wm_1_wmp_3.jpg)
标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 # 号即可。
 # 一级标题

 ## 二级标题

 ### 三级标题
以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。
### 列表
熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加 1. 2. 3. 符号要和文字之间加上一个字符的空格。
![2](http://cdn.sspai.com/attachment/thumbnail/2014/04/15/a72338b96cf4bfc1dacd610756786ae310f75_mw_800_wm_1_wmp_3.jpg)
### 引用
如果你需要引用一小段别处的句子，那么就要用引用的格式。

 > 例如这样

只需要在文本前加入 > 这种尖括号（大于号）即可
![3](http://cdn.sspai.com/attachment/thumbnail/2014/04/15/07bd8bf6fd38ea7d3bffdc3cae04f6f210f76_mw_800_wm_1_wmp_3.jpg)
### 图片和链接
插入链接与插入图片的语法很像，区别在一个 !号

插入图片的地址需要图床，这里推荐 CloudApp 的服务，生成URL地址即可。
![4](http://cdn.sspai.com/attachment/thumbnail/2014/04/15/f96c892fc63933ab186235f7c910753b10f77_mw_800_wm_1_wmp_3.jpg)
### 粗体与斜体
Markdown 的粗体和斜体也非常简单，用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法。

例如：**这里是粗体** *这里是斜体*
