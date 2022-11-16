---
title: "在github两个仓库之间实现静态博客发布"
date: 2022-11-08T20:55:12+08:00
draft: true
---

* 首先在本地生成一对秘钥

  * ssh-keygen -t ed25519 -C "username@163.com"

  * 将公钥保存在博客静态网页文件仓库的deploy key下。

  * 将私钥保存在项目源文件的仓库secrets下。

* 编写hugo deploy的action脚本

* 编辑项目源文件根目录下的config.toml文件的发布项信息。

![](/image/云山雾绕.jpg)
