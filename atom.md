# 
## atom的安装
1.wget -c 链接地址
2.sudo dpkg -i atom-amd64.deb
## atom插件的下载
activate-power-mode：动感插件 atl + ctrl + o :打开插件
vim-mode：vim模式
ex-mode：实现:w功能
monokai：高亮显示
atom-ternjs：JavaScript 自动补全
autoprefixer：给 CSS 添加适当的前缀
color-picker：选颜色
emmet：写 HTML 的神器
atom-beautify：美化代码，空格啊什么什么的
autoclose-html：HTML自动补全闭标签
file-icons: 增加许多图标,在侧边蓝文件名前面的icon,,很赞
autocomplete-modules: 自动补全插件, 有HTML, CSS, python 等
highlight-selected: 高亮当前所选的文字, 双击后全文这个词或变量都会变高亮.
Open In Browser: 右键打开浏览器.
atom-clock: 在bar显示 时间
autocomplete-js-import: 模块导入智能提示
autocomplete-modules: 模块智能提示【node_modules】
# CGI
## Apache开启CGI

需要在apache中开启cgi支持.
```c
sudo ln -s /etc/apache2/mods-available/cgi.load /etc/apache2/mods-enabled/cgi.load
```
需要重启 apache 服务器
```c
service apache2 restart
```
需要运行的cgi文件的存放路径为:
```c
/usr/lib/cgi-bin
```
改完目录的权限, 方便对目录下的文件写.
```c
sudo mkdir /usr/lib/cgi-bin/sx
sudo chmod 777 /usr/lib/cgi-bin/sx
```

## Makefile.
vim Makefile
```c
install:
	cp *.cgi /usr/lib/cgi-bin/sx
```
## 安装mysql的C语言库
```c
sudo apt-get update
sudo apt-get install libmysqlclient-dev
```
