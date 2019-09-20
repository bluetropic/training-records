# 科研训练计划
本项目面向刚刚入门科研的本科生或者研究生，旨在培养其基本的科研技能、普及入门科研常识。
## 1.基本科研工具
### （1）代码托管工具
主要介绍和学习git命令和github网站
- 使用git托管代码
  - git init命令新建文件
  - git status命令查看文件状态
  - touch新建文件
  - vim查看编辑文本文档 退出时可以用ZZ命令
  - ssh的连接:ssh-keygen -t rsa -C '1246677924@qq.com'
    - 密钥拷贝：cat ~/.ssh/id_rsa.pub
  - 配置远程仓库：git remote add origin 仓库地址
  - 添加文件：
      - git add 1.txt
      - git commit -m '添加描述'
  - 将文件提交GitHub库：git push -u origin master
      - 在使用git push -u origin master上提交文件时可能会出现错误error: failed to push some refs to 'https://github.com/Hicate/test1.git'
      - 解决方法：
          - git pull --rebase origin master  把远程README.md文件pull到本地
          - git push -u origin master       重新提交
    ![image](https://github.com/Hicate/training-records/blob/master/images/1.png)   
    ![image](https://github.com/Hicate/training-records/blob/master/images/2.png)  
  - GitHub中分支的合并：https://blog.csdn.net/qq_30607843/article/details/84404000
### （2）文献管理工具
主要介绍和学习JabRef和EndNote。
- JabRef:是一个开源的参考文献管理软件,用 Java 语言编写。这个需要下载安装，学习简单入门的文献管理功能。
- EndNote:简单了解，暂时不学。

### （3）论文写作和编辑工具
主要介绍和学习LaTex和流行的科技论文编辑工具Texlive + TeXstudio +JabRef
- LaTeX工具的使用
  - 具体细节可以参考ctex宏包集
    - 打开方式:cmd命令下输入texdoc ctex 
  - 运行实例：
    ![image](https://github.com/Hicate/training-records/blob/master/images/3.png) 
    ![image](https://github.com/Hicate/training-records/blob/master/images/3.png)
### （4）绘图制表等基本工具
主要介绍和学习Gnuplot,参考资料：[《使用 gnuplot 科学作图——Gnuplot 中文教程》](http://wap.sciencenet.cn/home.php?mod=attachment&id=16472)

## 2.编程语言和平台
- 熟悉Intellj IDEA编程平台。
- 熟悉Anaconda平台
- 通过简单的小项目，锻炼使用Python进行数据获取、数据处理和分析、数据挖掘、机器学习等基本技能。
## 3.学术成果
- 介绍期刊论文，会议论文，专利，软件著作权等科研成果相关的概念、背景，以及如何发表论文，申请专利和软著。

## 4.文件检索平台使用
- 了解并掌握SCI、EI检索工具，学会基本的论文检索方法。
- 了解Google scholar，DBLP，Springer，百度学术，CiteSeer，ACM DL等论文检索平台和工具。

## 5.项目基金
- 介绍科研和学术界流行的项目分类，了解如何申请这些项目，评审规则。
## 6.学者与团队，交流与合作
- 了解国内外知识图谱研究团队和学者信息。
- 积极交流与合作。
## 7.财务制度与报销流程
- 选学，不做重点要求。
