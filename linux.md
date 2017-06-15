# linux 安装
## linux环境的创建
## 1.vim的安装
```c
sudo apt-get install vim
```
## 2.vim的基本命令使用
* i：在当前字符的左边插入
* I：在当前行首插入
* a：在当前字符的右边插入
* A：在当前行尾插入
* o：在当前行下面插入一个新行
* O：在当前行上面插入一个新
* h: 向前移动一个字符
* j: 向上移动一行
* k: 向下移动一行
* l: 向后移动一个字符
* yy: 复制当前一行
* dd:删除当前一行
* p: 粘贴内容到游标之后
* P: 粘贴内容到游标之前
## 3.文件操作
```
touch  file (创建文件)
cp file file1(复制文件)
cp file  /home/linux/file1
mv file   file2（移动文件）
mv file  /home/linux/
ls -al  .（列出列表）
cat  file（显示文件信息）
```
## 4.目录操作
```c
mkdir dir     (创建目录)
cp dir   dir1  -a
cp dir   /home/linux/dir2  -a
mv dir  dir2
mv dir  /home/linux/ （移动目录）
rm  dir  -rf （删除目录）
ls -d  dir   （列出目录列表）
find  ./dir  -name  "filename"（目录中查找文件）
```
## 5.对文件解压缩
```c
tar xvf  file.tar.gz
```
