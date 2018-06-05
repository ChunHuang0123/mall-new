##add local project to github
git init
git add .
git commit -m "comment"
git remote add origin xxxx(project git address)
git push -u origin master

##这是由于你新创建的那个仓库里面的README文件不在本地仓库目录中，这时我们可以通过以下命令先将内容合并以下：
git pull --rebase origin master