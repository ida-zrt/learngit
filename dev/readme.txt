# 创建分支并转到
git checkout -b dev
# or
git branch dev
git checkout dev

# switch to a branch
# 转到对应分支
git checkout branch_Name
git switch branch_Name

# delete a branch
# 删除分支
git branch -d dev

# list all branch
# 列出所有分支
git branch

# 转到新的分支（不能是已有的分支）
git switch -c dev2

# 普通方式合并（--no-ff）
git merge --no-ff -m "merge with no ff" dev
