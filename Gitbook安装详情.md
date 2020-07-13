# 安装gitbook

$ rm -rf .git/
取消对文件夹 git init 初始化操作


$ sudo npm install gitbook-cli -g
报错 ➜ npm WARN checkPermissions Missing write access to /usr/local/lib/node_modules
搜索『报错信息』 ➜ 解决方案: 加sudo

在Documents指定的gitbook的文件夹
这里 ~/Documents/gitboo

1. `gitbook init` 初始化书籍目录
README.md 和 SUMMARY.md 是两个必须文件, README.md 是对书籍的简单介绍, SUMMARY.md 是书籍的目录结构

2. `gitbook serve` 编译和预览书籍
注: `gitbook serve` 命令实际上会首先调用 gitbook build 编译书籍，完成以后会打开一个 web 服务器，监听在本地的 4000 端口