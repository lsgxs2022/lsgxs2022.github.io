#### hugo 笔记



* 从github克隆一个仓库
* 在本地仅仅执行hugo new site quickstart ，不用git init ，利用github克隆下来的仓库git版本控制
* 把生成的hugo  项目源文件增加到刚下载的仓库，覆盖提示的文件复制
* git  submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git  themes/ananke
* 在config.toml文件最后增加:theme = "ananke"
* 添加hugo文档
* hugo server -D
* http://localhost:1313









