# Github

## Github命令

- 别名

	```
		git config --global alias.ci commit
	```
	
- 下载Github项目

	```
		git clone [url]
	```
	
- 查看本地操作状态

	```
		git status
	```

- 添加文件到暂存区

	```
		git add [file]
		git add . [添加所有文件至暂存区]
	```

- 从暂存区提交至本地仓库

	```
		git commit -m "注释"
	```

- 撤销本地提交

	```
		git reset HEAD
	```

- 查看远程Github的本地映射

	```
		git remote -v
	```
	
- 查看log

	```
		git log --oneline
	```
- 获取服务器最新的版本文件

	```
		git pull origin master
	```
	
- 提交本地文件至服务器

	```
		git push origin master
	```

## Git协议

- 本地协议

	 ```	 	
	 	git clone /c/md/test.git
		
	 ```
	 
	 ```
	 	git clone file:///c/wd/test.git
	 ```
	 
	 
	 
