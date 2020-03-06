## 查看本地分支与远程分支的对应关系
```
git branch -vv //查看设置的所有跟踪分支
git branch -v -a //显示当前使用仓库的所有分支
git remote show origin //查看本地分支与远程分支的对应关系
```
## 基于远程分支创建新分支
### 分支名与远程分支一致
```
git checkout --track origin/branch_name
```
### 分支名与远程分支不一致
```
git checkout -b new_branch_name branch_name
```
## 基于本地分支创建远程分支
```
git push --set-upstream origin branch_name
```
