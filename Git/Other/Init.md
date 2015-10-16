### 初始化
这里记录的一些初始化Git需要用到的命令。

---
```
/*
 * 创建一个本地仓库并从远程仓库拉取代码
 */
1. $ git init  //新建仓库
2. $ git config --global user.name "xxxxx"  //设置用户名
3. $ git config --gloabl user.email "xxxxxx@xxxxx.com"  //设置邮箱地址
4. $ git remote add origin https://github.com/Felix-zky/notebook.git  //绑定远程仓库，或者说与远程仓库建立连接。
5. $ git pull origin master  //origin为上面绑定的远程仓库别名，master为远程仓库的主分支。

//此时可以任意修改代码了。修改完继续操作。

6. $ git add .  //'.'代表把所有修改都添加到索引库中。如果修改操作中含有删除文件，需要将'.'换成'-A'。
7. $ git commit -m "xxxxx"  //将修改提交到本地仓库中。
8. $ git push -u origin master  //将代码推送至远程仓库。
```