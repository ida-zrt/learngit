Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.

# 将工作目录下的文件添加至缓存库
git add

# 将缓存库推送至当前分支
git commit

# 查看版本历史
git log
git reflog

# 将工作区文件回退至对应版本
git reset --hard

# 查看当前工作区，缓存库，分支的状态
git status

# 在add file之前恢复文档
# 实则为使用版本库中的文件恢复至工作目录
git checkout -- <file>
# or
git restore <file>

 # remove file 从版本库中移除文件
git rm <file>


# 关联远程库，使用命令
git remote add origin git@server-name:path/repo-name.git

# 首次推送所有内容，采用
git push -u origin master

# 之后的提交，采用
git push origin master

