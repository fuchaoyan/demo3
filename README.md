# git教程
## 在本地创建项目：
1. mkdir demo 建文件
2. cd demo 进入demo
3. git init

## 在github创建repository：
- 本地与远程同步：
4. git remote add origin https://github.com/tingyoung/projectdemo1.git(链接)

## 本地提交以及推到远程：
5. touch a （新建一个文件a）
6. git add . (add 与 . 之间有空格）
7. git status  
8. git commit -asm "提交的文件备注" 
9. git push -u origin master 

##SSH  
10. cd ~/.ssh
11. ssh-keygen -t rsa -C "915314265@qq.com"
12. cat id_rsa.pub

