Git is a version control system.
Git is free software.
1.你可以用命令git add告诉Git，把文件添加到仓库
2.用命令git commit告诉Git，把文件提交到仓库
$ git commit -m "wrote a readme file(提交的说明文字)"
现在总结一下今天学的两点内容：

初始化一个Git仓库，使用git init命令。

添加文件到Git仓库，分两步：

使用命令git add <file>，注意，可反复多次使用，添加多个文件；
使用命令git commit -m <message>，完成。

要随时掌握工作区的状态，使用git status命令。

如果git status告诉你有文件被修改过，用git diff可以查看修改内容。
git log 可以看到修改过的各个版本
