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