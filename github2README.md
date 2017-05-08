### 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
* new repository：新建仓库
* import repository:导入仓库
* new gist：代码片段
* new organization：新建组织


### 如何能将仓库中的html文件直接解析成页面？
Preview

Settings -> GitHub Pages -> Sourse -> master branch -> save -> 点击地址


### 如何删除仓库
Settings  ->  danger zone -> delete this repository

### Bash是什么操作系统的命令
Linux系统

### Pwd是什么命令
打印当前工作目录

### Cd是什么命令
改变目录

### Echo是什么命令
输出

### 配置git用户名的命令
git config  --global user.name="" 

### 配置邮箱的命令
git config  --global user.email="" 

### 命令行换行方式
/

### 命令行终结方式
Ctrl + c

### 使用命令行比GUI方式有何优势
有集体统一操作命令


### 提交到本地仓库时为什么有暂存区
缓存区对版本控制有优势

一次commit一次版本

第一步是用git add把文件添加进去，实际上就是把文件修改添加到暂存区；

第二步是用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支

### 新建代码仓库的命令
Git init

### git clone [url] 这个命令的作用是
远程克隆到本地

### 添加指定文件到暂存区的命令
git add [file1] [file2]

### 删除工作区文件，并且将这次删除放入暂存区的命令
git rm [file1] [file2]

### 改名文件，并且将这个改名文件放入暂存区的命令
git mv[file-origin] [file-renamed]

### 提交暂存区到仓库的命令
git commit -m [message]

### 直接从工作区提交到仓库的命令
git commit -a -m [message]

### 显示变更信息的命令
git status

### 查看历史信息的命令
git log

### Commit的意义是
提交信息

### Pull的意义是
将远程仓库的提交拉下到本地

### Push的意义是
将本地的提交推送到远程仓库
