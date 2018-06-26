### 1. 查看分支
```
charry@charrydeMacBook-Pro XiaocaiDemo$git branch -avv
* master                      c86890a [origin/master] first commit
  remotes/origin/HEAD         -> origin/master
  remotes/origin/change_theme b19d7f4 从本地checkout出来的branch
  remotes/origin/master       c86890a first commit
  remotes/origin/sunseaiot    b19d7f4 从本地checkout出来的branch

```
<<<<<<< HEAD


### 从现有的分支上检出新分支，并提交到远程
```
git status ——查看当前仓库的状态，明白当前在哪个分支上面
git branch——查看当前分支
git checkout master——切换成现有的master分支
git checkout -b dev——从已有的新分支（比如master）,创建一个dev分支
git push origin dev——提交该分支到远程仓库
```
=======
>>>>>>> feature1
