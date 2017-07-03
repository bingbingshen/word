一.git常用命令：
1.ls -a  查看当前文件下所有的文件
2.git init  初始化本地Git仓储，会在当前文件夹中创建一个.git文件夹，用于记录所有的项目变更信息
            初始化本地Git仓储，会在当前文件夹中创建一个.git文件夹，用于记录所有的项目变更信息
3.ls -a 重新查看一下
4.git status查看本地仓储的状态，初次查看时显示未被跟踪的文件
5.创建.gitignore忽略文件
	在当前目录中创建git忽略文件.gitignore,并指定忽略文件，每行写一个

6.git add 文件路径
添加文件到跟踪列表中去
git add . 或者是 git  add --all把剩下的都交给git管理

7.git commit -m 提交日志
	将当前文件提交到本地仓储中，需要指定提交日志（消息）

8.git diff对比版本库中状态和当前状态的变化
9.git log查看提交日志


10.git reset --hard 版本前6位 返回到哪一个版本

与github连用
1.为本地仓储添加远端（服务器端）地址，git remote add origin https://github.com/chenjinyan11/wbs17042.git
2.查看地址的名称：git remote －v
3.将项目推送上去 git push -u origin master

git clone 远端的仓储地址


分支
git branch		#查看所有的分支
git branch 分支名	#创建分支
git checkout 分支名	#切换到指定分支
git push –u origin 分支名 #推送到远端指定的分支

gh-pages分支
访问地址：https://账户ID.github.io/仓库名/

master分支
1.创建：账户ID.github.io或者账户ID.github.com
2.将项目推送到该仓储到master的分支上
访问地址： https://账户ID.github.io/ 

MarkDown 
插件：Markdown Editing可以高亮显示
	MarkDown Preview 
	为浏览器绑定快捷键

{
	"keys":["alt+f11"],"command":"markdown_preview","args":{"target":"browser"}
}







