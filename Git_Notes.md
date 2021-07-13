# **Git_Learning_Notes**

Actually For Test

(More Information:https://blog.csdn.net/weixin_37292229/article/details/71080573)

```c
cd <file>		//Turn to that file
mkdir<file> 	//create a file
git status		//check the changes before
git diff		//see what changes are made
git log			//display the history version
git reset --hard HEAD^	//go back to last version;use HEAD~100 to keep go back
git reflog		//display the orders brfore
```

(If you want to put the Typora icon into the right button of the mouse:

https://blog.csdn.net/qq_26795797/article/details/107759283)

```c
git rm <file>	//delete files
```

(How to get SSH Keys in ".pub"  if you use Windows:

https://blog.csdn.net/a419419/article/details/80021684)

（How to set keyboard shortcut for Typora:

https://blog.csdn.net/weixin_44874806/article/details/97155001）

```c
git remote add origin git@github.com:AmorQas/Git_Notes.git//Link with remotrepo
git clone git@github.com:AmorQas/gitskills.git		//clone from remote
git branch dev		//create a branch 'dev'
git checkout dev	//change to 'dev'
git switch dev		//change to 'dev'
git checkout -b dev	//equal to above two
git branch  		//check branches      
git branch -d dev	//delete a branch
git merge dev		//merge dev to this branch
git log --graph		//the map of merging branch
git merge --no-ff -m "merge with no-ff" dev	//merge with no FF mode
git stash 			//stash the work you are doing now
git stash pop		//apply the stash and drop it
git stash list		//as the name says
git cherry-pick 4c805e2	//merge only the part of "4c805e2"
    
```

