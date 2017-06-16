# git 延伸：远程仓库
### 1.本地先建一个仓库，再添加远程仓库
```c
git remote add origin https://github.com/wangleihd/h5class.git
```
### 2.将远程仓库中的东西同步到本地
```c
git fetch origin
```
### 3.将本地仓库上的东西提交到远程仓库
```c
git push origin master
```
### 4.将远程仓库上的东西拿到本地仓库
```c
git clone url （url为远程仓库的地址）
git pull (如果远程仓库上更新了东西 需要这个操作本地仓库才会同步)
```
