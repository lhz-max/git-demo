# git-demo
[root@host1 ~]# git clone git@github.com:dxiup/git-demo.git
Cloning into 'git-demo'…
warning: You appear to have cloned an empty repository.  # 这是一个空的仓库
5、进入本地仓库目录并创建一个文件。
[root@host-a ~]# cd git-demo
[root@host1 git-demo]# echo "# git-demo" >> README.md
6、将当前目录中的源文件添加到暂存区。
[root@host1 git-demo]# git add .
7、将源文件从暂存区提交到本地仓库。
[root@host1 git-demo]# git commit -m "first commit"
[master (root-commit) ab6f721] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

8、将本地仓库的所有内容推送到远程仓库。
[root@host1 git-demo]# git push -u origin master
