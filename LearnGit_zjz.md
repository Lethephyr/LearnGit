# LearnGit_zjz

#### 把目录变为Git可以管理的仓库:

```cmd
$ git init //初始化Git仓库
Initialized empty Git repository in /D:/learngit/.git/
```

 目录下会有 `.git` 目录（默认隐藏可用 `ls -ah`来查看

#### 向版本库添加文件

1. 告诉Git把文件添加到仓库

```cmd
$ git add <file> 
```

执行命令后  **没有消息就是好消息**  

2. 告诉Git把文件提交到仓库

```cmd
$ git commit -m <message>
```

`message `为本次提交的说明

#### 版本问题

查看仓库当前的状态

```cmd
$ git status
```

查看上次如何修改的file

```cmd
$ git diff <file>
```





#### 上传到Github

```cmd
$ git remote add prigin URL.git
$ git push -u origin master
$ git push origin master
```

