具体查看链接[廖雪峰](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
---
# 基本命令汇总
* git config命令的--global参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置
* pwd命令用于显示当前目录
* vim打开
* ls
* git add <file_name>
* git commit -m "what you want to say about you file"
* cd
* git init
* git push (-u)
* git clone

## 1.基本步骤
 * 在windowx下安装git
 
 * 安装完成后，在jit bush中敲
  
    * ``$ git config --global user.name "Your Name"``

    *  ``$ git config --global user.email "email@example.com"``
   
## 2.创建版本库
 * 选择一个合适的地方，创建一个空目录
   * ``$ mkdir learngit``
   * ``$ cd learngit``
   * ``$ pwd``
 
 * 通过git init命令把这个目录变成Git可以管理的仓库
   ``git init``
 
 *`` $ git add readme.txt``

 *``$ git commit -m "-m表示你要在此处添加对文件的描述信息"``

## 3. 远程仓库
  * 创建SSH Key,第一次用的时候使用
    * 关联远程库
    
    ``*$ ssh-keygen -t rsa -C "youremail@example.com"`` 
 
 * ``$ git remote add origin git@github.com:michaelliao/learngit.git``
 * ``$ git push -u origin master``
 * ``$ git push origin master``
 

## 4.从远程库克隆 
* 最好的方式是先创建远程库，然后，从远程库克隆。首先，登陆GitHub，创建一个新的仓库，名字叫gitskills，我们勾选Initialize this repository with a README，这样GitHub会自动为我们创建一个README.md文件
* 从远程库中克隆到本地库
     
``$ git clone git@github.com:michaelliao/gitskills.git`` 

        



 
    
    
    
    
    
    


