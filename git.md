# GIT基本用法
## 1.GIT基本配置
**查看基本配置**  
git config --list 查看已经配置的GIT参数。  
**配置用户名及邮箱**    
git config --global user.name "xxx"  
git config --global user.email "xxx@qq.com"  
注： 三个级别保存位置 --system(所有用户) --global(当前用户) --local(当前目录)  

## 2.初始化GIT仓库  
git init 初始化当前目录  

## 3.从远程获得GIT仓库  
git clone https://github.com/zjg1979/ITL

## 4.提交更新 
git status  
git add readme.md 或者 git add .  
git diff    
git commit -a  
git push  
注：commit <-- stage <-- modify  


## 5.提交历史查看
git log --stat  

## 6.舍弃本地代码，重新远程拉取
git fetch --all  
git reset --hard origin/master  
git fetch

## 7.保留本地更改，终止合并，重新合并，重新拉取
git merge --abort
git reset --merge
git pull




