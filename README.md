# Github-Pages-Practice
版本查询： 	  	 	git --version

名字邮箱设定： 		git config --global user.name " "
					git config --global user.email " "

目录加git功能： 	git init

检查状态：      	git status

加入commit:    	 	git add <filename>
					git commit -m "更新说明"
				
显示差异：			git diff

git加GitHub账号：	git congif --global user.username " "

检查Github账号：	git congif --global user.username

增加链接：			git remote add origin <URL>

修改链接：  		git remote set-url origin <URL>

查看链接地址：		git remote -v

上传：				git push origin master

更新（下载）：		git pull <REMOTENAME> <BRANCHNAME>

切换目录：          cd

克隆项目：      	git clone <URL>

连接到fork原始项目：git remote add upstream <URL>

新建分支：			git branch <BRANCHNAME> 

新建并进入分支：	git checkout -b <BRANCHNAME>

进入分支：			git checkout <BRANCHNAME>

显示分支：			git branch

重命名当前分支：	git branch -m <NEWBRANCHNAME>

检查状态：      	git status

更新之前检查变化：  git fetch --dry-run

合并一个分支到当前：git merge <BRANCHNAME>

删除分支：  （本地）git branch -d <BRANCHNAME>
		   （GitHub)git push <REMOTENAME> --delete <BRANCHNAME>
