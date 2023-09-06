> # 网页显示GitHub版  docsify+ 文档（动态版）
>
> > 通过init初始化项目  在net_file文件下建立项目名称
>
> 	docsify init 项目名称
>
> ## 第一次建立GitHub
>
> > 进入路径  
>
> 	cd 项目名称
>
> > 初始化  
>
> 	git init
>
> > 添加文件(一个是全部，一个是单独)  
>
> 	git add "--all"
> 	git add 文件名
>
> > 查看状态  
>
> 	git status 
>
> > 上传文件到GitHub的位置（建议在GitHub上建立文档）  
>
> 	git commit -m "java"
>
> > 远程连接  
>
> 	git remote add origin https://github.com/ali1mumu/java.git
>
> > 上传文件  
>
> 	git push -u origin master
>
> > 上传文档时，可能出现去掉代理或者超时问题解决方法  
>
> 	//取消http代理
> 	git config --global --unset http.proxy
> 	//取消https代理 
> 	git config --global --unset https.proxy
>
> > 再重新上传文件  
>
> 	git push -u origin master
>
> > 去GitHub上setting--pages--save  
> > 最后去actions 看链接
>
> ## 更新说明
>
> > 查看状态  
>
> 	git status 
>
> > 添加修改的文件  
>
> 	git add 修改文件
>
> > 上传文件到GitHub的位置  
>
> 	git commit -m "java"
>
> > 重新上传文件  
>
> 	git push -u origin master
>

# java 学习路线

[链接]([路线特点 (yupi.icu)](https://luxian.yupi.icu/#/roadmap/Java学习路线?id=🌕-mysql-数据库（7-天）))

## MySQL 数据库

[课程链接](https://www.bilibili.com/video/BV1Vy4y1z7EX )

[笔记链接]([Document (ali1mumu.github.io)](https://ali1mumu.github.io/mysql/#/))



## 操作系统

[os课程 ](https://www.bilibili.com/video/BV1uW411f72n)

[os笔记链接]([Document (ali1mumu.github.io)](https://ali1mumu.github.io/os/#/))



## 计算机网络

[课程链接](https://www.bilibili.com/video/BV1c4411d7jb)

[计算机网络笔记链接]([Document (ali1mumu.github.io)](https://ali1mumu.github.io/comnet/#/))



# docsify+ 文档使用说明(静态版)

> 通过init初始化项目

	docsify init 项目名称

> 通过 docsify serve 命令在本地启动网站服务器，支持热加载，修改文档后自动更新，做到实时预览

	docsify serve 项目名称

> 在浏览器打开 http://localhost:XXXX 即可查看效果



# md 文档书写说明

## 标题

> 一个 # 是一级标题，二个 # 是二级标题，以此类推。支持六级标题。

## 字体

>  **颜色** 
>  \<font color=Blue>Test</font>
>  **高亮**显示（左右各两个 = ）**加粗**（左右各两个 \* ）斜体（左右各一个 \* ）  
>  ** 删除线**（左右各两个 ~ ）**斜体加粗**（左右各三个 \* ）  
>  文字超链接（\[链接名\](链接) eg:[书写标准](https://www.runoob.com/markdown/md-link.html)  
>  **表格**（|姓名|性别|）**引用**（>）

> **方程和公式** latex 格式+左右加一个 $

## 代码

> 代码前空一行，代码行前加 \tab

# jacoco安装使用

> [jaCoCo](https://zhuanlan.zhihu.com/p/363864068)
