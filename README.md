# 2018-11-13-1
# 作业1
## git与gitup的区别
git与gitup是不同的概念，总的来说git是一个版本管理工具，gitup是一个用做版本控制的项目托管平台。
（1）.git是一个版本控制工具，也可以理解为一个应用软件，是一个开源的分布式版本控制系统，可以在电脑不联网的情况下只在本地使用的一个版本管理工具，用以有效，高速的处理各种规模的项目版本管理。它是Linux的一个开放源码的版本控制软件，作用就是可以可以让你更好的管理你的程序。比如你原来提交的内容可以修改，可以通过git这个工具把你原来的内容呈现出来。
（2）.gitup是一个网站，可以托管各种git库，并提供一个Web界面，但与其他像SourceForge或GoogleCode这样的服务不同，gitup的独特卖点在于从另一个项目进行分支的简易型。非常适合程序员交流，很多国际的技术大神都在gitup上有自己的开源代码，其他人只要申请个账号就可以看到这些大神写的程序。国内很多互联网公司如百度阿里等也在gitup上公布有开源的代码。
# 作业2
## 课上流程
1. 创建仓库
  可以直接点击右上角的+符号，选择new respository，写上库的名字，若显示√，则说明名称可用；进行库的描述，选public，和下面的创建markdown文档，点击create，直接进入仓库，可以在线编辑，上传文件等。
  > 在线编辑：点击create new file（右上角），写新建文档的名字，备注，点击commit new file。
  >上传文件：点击upload files →choose your files→备注→commit
  
2. 本地创建文件并和仓库建立联系
  在本地的某个文件中新建一个文件，右键git bash，然后在界面中打印git+空格+clone+空格，在仓库中找到clone or download，点击后复制路径，回到刚刚的界面，右键，paste，回车，此时打开新建文件发现有仓库中的文件，说明已经建立了联系。
3. 本地的文档修改后，让仓库同步？
  首先，本地的文档被修改，回到修改的文档的上一级文件夹，点击右键，git GUI，双击左上的图标移动到左下，在右下备注，点击commit，备注内容不见后，点击push→push→close，回到仓库同步完成。
4. 仓库的内容修改后让本地同步？
仓库中的内容修改后，在本地找到相应文档的上一级文件夹，右键git GUI，点击remote→fetch；点击merge→local merge→merge，本地同步完成。

> 流程：工作区→暂存区→本地仓库→远程仓库；工作区的内容在暂存区中经过commit到本地仓库中，经过push到远程仓库；反过来，远程仓库经过fetch到本地仓库，再经过merge到工作区，从而仓库和本地联系。


 
