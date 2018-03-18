git就像一个仓库一样，编辑器的作用是什么。
目前已知的功能是：
1.在本电脑上创建一个文件夹当作Git的管理仓库，仅仅创建一个文件夹是不够的，应为对于你的财产，没有你的允许，Git也无法自己管理。在你创建的文件夹里输入“git init”命令就可以将你的“仓库”交给git去管理了;
2.你需要手动在仓库中添加你的文件，作为一个本地的文件，再添加之后，这个文件仍然不能被Git所管理，Git是一个很小心翼翼的人，本来就附才华于一身，又谨慎到不侵犯我们的权利。所以我们需要通过“git add filename.txt”等命令将文件交给Git;我们还需要“git commit -m ”等命令;
使用git log 查看提交的日志;
使用 git status 来查看整个Git 仓库的状态;

第一次使用Git与Github进行关联，使用“git remote add origin git@github.com:hujiaqi7777/learngit.git”。然后使用命令“git push -u origin master”将本地库的内容推送到远程库上;之后直接可以用“git push origin master”提交。
使用git branch dev创建分支，使用git checkout name切换到分支。创建+切换分支：git checkout -b <name>，使用git merge dev将当前分区与dev分支合并，然后用git branch -d dev删除分支。用git branch 查看分支 

git 还有解决冲突的任务
