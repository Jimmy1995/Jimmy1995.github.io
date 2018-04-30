---
layout: post
title: "Welcome to Jekyll!"
date: 2018-4-30 13:32:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img:  # Add image post (optional).
---
一直以来都想搭建一个自己的博客，但是一直都，所以也一直没顾得上。一次偶然在网上上看到一些博客相关的内容，参考node.js下的hexo和 ruby下的jekyll，两个都是用github pages功能的静态页面,一个是将遍以后的markdown文本转成html上传,一个是直接上传markdown文章，都有在本地搭建运行,因为想某些时候在浏览器上编辑更改,最终选择了在github上用jekyll搭建博客。

从去年开始就想搭建一个自己的博客，但是一直都没有行动，但是今天觉得自己搭个博客更加方便以后的一些笔记的记录，在朋友的帮助下最终选择了在github上用jekyll搭建博客。

#搭建过程：

在jekyll的官网上[ <http://jekyllrb.com/>](http://jekyllrb.com/) 其实已经说得比较明白了，我在这里还是简单的说一下吧。我用的是Windows系统。  

主要环节有：安装Ruby，安装RubyGems，安装jekyll，运行已有的blog项目

## 安装Ruby

ruby官网下载安装：[<https://www.ruby-lang.org/en/downloads/>](<https://www.ruby-lang.org/en/downloads/>)

安装完成后配置环境变量

在命令提示符中，得到ruby版本号 ruby -v



## 安装RubyGems

官网下载 [<http://rubygems.org/pages/download>](<http://rubygems.org/pages/download>)rubygems-2.4.5.zip

cd到RubyGems目录

执行安装 ruby setup.rb



## 用RubyGems安装jekyll

gem install jekyll



### 安装本blog依赖 的一些插件

gem install jekyll-sitemap

gem install jekyll-paginate

gem install jemoji

## 运行blog

cd 进入blog的根目录 运行windows命令行：jekyll server / jekyll server --watch