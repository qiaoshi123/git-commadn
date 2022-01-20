# 本地不存在项目，新建项目
``` 
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:qiaoshi123/git-commadn.git
git push -u origin main

```

# 本地已存在的仓库
```
git remote add origin git@github.com:qiaoshi123/git-commadn.git
git branch -M main
git push -u origin main
```

# 常用命令集合
```
创建分支： $ git branch mybranch
切换分支： $ git checkout mybranch
创建并切换分支： $ git checkout -b mybranch

更新远程库到本地： $ git fetch origin
取远程分支合并到本地： $ git merge origin/mybranch
取远程分支并分化一个新分支mybranch2： $ git checkout -b mybranch2 origin/mybranch
推送分支： $ git push origin mybranch2

-----------
更新master主线上的东西到该分支上：$git rebase master
切换到master分支：$git checkout master
更新mybranch分支上的东西到master上：$git rebase mybranch
提交：git add -A 
     git commit -m'xxx'
-----------
删除分支： $ git branch -d mybranch
强制删除分支： $ git branch -D mybranch
列出所有分支： $ git branch
查看各个分支最后一次提交： $ git branch -v
删除远程分支：$ git push origin :mybranch
查看哪些分支合并入当前分支： $ git branch –merged
查看哪些分支未合并入当前分支： $ git branch –no-merged


