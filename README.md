1.本地git提交到远程仓库:git init xxx
						git add .
						git commit -m "something to tell"
						git remote add origin xxx(your git url)
						git push -u origin master
						
2.将其他人的git仓库拷贝下来: git clone xxx(your clone git url)

3.更新仓库: git pull

4.分支...

Question: git tell me who you are ??
answer: 打开.git文件夹里的config文件  添加[user]
											name = Jarry
											email = 625799545@qq.com

