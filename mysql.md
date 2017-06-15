# MySQL安装

## 打开源列表文件
```c
sudo vim /etc/apt/souces.list(注意vim后面要有空格)
```
## 将源列表中的东西删掉 粘贴下列的代码
```c
deb http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ xenial-security main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse
##测试版源
deb http://mirrors.aliyun.com/ubuntu/ xenial-proposed main restricted universe multiverse
# 源码
deb-src http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-security main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse
##测试版源
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-proposed main restricted universe multiverse
# Canonical 合作伙伴和附加
deb http://archive.canonical.com/ubuntu/ xenial partner
deb http://extras.ubuntu.com/ubuntu/ xenial main
```
## 安装sql语句
```c
sudo apt-get update 更新源
sudo apt-get install mysql-client mysql-server 安装mysql服务器和客户端
sudo /etc/init.d/mysqld start 启动mysql服务
```
## apache 安装
```c
sudo apt-get update
sudo apt-get install tasksel
sudo tasksel
```
# sql数据库中的各种命令
1.创建数据库
```c
create database stu;
```
2.显示数据库
```c
show databases (注意有s)
```
