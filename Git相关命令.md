# Git相关命令

1.git init	把当前目录变成Git可以管理的仓库

2.git add <文件名>	将当前文件加入仓库中

3.git commit -m "<注释>"	提交文件到仓库

4.git branch <分支名>	建立分支

5.git checkout <分支名>	跳转至分支

6.git checkout main	切回主分支

7.git checkout -- <文件名>	撤销修改（未放置暂存区的变回版本库状态，已添加至暂存区的变回初入暂存区状态）

8.git status	展示当前仓库状态

9.git diff <文件名>	展示文件哪些地方发生了修改

10.git diff HEAD -- <文件名>	查看工作区与最新版本区别

11.git log	展示文件历代提交的版本及注释

   git log --pretty=oneline	只展示版本号及注释

12.git reset --hard HEDA^（或版本号前几位（数字及字母组合））	回退至上一次版本

13.git reset HEAD <文件名>	把暂存区的修改撤销，放回工作区

14.git reflog	展示每一次的命令

15.git rm <文件名>	删除文件

16.git merge <分支名>;<分支名>	合并两个分支

17.git rebase <分支路径>	取出一系列提交记录并复制，在其他地方逐个放下