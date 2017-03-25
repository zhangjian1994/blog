---
title: HTML的基础语法
date: 2017-03-15 21:32:07
tags: HTML
---
HTML(Hyper Text Mark-up Language超文本标记语言)：不是编程语言，而是一种描述性的标记语言，用于描述网页中内容的显示方式，比如文字以什么颜色、大小来显示等，这些都是利用Html标记来实现。
# HTML的文档结构
	所有的网页文件，通过都是四对标记来构成文档的骨架，它们是：
	<html>  
  
      <head>  
  
           <title>  
  
                标题  
  
           </title>  
  
      </head>  
  
      <body>  
  
           正文  
  
      </body>  
  
</html>   

# 小结
	<html>…</html>标识网页文件的开始与结束，所有的Html元素，都要放在这对标记中。
	<head>…</head>标识网页文件的头部信息，如标题、搜索引擎关键字等
	<title>…</title>标识网页文件的标题
	<body>…</body>标识网页文件的主体部分
# 常见的HTML的标记语法
	1.单标记
	一．<标记名称>
		单一型，无属性值
		如：<br/>——表示换行符
	二．<标记名称属性=”属性值”>
		单一型，有属性值
		如：<hr width=”80%”/>
	2.双标记
	三．<标记名称>…</标记名称>
		没有属性值
	如：<title>…<title>
		 四．<标记名称属性=”属性值”>…</标记名称>
		有属性值
	如：<body bgcolor=”red”>…</body>
# 注释
	格式：
      <!—注释内容-->
	Body属性
      <body bgcolor=”背景颜色” background=”背景图像” text=”文本颜色” link=”链接文本颜色” vlink=”访问过的文本颜色” alink=”激活的连接文本颜色” leftmargin=”左边界”>
# <font>标记
	语法：<font color=”文本颜色” size=“字号”>文本</font>
# 段落标记
	|  align   | Left   | 左对齐  |
	|          | Center | 居中    |
	|          | Right  | 右对齐  |
# 总结
	以上就是我们在学习html中经常用到的语法，如果想更详细的了解html语法的话，请查看[HTML参考手册](http://www.jb51.net/w3school/tags/index.htm)。
	