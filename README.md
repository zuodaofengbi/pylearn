# pylearn

# Git和github使用

## Git用户设置

首先在网上下载git软件并安装，一路默认安装即可(安装路径可以自己选择),然后进行本地账户设置，打开安装的git文件夹中的Git Bash端，我们所有的操作都需要使用在这个里面进行（建议添加桌面快捷方式）。

在GIT Bash中设置用户名和邮箱：

**git config --global user.name "用户名（自取）"（回车）**

**git config --global user.email "自己的邮箱"（回车）**

## 建立本地仓库

1.在路径下输入 git init

2.git add .

3.git commit -m "version"

## 远程仓库

创建

## 本地和远程连接

git remote add origin git@github.com:zuodaofengbi/pylearn.git(:后面输入自己的仓库地址+.git)

**第一次push**
git push -u origin master   

**以后可以简化**

git push
