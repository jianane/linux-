# linux_ops
[git服务器搭建](https://www.centos.bz/2018/01/%E5%9C%A8%E9%98%BF%E9%87%8C%E4%BA%91%E7%9A%84centos%E4%B8%8A%E6%90%AD%E5%BB%BAgit%E6%9C%8D%E5%8A%A1%E5%99%A8/)

### git 错误 fatal: This operation must be run in a work tree  
由于git init –bare 方法创建一个裸仓库，在该仓库无法进行任何git操作，所以抛出错误.
解决方法：在该仓库目录下，新建文件夹，进入该文件夹，执行如下命令：
1. touch Readme
2. git init
3. git add Readme
4. git commit -m 'initial commit' Readme

### my npm account
mystic_
https://www.jianshu.com/p/901f94c44191
