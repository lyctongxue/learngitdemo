[Bug分支管理---廖雪峰](https://www.liaoxuefeng.com/wiki/896043488029600/900388704535136#0)

#### 学习Git的使用--Bug的分支管理

Q：当需要修复BUG，但是在dev分支上开发的工作还未提交，这个时候我们该如何解决？

```git
$ git status
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)
        modified:   "test.md"
no changes added to commit (use "git add" and/or "git commit -a")	
	
```

A：因为dev环境也是从master环境复制而来，并且dev环境下已经进行了开发，所以我们需要切换到master环境进行BUG修复。但是dev环境的修改的代码目前还不能提交











