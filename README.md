此仓库记录了我学习git的相关内容： 
主要是一些常见的git命令，和git以及github操作技巧。

## 重点写出, 方便记忆:

来自 **git快速提交Github步骤.txt**
#找到你要提交的目录下

`git init`

#添加提交的远程仓库:

码云:

`git remote add origin git@gitee.com:menglanyingfei/matlablearning.git`

github:

`git remote add origin git@github.com:menglanyingfei/matlablearning.git`

#push前先将远程repository的修改pull下来

`git pull origin master`
<br />
#作出修改, 如: 修改文件和增加文件(或者文件夹)
<br />
#将添加的提交到列表上

`git add .`

#提交你的文件, 添加消息”第一次提交”

`git commit -m 'first commit'`

#发送你的提交到GitHub

`git push origin master`

成功提交了! 哈哈!

#查看git状态

`git status`

其中, JavaWeb项目中`.gitignore`文件应添加的内容为:

*.DS_Store

*.iml

.classpath

.project

.settings

.idea

.springBeans

.checkstyle

target

bin/

logs/

src/main/webapp/WEB-INF/classes/

src/main/webapp/WEB-INF/lib/
