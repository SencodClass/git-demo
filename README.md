# git-demo
git 常用操作
### 练习
#### 1.git clone 远程仓库 
git@github.com:SencodClass/git-demo.git
#### 2.git 本地创建分支并推送到远程
git checkout -b lzqsb
git push origin lzqsb
#### 3.git clone 远程仓库指定分支
git主页branch设为lzqsb 复制clone的地址
git clone git@github.com:SencodClass/git-demo.git
#### 4.git 本地创建tag 并推送到远程， 
git tag lzqab_v1.0
git tag lzqab_v1.1
#### 5.git 切换到某个tag
git checkout lzqab_v1.1
#### 6.git 实战开发
- 1.git 基于master创建dev 分支 给团队开发
git checkout master
git checkout -b dev
- 2.git 基于dev 分支 创建自己的分支开发 xxx_dev
git checkout -b xxx_dev
- 3.在自己的开发分支add some files并push 到远程
git add lzq.py
git commit -m "lzq上班"
git push -u origin xxx_dev
- 4.使用git merge 命令将自己的分支改动的内容合并到dev 分支
 git merge dev
- 5.模拟团队协作基于dev 创建一个新的个人分支xxx_dev  

