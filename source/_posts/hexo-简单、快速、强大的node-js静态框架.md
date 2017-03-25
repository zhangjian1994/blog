---
title: hexo--简单、快速、强大的node.js静态框架
date: 2017-03-15 21:57:48
tags: hexo
---
hexo是一款基于Node.js的静态博客框架。目前在GitHub上已有1375 star 和 219 fork。
![node](https://segmentfault.com/image?src=http://i.imgur.com/40XuB.png&objectId=1190000000370778&token=c44ffdd1cb839bc605d8386ea529233a)
# 特性
*风一般的速度
Hexo基于Node.js，支持多进程，几百篇文章也可以秒生成。
*流畅的撰写
支持GitHub Flavored Markdown和所有Octopress的插件。
*扩展性
Hexo支持EJS、Swig和Stylus。通过插件支持Haml、Jade和Less.
# 快速入门
## 安装
前提是必须先安装 Node.js，至于怎么安装自己 Google 吧
	npm install hexo -g
仅需一步就把 Hexo 本体和所有相依套件安装完毕，很简单吧？
## 升级
更新hexo到最新版
	npm update hexo -g
## 初始化
	hexo init <folder>
如果指定 <folder>，便会在目前的资料夹建立一个名为 <folder> 的新资料夹；否则会在目前资料夹初始化。
## 创建新博客
	hexo new "Hello World"
## 生成网站
	hexo generate
## 服务器
	hexo server
伺服器会跑在 http://localhost:port （port 预设为 4000，可在 _config.yml 设定），也可以搭配 Pow 使用：
	cd ~/.pow
	ln -s /path/to/myapp
基本使用差不多就是这样子，非常简单。
