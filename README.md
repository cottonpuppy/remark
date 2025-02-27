# github使用
### 上传项目
```
git init//初始化
git add README.md//可以添加其他的文件
git add .//上传全部文件
git commit -m "first commit"//备注
git branch -M main //建立新的分支
git remote add origin https://github.com/xxxx/xxx.git
git push -u origin main
```
### 分支操作和将修改后的项目提交到github
1. 本地仓库创建新的分支`git branch dev`
2. 查看分支`git branch`
3. 以当前分支为基础创建dev1分支,我们也会进入新的分支`git checkout -b dev1`
4. 切换到之前的main分支`git checkout main`
5. 删掉特定的分支`git branch -D <branchname>`
6. 名称提交代码先pull再push
```
git pull origin main
git push origin main
```
### 回滚
* 将文件从暂存区回滚到工作区
`git checkout  文件名称 `
* 将已经提交到仓库的文件回滚到工作区
```
git reset HEAD^1 
git checkout
```
### 使用浅拷贝
不需要存储库的整个历史记录
`git clone --depth 1 https://github.com/kekingcn/kkFileView.git`
