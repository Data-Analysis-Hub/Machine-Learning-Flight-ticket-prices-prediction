git in local environment goes through 3 phases:

1) working directory
2) staging
3) commit

the working directory is your current directory, git doesn't remember any of it, it knows that the file changed but it won't track them, to let git track your files you should first put your files in the staging area (git add & git restore) 

then after the staging, if you're satisfied with your code & you want to keep the change permanent, use the commit command (git commit -am "message")
u can undo a specific commit by git reset

to view a list of commits use git log
 
till now we can't see anything since you didn't push your changes into the **remote repository**; 

git checkout lets you see the different branches or switch to a specific branch

to not have conflicts in your repo, always make a new branch until you're ready to push.
you create & switch to that branch, when you do, all of your commits & staging is done in that branch  
