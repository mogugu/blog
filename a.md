# git 分支操作
## 查看所有分支
git branch -a
## 创建本地库 dev分支
git branch dev
## 切换到dev 分支
git checkout dev

touch b.md 
git add .
git commit -am "add b.md"

## 推送到origin地址的dev分支上
git push origin dev
git push origin master
