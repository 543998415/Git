# Git
什么是Git

Git的由来

分布式和集中式

Git和GitHub的使用



#### 什么是Git？

分布式版本控制工具

#### 什么是GitHub？

一个网站 ,GitHub是代码托管服务器

国内类似的网站：git.oscine.net   coding.net等等

#### Git的由来

http://www.cnblogs.com/xiaofeixiang/p/4116411.html

#### 集中式和分布式
​       集中式开发：是将项目集中存放在中央服务器中，在工作的时候，大家只在自己电脑上操作，从同一个地方下载最新版本，然后开始工作，做完的工作再提交给中央服务器保存。这种方式需要联网，现在云开发就是这样的处理方式。 

​        分布式开发：只要提供一台电脑作为版本集中存的服务器放就够了，但这个服务器的作用仅仅是用来方便“交换”大家的修改，没有它也一样干活，只是交换修改不方便而已。而每一台电脑有各自独立的开发环境，不需要联网，本地直接运行，相对集中式安全系数高很多。

#### Git和GitHub的使用

工作区->暂存区->本地分支master->远程分支master

期间 可以通过 git status 查看状态

1.添加

​	```git add ./A```  从工作区提交到缓存区

2.提交
​	```git commit -m '修改内容'```   暂存区的内容提交到本地分支
3.推送
​	```git push```  推送到自己的远程库

4.Github 通过pull request 提交代码到自己的远程库

通过pull request提交到组织的个人分支中
如果 pull request没有通过。你下次push依旧会保存在该pull request中



#### SourceTree

sourcetree是 Windows 和Mac OS X 下免费的 Git 和 Hg 客户端管理工具。其操作简单，功能强大，视图也很直观。支持创建、克隆、提交、push、pull和合并等操作。

#### 如何使用GitHub

1.注册账户以及创建仓库
要想使用github第一步当然是注册github账号了。之后就可以创建仓库了（免费用户只能建公共仓库），Create a New Repository，填好名称后Create，之后会出现一些仓库的配置信息，这也是一个git的简单教程。

2.安装客户端msysgit
github是服务端，要想在自己电脑上使用git我们还需要一个git客户端，我这里选用msysgit，这个只是提供了git的核心功能，而且是基于命令行的。如果想要图形界面的话只要在msysgit的基础上安装TortoiseGit即可。

3.配置Git

4.提交、上传

5.gitignore文件

6.tag

