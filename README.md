# ZZY
ZZY学习报告
# 第N周学习报告  



`@Author 赵芝因`  



`@Date 20200229`  



[学习内容1](#1) | [学习内容2](#2) | [学习内容3](#3) | [学习内容4](#4) | [学习内容5](#5) | [学习内容6](#6) | [学习内容7](#7) | [学习内容8](#8)











# <a id='1'>学习内容1</a>



## 了解github



学习github目的： 借助github托管项目代码



学习一些基本概念 ： 



仓库（Repository）



仓库用来存放项目代码，每个项目对应一个仓库



收藏（Star）



收藏项目，方便查看



复制克隆项目（Fork）(fork项目独立存在) 



复制他人的项目



发起请求（Pull reques）



fork他人的仓库可添加修改文件pull request后原仓库主任感觉不错->合并到原仓库



关注（Watch）



关注项目，当项目更新可以接收到通知



事务卡片（Issue）



发现代码BUG，但是目前没有成型代码，需要讨论时用



Github主页 仓库主页 个人主页







# <a id='2'>学习内容2</a>



## 学习github仓库相关操作



### 创建仓库 



1.star a project 进入创建仓库；



2.repository name 仓库名称；



3.descrition optional 项目描述；



4.initialize this repository with a README; 在仓库下多一个README文件说明项目；



5.craete repository; 创建完成；



### 仓库管理



新建文件 仓库主页，点击【create new file】创建仓库文件



编辑文件 仓库主页，点击【需要修改的文件】进入文件详情页



删除文件 （可点击commits按钮查看删除文件信息）



上传文件  点击【Upload files】上传文件或拖动到区域



搜索仓库文件 快捷键（t）



下载/检出项目 Download ZIP



### Github Issues



作用：发现代码BUG，但是目前没有成型代码，需要讨论时用；或者使用开源项目出现问题时使用 



情景：张三发现李四开源git库，则发提交了一个issue；李四隔天登录在github主页看到通知并和张三交流，最后关闭issue







# <a id='3'>学习内容3</a>



## 了解git



通过git管理github托管项目代码



## 下载安装 



1、GIt官网下载：https://www.git-scm.com/download/win



2、双击安装



3、选择安装的工作目录



4、选择组件



5、开始菜单目录名设置



6、选择使用命令行环境



7、以下三步默认，直接点击next



8、等待安装



9、 检验是否安装成功







# <a id='4'>学习内容4</a>



## git基本工作流程



git工作区域



Git Repository（git仓库）最终确定文件保存到仓库，成为一个新的版本，并且对他人可见



暂存区 暂存已经修改的文件最后统一提交道git仓库中



工作区（Working Directory）添加、编辑、修改文件等动作



向仓库中添加文件流程



1、git status + git add+文件名 -----从工作区到暂存区



2、git status + commit -m +文件提交描述 ----从暂存区到仓库



3、git status + 添加文件







# <a id='5'>学习内容5</a>



## Git初始化及仓库创建和操作



### 基本信息设置



1. 设置用户名



git config --global user.name 'itcastphpgit1'



2. 设置用户名邮箱



git config --global user.email '485434609@qq.com'



（该设置在github仓库主页显示谁提交了该文件）



### 初始化一个新的Git仓库



1、创建文件夹



2、在文件内初始化git（创建git仓库）



cd test



git init （创建隐藏文件存储仓库信息）



### 向仓库添加文件



touch a1.php                         # 创建a1.php文件到工作目录



git adda1.php                      # 添加a1.php到暂存区



git commit -m  '文件描述'     # 添加a1.php到仓库



### 修改仓库文件



vi(m) a1.php



git status + git add 从工作区到暂存区；



git commit -m +‘文件描述’ 从暂存区到仓库；



git status + 添加文件；



### 删除仓库文件



rm -rf a1.php



git rm a1.php



git commit -m‘文件描述’







# <a id='6'>学习内容6</a>



## Git管理远程仓库



### 使用远程仓库的目的



作用：备份，实现代码共享集中化管理



## Git克隆操作       



### 目的



将远程仓库（github对应的项目）复制到本地



gitclone 仓库地址



将本地仓库同步到git远程仓库中



git push







# <a id='7'>学习内容7</a>



## GithubPages 搭建网站



### 个人站点



访问



https://用户名.github.io 



 



### 搭建步骤



（1）创建个人站点   ->  新建仓库（注：仓库名必须是【用户名.github.io】）



（2）在仓库下新建index.html的文件即可



注：



1、github pages仅支持静态网页



2、仓库里面是.html文件



3、个人主页也可以设置主题







# <a id='8'>学习内容8</a>



## ProjectPages 项目站点



访问



https://用户名.github.io/仓库名  



原理



gh-pages 用于构建和发布



搭建步骤



1、进入项目主页，点击settings



2、在settings页面，点击【Launch automatic page generator 】来自动生成主题页面



3、新建站点基础信息设置



4、选择主题



5、生成网页
