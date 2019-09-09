# Git命令

git init :初始化git项目

git add :将本地文件 添加到暂存区

git commit :将暂存区内容 提交到 本地仓库 (本地分支，默认master分支)

git push :将本地仓库内容 推送到远程查看 (远程分支)

git pull :将远程仓库  (远程分支)的内容 拉取到 本地仓库(本地分支)

git config --global user.name "" 设置用户

git config --global user.email ""  设置邮箱

#### 第一次发布项目

git add .      : 文件-暂存区

git commit -m "注释内容"    ：暂存区-本地分支

git push -u origin master

#### 第一次下载项目

git clone 唯一标识符

#### 后期提交

git add .      : 文件-暂存区

git commit -m "注释内容"    ：暂存区-本地分支

git push  origin master

## egit

#### 第一次发布

share project

add to index  :加入到暂存区

commit   ：提交到本地分支

team -remote -push

#### 第一次下载

import -git -clone  -输入唯一标识符

## git 冲突解决

发现冲突    进入同步视图  邮件   --team -synchronized...

解决:

​		添加到本地暂存区 add to index

​		提交到本地分支 commit

​		更新服务端的分支内容 到本地分支pull

​		修改冲突 ：可直接修改/ mergr tool

​		此时已经变成了本地文件   再add to index       commit and push