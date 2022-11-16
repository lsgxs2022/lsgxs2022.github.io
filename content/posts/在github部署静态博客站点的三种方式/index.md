---
title: "在github部署静态博客站点的三种方式"
date: 2022-11-14T08:49:58+08:00
draft: false
featured_image: "image/冰山.jpg"
---

 最近使用hexo 和hugo两种静态站点框架在github上部署博客，总结一下有三种常用的部署方式：

* 在两个不同的仓库之间使用githbu actions flow自动化部署站点
  * 一个仓库作为博客项目源文件的存储空间
  * 另外一个仓库作为博客项目生成的静态文件发布源
  * 具体的实现可以参照自己hexo博客的部署项目源文件
* 在一个仓库的两个不同分支之间部署博客站点
  * 首先要建立一个username.github.io的仓库，在main分支保存博客项目源文件。
  * 其次是在本地建立一个独立分支gh-pages，用这个分支来发布生成的静态网页文件
* 利用github基于项目的github pages服务
  * 在仓库的main分支保存博客项目源文件
  * 在项目的根目录下建立docs目录，并修改config.toml文件，在文件末尾添加publish = "docs"的数据项。github项目仓库默认使用docs作为静态站点发布源，替代了public目录的作用，可以删除public目录。
  * 也就是说在一个仓库的main分支下保存源文件，同时把项目根目录的docs目录作为静态站点发布源。
