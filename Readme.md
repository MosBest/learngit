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
  
    * ``$ git config --global user.name "github用户名"``

    *  ``$ git config --global user.email "github邮箱"``
    
    *  ``$ ssh-keygen -t rsa -C "github邮箱"   //生成ssh key"``
    
    一直按回车，直到结束
    
    *  在上面输出内容中可以找到id_rsa.pub的路径,打开id_rsa.pub(打开记事本直接拖入),全文复制
    
    * 打开网页github，现则settings / ssh and GPG keys
    
        title ：随便起

        key：将刚刚从id_rsa.pub 复制得内容完全粘贴
    
    * 测试git 是否连接成功github
        
        ssh git@github.com
       
        若出现 Hi MosBest! You've successfully authenticated, but GitHub does not provide shell access.表明连接成功
    
    
    
  

## 4.从远程库克隆 
* 最好的方式是先创建远程库，然后，从远程库克隆。首先，登陆GitHub，创建一个新的仓库，名字叫gitskills，我们勾选Initialize this repository with a README，这样GitHub会自动为我们创建一个README.md文件
* 从远程库中克隆到本地库
     
* ``$ git clone git@github.com:michaelliao/gitskills.git`` 

* `` $ git add readme.txt``

* ``$ git commit -m "-m表示你要在此处添加对文件的描述信息"``

* 第一次用 ``$ git push -u origin master`` ， 以后用``$ git push origin master``      

*  可能还要有``$ git remote add origin git@github.com:michaelliao/learngit.git``

 
    
    
    
    
    
    


