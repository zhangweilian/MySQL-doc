# git 安装
git是一个分布式的源码管理工具
## 1.github网址的注册
注册新的github用户 并且登录
在github中建立一个仓库 repository 可以命名为myweb
## 2.git安装
```c
sudo apt-get install git;
```
## 3.git 命令的使用
### 3.1 建立一个目录
```c
mkdir github
cd github/
mkdir demo
cd demo/
```
### 3.2初始化仓库
```c
git init
```
### 3.3显示仓库信息
```c
git status
```
### 3.4在仓库中添加文件（即关注追踪这个文件）
```c
touch hello.c   (hello.c可以替换成你自己的文件名)
git add hello.c
git add . (这个命令可以把所有文件全部放进仓库去)
```
### 3.5从仓库中移除文件
```c
git rm --cached hello.c (hello.c可以替换成你自己的文件名)
```
### 3.6添加文件信息
```c
 git config --global user.name （配置用户名）
 git config --global user.email（配置用户邮箱）
 git config --global core.editor vim（配置vim编辑器）
```
### 3.7查看提交信息
```c
 git log
```
