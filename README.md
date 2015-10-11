# NodeJS
===========

前端开发环境准备
-----------
###步骤
 进入IBM联合实验室接手的第一个项目就是前端Nodejs和d3的。第一步做的事情就是前端的环境配置。<br>
 
 1.在官网下载nodejs，安装之，并且会默认安装npm。<br>
 
 2.用npm安装grunt js和bower js。具体步骤如下：<br>
 
 安装完以后进行全局安装目录设置:<br>
 
    2.1.在安装v0.10/32版本时,如果不是采用默认安装方式,这个时候自己新建安装目录,然后把安装包放在自建的目录下安装<br>  
    2.2.在C:\Users\Administrator\AppData\Roaming\ 在这个目录建立npm文件夹<br>  
    2.3.比如我们要按2.4修改全局安装及缓存路径,我们需要手动建立文件夹,如:D:\nodejs\新建node_global文件夹,之后按2.4操作<br>  
    2.4  npm config set prefix "D:\nodejs\node_global"  //设置全局安装的路径,安装的时候会自动创建该目录 <br> 
    2.5  npm config set cache "D:\nodejs\node_cache"    //设置缓存目录,离线的时候会从该目录读取数据<br>  
    2.6  替换环境变量中系统默认的的node.js的全局路径C:XXXX为D:\nodejs\node_global加到系统PATH里面，方便在控制台直接运行<br>
    
 3.打开命令行，在项目根目录输入npm install，会安装package.json下面的项目依莱酷，安装完成后会出现node_modules目录。<br>
 
 4.上一步应该会自动运行bower install,安装定义在bower.json里面的前端依赖库，会出现component目录，如果没有出现，可以手动运行bow er install安装。<br>
  
  
 
