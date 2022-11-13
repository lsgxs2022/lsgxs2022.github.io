---
title: "删除github分支"
date: 2022-11-10T15:18:16+08:00
draft: false
featured_image: "image/冰山.jpg"
---

#### 删除github仓库的分支

* 删除远程分支

  * git push origin `--delete` branch-name

    ![](image/git-branch-delete.png)

  * 也可以登录github账户，在branches下浏览所有分支，删除指定分支

    ![](image/github-branches.png)
  
    ![](image/github-branches-delete.png)

* 删除本地仓库分支

   git branch -d branch-name 