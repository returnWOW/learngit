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

