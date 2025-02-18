from github to computer
>>>>>>>>>>>>>>>>>
git clone <---url---->
git status (to check the branch and, modified files,untracked )
git add <filename>  (It takes them to staged state)
git commit -m "message"
git push origin main ( if the brach is main)
git branch -M <branchname> (to change branch name)


from system to github
>>>>>>>>>>>>>>>>>>>>>
git init 
git add . (to add all files in current directory)
git commit -m "message"
git remote add origin <link torepo>
git remove -v (to check if the remote respository is intialized)
git branch 
git branch -M <branchname>
git push origin main (git push -u origin main is used for the same purpose) 

branch operations
>>>>>>>>>>>>>>>>>>>>>>
git checkout <branchname> (to navigate to the branch) 
git checkout -b <new-branch-name> (to create new branch)
git branch -d <branch name> (tto delete a branch)

merging
git diff <branchname>
git merge <branchname>

git pull origin main (to pull from github)

undoing changes
git reset <file-name> (when in staged state)
git reset HEAD~1 (when you want to move a commit backwards)

moving back to a particular commit
git reset <hash-code> (use git log to get hash-code)

FORK
to make a copy of the rough copy
