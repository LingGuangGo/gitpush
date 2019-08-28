# git 使用

## 建立新项目

```
$ git clone	https://github.com/LingGuangGo/helloword.git	// lcone项目资源
$ git status	// 查看当前目录下文件的状态	
$ git add -A	// 提交当前目录下的所有文件，和改变的日志
$ git commit -m "first git push"	// commit提交， “log”
$ git push -u origin master 		// push 上传
```

## 更新和合并

```
git fetch		// 下拉改变的文件
git merge		// 和本地文件进行合并

git pull		// 一般不使用，会覆盖本地文件
```

## 建立分支

```
git branch dev		// 建立一个目录分支
git checkout dev	// 切换到dev目录

push的时候注意更改目录
```

