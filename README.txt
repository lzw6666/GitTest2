git 是版本管理软件

mkdir gitTest 使用命令行创建一个文件夹

touch test.txt 创建一个文件
ls 查看文件
 git init 创建代码创库的操作
git add . 添加所有文件到库
git commit -m "提示信息"  提交

git log 查看提交的东西日志

cat test.txt 查看该文件东西

git checkout *******(有7位) 是每次修改的时的前7位   		回滚到当前时刻
   ******* 这个是你git log 出来的 commit 后面数字的前7位

git branch 查看分支的目录

git branch *** 创建新的分支

git checkout 分支名   调到当前分支

git merge 分支名   将该分支合并到主分支

git branch --delete 分支名1 分支名2  删除分支(当将子分支也主分支合并后,再将其删除)