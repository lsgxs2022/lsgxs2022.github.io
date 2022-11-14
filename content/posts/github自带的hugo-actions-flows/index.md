---
title: "Github自带的hugo Actions Flows"
date: 2022-11-14T22:47:45+08:00
draft: false
featured_image: "image/冰山.jpg"
---

#### 测试github推荐的hugo actions worklows

很神奇，在username.github.io仓库的actions下采用了github推荐的hugo站点actions workflow，点击commit后在项目的根目录下新建了hugo.yml文件，新增博客文档后，git-add-commit-push 之后，显示deploy successful，使用https://username.github.io，居然可以正确的显示最新发布的文章，也就是说，什么也没有配置，直接可以发布成功，而且没有用到自己手动建立的gh-pages分支。

我很好奇，怎么实现的呢？那么多参数，不太明白具体的作用，慢慢来，会懂得^-^。
