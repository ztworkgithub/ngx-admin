# ngx-admin
参考前端项目

git拉取地址：
https://github.com/akveo/ngx-admin.git
git官方地址：
https://github.com/akveo/ngx-admin
官方网址：
http://akveo.github.io/ngx-admin/
使用指南：
https://akveo.github.io/ngx-admin/docs/getting-started/installation-guidelines#install-ngxadmin


对官方项目修改之处：
https://github.com/akveo/ngx-admin/pull/5945/files/1f4008b908d0573448ee5f4afa5256999655345d
删除: package.json 中 65 行， "node-sass": "^4.14.1",


环境配置：
安装 node 14.21.3 版本
安装 angular 10.2.0 版本

下载项目所需 node_modules：
通过控制台切换到当前目录下， 使用 npm i 命令下载 node_modules

启动：
然后使用 npm start 启动项目








使用指南（复制过来的）： 防止官方使用指南打不开
安装 ngx-admin
请注意，ngx-admin只是一个前端应用程序。后端集成可以相对简单地完成，但您应该知道所有数据都是使用 JavaScript 对象模拟的。 如果您希望数据是动态的，则应考虑自己开发后端集成。 Nebular 团队不考虑提供通用集成层作为该项目的一部分，因为每个后端 API 在数据格式和 URL 方面都有不同的结构。

安装工具
要在计算机上安装 ngx-admin，您需要安装以下工具：

Git - https://git-scm.com
节点.js - https://nodejs.org。请注意，版本应为 >=8
Npm - Node.js包管理器，自带Node.js。请确保 npm 版本为 >=5
您可能还需要一些特定的本机软件包，具体取决于您的操作系统，例如在 Ubuntu 上build-essential
警告！
请注意，如果没有这些工具，就不可能构建ngx-admin，并且由于Angular的构建方式，这是不可能的。
下载代码
完成工具设置后，您需要下载 ngx-admin 应用程序的代码。最简单的方法是克隆 GitHub 存储库：

git clone https://github.com/akveo/ngx-admin.git
克隆完成后，需要安装 npm 模块：

cd ngx-admin && npm i
警告！
请确保安装过程成功完成，没有错误。
运行本地副本
要在开发模式下运行本地副本，请执行：

npm start
转到浏览器中的 http://0.0.0.0:4200 或 http://localhost:4200。
