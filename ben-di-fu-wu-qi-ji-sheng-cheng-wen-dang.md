# 安装node.js 及 Gitbook

***

从网盘获取：[node.js安装包](http://pan.baidu.com/s/1slBGlw5)
中文网获取：[node.js中文网](http://nodejs.cn/download/)

#### 下载后一路安装即可，安装成功后使用如下命令下载安装Gitbook

    npm install gitbook-cli -g

#### 安装成功后可以使用 gitbook -V 查看当前版本

    C:\Users\dragon>gitbook -V
    CLI version: 2.3.2
    GitBook version: 3.2.2

#### gitbook常用命令如下

    gitbook init //初始化目录文件
    gitbook help //列出gitbook所有的命令
    gitbook --help //输出gitbook-cli的帮助信息
    gitbook serve //运行本地服务器，编写时可以使用本命令查看生成的静态网页的效果
    gitbook build //生成静态网页 生成后文件在当前书籍目录下的_book文件夹中
    gitbook build --gitbook=2.6.7 //指定gitbook的版本，如果本地没有指定的版本，系统会自动下载并生成静态网页
    gitbook ls //列出本地所有的gitbook版本
    gitbook ls-remote //列出远程可用的gitbook版本
    gitbook update //更新到gitbook的最新版本
    gitbook uninstall 2.0.1 //卸载对应的gitbook版本
    gitbook build --log=debug //指定log的级别
    gitbook builid --debug //输出错误信息
    
    
    