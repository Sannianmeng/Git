Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.
Git tracks changes of files.


 git add readmes.txt --->将修改的文件存进暂存区；
 git commit-m "readmes" --->将暂存区的文件提交
 cat readmes.txt ----->查看文件的内容；
 git status ------>查看文件的状态（是在暂存区还是未在暂存区或者提交了）
 git checkout -- readme.txt ----->放弃工作区的内容修改；

命令git checkout -- readme.txt意思就是，把readme.txt文件在工作区的修改全部撤销，这里有两种情况：

一种是readme.txt自修改后还没有被放到暂存区，现在，撤销修改就回到和版本库一模一样的状态；

一种是readme.txt已经添加到暂存区后，又作了修改，现在，撤销修改就回到添加到暂存区后的状态。

总之，就是让这个文件回到最近一次git commit或git add时的状态

git checkout -- file命令中的--很重要，没有--，就变成了“切换到另一个分支”的命令，我们在后面的分支管理中会再次遇到git checkout命令。


