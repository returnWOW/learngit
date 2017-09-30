Git is a distribution version control system.
Git is free software.
Git has a mutable index called stage.
Git tracks changes.
Git tracks changes of files.
Creating a new branch is quick.

Git
Git init
Git add xxx
Git commit -m "xxx"
Git status
Git log
Git diff xxx xxx  HEAD xxx

Git checkout  -- xxx --意思是指明后边是文件，不是命令
Git reset HEAD xxx  退回暂存区stage的内容
#版本回退 
Git reset --hard HEAD^  HEAD^^ HEAD~100
Git reset --hard commit_id
Git reflog
Git rm xxx

ssh-keygen -t rsa -C "xxx@mail.com"
Git remote add origin git@github.com:path/repo_name.git
Git push -u origin master

#分支管理
git branch dev
git checkout dev
git checkout -b dev
git branch  #查看分支情况
git merge dev #合并指定分支到当前分支。Fast-forward是一种合并方式（快进）
git branch -d dev #删除分支
#小结：
Git鼓励大量使用分支：
查看分支：git branch
创建分支：git branch <name>
切换分支：git checkout <name>
创建+切换分支：git checkout -b <name>
合并某分支到当前分支：git merge <name>
删除分支：git branch -d <name>

Creating a new branch is quick AND simple.