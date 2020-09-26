#创建一个版本库
`$ mkdir learngit`(文件名)  
`$ cd learngit`  
`$ pwd`  
路径  

`$ git init`  
`git add (file)`可重复使用  
`git commit -m (message)`

#查看文件内容
`cat 文件名.格式`


#修改后的查看  
`git status`可以让我们掌握仓库当前状态  
`git diff 文件名`即查看difference 

#提交到仓库
`git add 文件名.格式`   
`git commit -m "add 改动部分"`  


#查看改动的历史记录
`git log`  
`git log --pretty=oneline`
###退回某一版本  
`git reset --hard HEAD^`往上一百个版本就是HEAD~100  
`git reset --hard 文件序号前几位`回到某一版本  
`git reflog`记录每一次命令



