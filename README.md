# Introduction-to-Git-and-Github
## Instal
参考https://git-scm.com/download/mac中的方法，或直接在命令行输入"xcode-select --install"
接着设置用户名和邮箱：
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
使用一下命令确认用户名已正确设置：
$ git config --global user.name
> Your Name
## Github创建仓库
首先在官网注册账号：https://github.com/
接着创建自己的仓库(repository): https://docs.github.com/zh/get-started/quickstart/create-a-repo
为了保存进度，我们在可以利用branch来保存各个阶段的更新：
在上方小箭头处下拉，可从当前分支搜索或创建新分支。对内容进行更改后，在"Pull requests"处点击绿色按钮"new pull request".
Comfirm merge后删除此分支。
## 连接Git和Github
![image](https://user-images.githubusercontent.com/121569054/209863485-3030079d-c5af-43e2-8b69-742a9f69280f.png)
Workspace：工作区
Index / Stage：暂存区
Repository：仓库区（或本地仓库）
Remote：远程仓库

首先把Github伤的仓库克隆到本地：git clone SSH
（SSH从“code”下拉可复制）
每次在本地更新前，先同步在线仓库的更新：
git pull origin master
