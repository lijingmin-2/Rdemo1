#### 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
  New repository、Import repository、New gist、New organization
  新的仓库、导入库、新的依据、新的组织
#### 如何能将仓库中的html文件直接解析成页面？
  Page链接
#### 如何删除仓库？
  点击：Delete this repository
#### Bash是什么操作系统的命令
  shell的内建命令，又叫内部命令。linux系统命令
#### Pwd是什么命令？
  查询当前目录
#### Cd是什么命令？
  改变目录
#### Echo是什么命令？
  打印输出
#### 配置git用户名的命令
  git config --global user.name "youname"
#### 配置邮箱的命令
  git config --global user.email "youeamil@email.com"
#### 命令行换行方式
   git config core.autocrlf命令用来改变Git换行处理的方式，该命令需要一个独立参数。
   在Windows上，仅仅需要设置ture，例如git config --global core.autocrlf true
#### 命令行终结方式
   Ctrl+c
#### 使用命令行比GUI方式有何优势？
   对于许多管理任务来说，使用命令行比图形界面还更简单,
     一是错误提示非常详细，详细到你知道错哪了，正确的用法是什么，一来二去很快就能熟悉
     二是写自动化脚本的时候，只能用命令行啊，比如自动测试和部署脚本，无论是shell脚本还是py脚本，GUI没法用的
#### 提交到本地仓库时为什么有暂存区
   将工作区和commit仓库操作之间做了一个缓冲。即可以对代码进行版本的管理，又避免了多次琐碎的commit提交。
#### 新建代码仓库的命令
   Git init
#### git clone [url] 这个命令的作用是？
   远程仓库克隆
#### 添加指定文件到暂存区的命令
   Git add[file1][file2]
#### 删除工作区文件，并且将这次删除放入暂存区的命令
   Git rm[file1][file2]
#### 改名文件，并且将这个改名文件放入暂存区的命令
   Git mv[file1][file2]
#### 提交暂存区到仓库的命令
   Git commit-m[message]
#### 直接从工作区提交到仓库的命令
   Git commit-a -m[message]
#### 显示变更信息的命令
   Git status
#### 查看历史信息的命令
   Git log
#### Commit的意义是？
   提交当前工作空间的修改内容
#### Pull的意义是？
   是将代码从远程仓库同步至本地仓库并merge的命令
#### Push的意义是？
   push本地git至github远程仓库
