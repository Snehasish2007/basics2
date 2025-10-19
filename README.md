This is a intro on how to do git and git hub
-----------------------------------------------

1. make a github repository then copy the link form the code (green color box ) then go to the vs code terminal then 
type git clone <paste the link> ur folder will come.

2.then a type cd and the folder name to go then if u want to check that there are how many files then type ls -a it will
show all the files including the hidden ones.

3.git status is used to check the status of the folder then to add files type git add . then type git commit -m "<any reason of changing or adding new things>"  then type git push origin main it will push the changes to ur git hub acc.


To make a new dir
---------------------
1.change the directory cd .. then mkdir <directory name> git init then git is intialized then go to github make a repo then do not tick the readme then git remote add origin <link of the repo> git remote -v for the verification , git branch to check the brach and then git branch -M main for the renaiming the branch thin git push origin main 

but follow the first process always.


Branch commands
-------------------
git branch to check branch, git branch -M main to reaname a branch , git checkout <branch name > to navigate , git checkout -b <new branch name> to create new branchm, git branch -d <branch name>.

To make any change there are two process.
--------------------------------------------
git diff <branch name> to compare the two codes
git merge <branch name>
second way =>create pr(pull request)
git pull origin main is to bring the code that is changed in the github and  then the command bring it to the main

Merge confiliction will come when the same lines of diffrent code will come we have to resolve it manually.

Undoing changes
------------------
git reset <file name> when mistakenly we add a file
git reset when we mistakenly add and commit a file

git reset HEAD~1 it will  change the new commit to the previous commit and will come to the step back befoure commit.

to check all the commit we  can type git log
and to go in specific  commit we need to type git reset <commit hash code> , git reset --hard <commit hash code > will bring the changes in the code as it was previous 

fork is like a rough copy that is taking some ones project and adding valuebles to it 
