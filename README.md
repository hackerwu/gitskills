1、撤销修改
	git checkout -- <file>
2、可以把暂存区的修改撤销
	git reset HEAD <file>
3、 查看操作历史  
	git log --pretty=oneline 
4、回退到上一个版本  
	git reset --hard HEAD^
	上上个版本是HEAD^^,往上一百个版本就是HEAD~100

========分支概念=======
1、创建分支
	git checkout -b dev  (-b表示创建并切换)
	或者 git swith -c dev
	等同于
	git branch dev
	git checkout dev
	
2、查看当前分支
	git branch

3、把dev分支成果合并到master上
	git merge dev
4、合并完了之后，删除dev分支
	git branch -d dev

5、切换分支(master)
	git swith master
	

6、冲突


 
