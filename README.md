# SGit
快速使用git项目讲解文档

###查看git版本
>git --vertsion


###配置git登录
> git config --global user.name "Your Name"  
> git config --global user.email "email@example.com" 


###查看当前用户信息
>git config --list

###建立本地git仓库
#####1创建本地仓库文件夹
#####2进行git本地初始化仓库操作
>git init
####3 将本地仓库加入缓存
>git add .
####4 书写提交信息注释详情
>git commit -m "添加项目"
####5 提交代码到github上（个人一般为主分支）
>git push origin master


###拓展信息
>git pull github/xxxxxx/xxxxxxx.git
