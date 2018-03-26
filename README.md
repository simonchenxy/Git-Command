# Git Command Notes

###### git init 初始化一个git的项目

###### git add <file>   添加文件到缓存区
###### git add .    添加文件到缓存区，包括新文件和修改过的文件，但不包括被删除的文件
###### git add -U   添加已经add过的文件，不会添加新文件
###### git add -A   添加所有的文件到缓存区 类似于 -U 和 . 的合集
###### git add --all    等同于git add -A

###### git commit   提交文件
###### git commit -m "comments" 提交文件并赋予解释说明
###### git commit -a -m "comments"  先add再提交文件并赋予解释说明（-a不会提交新文件）

###### git branch   查看分支
###### git branch -r    查看远程分支
###### git branch -a    查看所有分支
###### git branch -d    删除合并之后的分支（未合并分支会提示不可删除，使用-D可删除）
###### git branch -D    强行删除分支

###### git checkout <path/fileName> 回退到最近的一次版本

###### git fetch    检查远程分支是否有修改
###### git fetch -p 检查并删除远程服务器不存在的分支（类似于同步远程服务器的分支列表）

###### git reset    回滚了「单独一个提交」，并移除后面的提交

###### git revert <commit>  回滚了「单独一个提交」，它没有移除后面的提交，然后回到项目之前的状态

###### git pull 本地与服务器端同步
###### git push 将本地分支推送到服务器上去。

###### git checkout <branch name>   跳转本地分支或拉取本地不存在的分支
###### git checkout <brnach name> -f 强制跳转分支（会丢失之前分支的修改内容）

###### git stash 暂存分支
