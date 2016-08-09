添加文件：git add <name>

提交文件：git commit -m "此次添加备注"

查看工作区状态：git status

查看被修改文件: git diff

查看历史记录：git log (--pretty=oneline 精简显示）

回退版本：git reset -hard HEAD^ (上上HEAD^^或HEAD~3）

查看历史命令：git reflog

前进版本：git reset -hard <版本号>

查看文件：cat <name>

工作区撤销修改：git checkout -- <name>

暂存区撤销修改：git reset HEAD <name>

删除文件：git rm <name>

推送文件到远程库：git push origin master

远程库克隆文件：git clone <name>

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>