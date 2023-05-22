# 学习地址
http://www.javascriptpeixun.cn/course/1428/task/70314/show

# 配置使用git仓库的人员姓名
- git config --global user.name "Your Name Comes Here"
# 配置使用git仓库的人员姓名
- git config --global user.email you@yourdomain.example.com

- git --version                           # git版本
- git init                                # 初始化仓库
- git status                              # 查看文件状态
- git add <file>                          # 将文件提交到暂存区
- git add .                               # 将所有修改过的文件提交到暂存区
- git checkout 1.txt                      # 暂存区回来覆盖工作区
- git commit -m ""                        # 提交你的修改
- git log                                 # 查看提交记录
- git reset --hard ****                   # 回退某个版本
  
- git clone git@*******                   # 相当于连接和初始化
- git remote -v                           # 查看连接信息
- git remote add origin git@*******       # 连接远程仓库
- git push origin master                  # 将本地主分支推到远程主分支
- git push                                # push所有分支
- git pull origin master                  # 拉远程主分支到本地主分支
- git pull                                # 抓取远程仓库所有分支更新合并到本地
  
# 分支操作
- git branch                              # 查看当前存在的分支
- git branch dev                          # 创建一个叫degongv的分支
- git checkout dev                        # 切换dev分支
- git checkout -b dev                     # 创建并切换到这个分支
- git merge dev                           # 合并dev分支，当前工作目录为master
- git branch -d dev                       # 删除分支
  
  
# 公钥和私钥的地址(C:\Users\Administrator\.ssh)
  - 指令:ssh-keygen -t rsa
  
# 冲突的本质:
- 同名文件中有不同的代码
- 多人协作修改了公共的代码

# 如何解决冲突?
- q退出解决冲突仓库

# 常见的几个疑问
- 刚开始本地仓和远程仓一致,如果远程仓库修改了,本地文件是否会被覆盖？本地仓库是否能更新上去?
- 刚开始本地仓和远程仓一致,如果远程仓库增加了文件，本地仓是否能更新上去?
- 刚开始本地仓和远程仓一致,如果远程仓库删除了文件，本地仓是否能更新上去?