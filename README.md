

git 命令的使用：


仓库：
示例：从Git 版本库的初始化，通常有两种方式：
1）git clone：这是一种较为简单的初始化方式，当你已经有一个远程的Git版本库，只需要在本地克隆一份

例如：git clone git://github.com/someone/some_project.git some_project
上面的命令就是将'git://github.com/someone/some_project.git'这个URL地址的远程版本库，完全克隆到本地some_project目录下

2）git init 和 git remote：这种方式稍微复杂一些，当你本地创建了一个工作目录，你可以进入这个目录，使用'git init'命令进行初始化；Git以后就会对该目录下的文件进行版本控制，这时候如果你需要将它放到远程服务器上，可以在远程服务器上创建一个目录，并把可访问的URL记录下来，此时你就可以利用'git remote add'命令来增加一个远程服务器端，

例如：git remote add origin git://github.com/someone/another_project.git
上面的命令就会增加URL地址为'git://github.com/someone/another_project.git'，名称为origin的远程服务器，以后提交代码的时候只需要使用 origin别名即可

作者：子疯zp
链接：https://www.jianshu.com/p/d220c88bb516
來源：简书
简书著作权归作者所有，任何形式的转载都请联系作者获得授权并注明出处。


添加命令：
git add *  
git add .
git add 文件名/文件下某个文件 或者 全部文件

提交命令：
git commit -m "comment"

上传命令：
git push -u origin 分支命令


获取(拉取)命令：
git pull



大致流程是：

1、在github上创建项目

2、使用git clone https://github.com/xxxxxxx/xxxxx.git克隆到本地

3、编辑项目

4、git add . （将改动添加到暂存区）

5、git commit -m "提交说明"

6、git push origin master 将本地更改推送到远程master分支。

这样你就完成了向远程仓库的推送。


学习地址：
https://www.jianshu.com/p/d220c88bb516
提交修改的文件：
https://blog.csdn.net/yidu_fanchen/article/details/78663359
