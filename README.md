# Git学习笔记

## 一、总感想

用git打了任务中的hello的md文件，被上传搞得头疼。git需要输入很多指令来相应完成需求，而我作为初学者只能借助ai来帮我逐步完成。后面探索出来可以用vscode，上传比git bash方便太多了。



## 二、学到的Git知识

1.下载完git第一步就是录入名字和邮箱，我选择了与Github相同的个人信息，便于后续在云端上传。

2.git不能用字符（？）我在复制网址的时候才知道不能加入$符号，翻译它的警告说是git bash无法识别。

3.git bash里有很多关键词（也许是这么叫），必须符合相应的格式才可以打出指令。

像录入名字和邮箱用git，进入桌面的文件架用cd，创建文件夹用mkdir等等。但目前还没理解这些代表着什么，也不懂要记多少，不过目前看来Git的格式很严谨，与C语言类似。

4.在粘贴复制的远程仓库 HTTPS 地址的时候结尾必须是git，后续如有内容要删除。

5.关于上传文件的格式:

a:创建本地仓库并进入并初始化（git init）

b:编写文件

c:关联远程仓库，比如我写的时候用的(git remote add origin https://github.com/Technoblade1889/git-practice.git)

d:提交先添加到暂存区在搞到仓库，显示 `1 file changed, 1 insertion(+)`，则提交成功。

e：推送：git push -u origin master（注意搞清楚是main还是分支）



6.我在上传的时候总是提示我网络有问题，后面探索出可以用SSH不一定非要HTTP，只要去Github搞个密钥就可以了。



