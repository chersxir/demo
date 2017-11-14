**参考简书**[http://www.jianshu.com/p/662d9bb9cadc](http://www.jianshu.com/p/662d9bb9cadc "git for windows")  

----------
**指令操作**

`ssh -T git@github.com` 链接服务器

`git clone git@github.com:chersxir/demo.git`   下载master下资源

`git remote add origin git@github.com:chersxir/demo.git`  获取本地没有的资源

`git fetch origin`   获取到本地缓存中

`git merge origin/master` 和当前分支合并


`git push origin master` 将本地上传到服务器中

	
`git pull origin master --allow-unrelated-histories` 	本地仓库改变需要这样下载
 
`git clone xxx.git "指定目录"` 				克隆指定目录
`git commit -m "first commit"`提交缓存到仓库
`git status` 查看当前缓存状态   
`git config --list`显示当前的配置信息    
`git init`初始化一个本地仓库         
`git add xxx  `增加文件到缓存  
`git config --global user.name "yourname"` 配置名字 
`git config --global user.email "youremail"`配置邮箱    
 
配置ssh密钥     

    cd ~/.ssh   
    ssh-keygen -C "XX@gmail.com" -t rsa     
`git checkout master`  转移分支 
`git push origin --delete new_task_A`删除远程分支  
    
`git branch -a`显示所有分支   
2017/11/13 23:53:27 
    
    