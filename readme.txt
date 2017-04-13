Git is a distributed version control system
Git is free aaaaa software distributed under the GPL
Git has a mutable index called stage
Git tracks changes of files
Creating a new branch is quick and simple

我又加了一行 删除上一行 add a line
来测试 在dev分支上修改(master 上不更改)  会完全覆盖master

不论是在 master 还是 dev 分支上增删改查，在哪条分支上执行 git commit 命令，哪条分支才会保存下修改

分支管理策略

git merge --no-ff -m "merge with no-ff" dev
本次合并创建了一个新的 commit 所以加上了 -m 参数 把描述写进去
这也是为什么禁止 Fast forward 模式 能从分支历史上看到分支信息
不使用 --no-ff 参数
