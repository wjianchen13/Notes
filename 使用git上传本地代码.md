使用git上传本地代码
1.首先在github上创建一个空的仓库，AndroidIndex
2.创建文件夹
3.进入该文件夹，建立git仓库：git init
4.添加需要上传的文件到文件夹，查看最新状态，显示红色：git status
5.添加文件到仓库
git add + 需要添加的文件名
git add --all 添加所有文件
使用git status，添加的文件变成绿色
6.提交到仓库 git commit -m "描述"
7.关键github仓库
git remote add origin https://github.com/wjianchen13/AndroidIndex.git
git push -u origin master 
8.使用命令行输入账号密码，要一次性输入正确，不能输错之后按删除重新输入

git remote基本的用法
git remote 不带参数 列出已经存在的远程分支
git remote -v |--verbose 列出详细信息 在每一个名字后面列出其远程的url
git remote add url 添加一个远程仓库
git push - u使用
git push -u origin master将本地的分支推送到origin主机 同时指定origin为默认主机 以后就可以不加任何参数使用git push






 