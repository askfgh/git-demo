# git学习

## 基础流程

**git init** :初始化

**git status** ：查看状态

有新文件 c.txt :使用 <font color='red'>1</font> **git add** c.txt 将 c.txt 送入暂存区，可以使用 git rm --cached c.txt 将它从暂存区中删除

<font color='red'>2</font>****git commit -m "版本信息（可自己随便编写）" c.txt** 将 c 提交到本地库

**cat c.txt** :查看c的内容

**git reflog** :查看版本信息

**git log** :查看详细版本

**vim c.txt** :修改c文件，修改后要重复上述步骤 **1 2**提交到本地库

## 穿越版本

1 使用 **git reflog**查看版本信息，得到版本号

2 使用 **git reset --hard 版本号** 穿越版本

注释：实际是对指针进行操作

## git 的分支操作

 **git branch 分支名** ：创建分支

**git branch -v** ：查看分支

**git checkout 分支名** 切换分支

**git merge 分支名** ：把指定的分支合并到当前分支上

## github操作

### 创建远程仓库命名

**git remote -v** :查看当前所有远程地址别名

**git remote add** 别名 远程地址 ：创造别名

### 推送本地分支到远程仓库

git pull  git@github.com:askfgh/git-demo.git master

git push git@github.com:askfgh/git-demo.git master



1：
