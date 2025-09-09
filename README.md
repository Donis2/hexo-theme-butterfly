git remote -v # 查看当前设置的远程仓库地址

origin  https://github.com/Donis2/hexo-theme-butterfly.git (fetch)
origin  https://github.com/Donis2/hexo-theme-butterfly.git (push)
upstream        https://github.com/jerryc127/hexo-theme-butterfly.git (fetch)
upstream        https://github.com/jerryc127/hexo-theme-butterfly.git (push)

可以看见有两个远程仓库，一个是 origin，一个是 upstream。
origin是自己的仓库的别名
upstream是原作者的仓库的别名,用来以后更新
git fetch upstream  来获取原项目的更新.然后再运行别的,合并到自己仓库(暂时不知道命令)




上传命令:
git add .

git pull origin dev 

git commit -m "统计图功能没显示我再上传一次" 

git branch -M dev

git push -u origin dev
