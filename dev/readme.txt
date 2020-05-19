# 创建分支并转到
git checkout -b dev
# or
git branch dev
git checkout dev

# switch to a branch
# 转到对应分支
git checkout branch_Name

# delete a branch
# 删除分支
git branch -d dev

# list all branch
# 列出所有分支
git branch

# 普通方式合并（--no-ff）
git merge --no-ff -m "merge with no ff" dev

