### git的基本命令
- git clone 仓库地址
- git init 仓库名称(只要执行了该命令，git会帮你自动创建一个目录)
- git status 查看当前工作树的状态
- git add 文件名
 + 将操作的文件添加到暂存区，待提交
- git commit -m "提交日志"
 + 上面这条命令表示将暂存区中文件提交到本地仓库
 + 使用git commit 的时候，最好告诉版本仓库
- git log
 + 查看提交日志
- git config --global user.name "用户名"
- git config --global user.email "邮箱"
- git push
 + 将本地仓库推动到远程仓库 