### 从远程库下载的步骤
```git
#克隆
$ git clone https://github.com/yespider/Hello_World.git

#设置用户名
$ git config --global user.name "github's Name"
$ git config --global user.email "github@xx.com"
$ git config --list
```

###修改添加文件
```git
#文件名区分大小写
$ git add readme.md
#查看工作区状态
$ git status
#提交
$ git commit -m "first commit"
```

###提交到远程库
```git
$ git push origin master
```
origin是远程库的别名，在`git  clone`的时候就创建了
可以通过`git remote`来进行一些相关操作

###本地分支创建与合并
```git
$ git chechout -b dev  //creat new branch "dev"
```