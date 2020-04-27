# gitpractice
刚开始在vscode中建立了一个文件，进行了init.add.commit操作之后，
利用git remote add origin + 远程仓库地址 //链接远程仓库，创建主分支，
利用git pull origin master // 把本地仓库的变化连接到远程仓库主分支，但是报错了（ refusing to merge unrelated histories）
解决方法：git pull origin master --allow-unrelated-histories
然后再正常进行下一步： git push -u origin master //把本地仓库的文件推送到远程仓库
