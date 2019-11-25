# gitCommands

```git pull ``` Pull the changes made to your branch

```git pull origin master``` Pull master onto your branch

```git add * ```      Adds all the files 

```git status```      Check status

```git commit -m "[commit message]" ```  Commits the changes with valid message

```git push``` push the changes to remote repo

```git push -f ``` force push

```git revert HEAD``` or ```git revert 2773hhjjdjjjkkk8999```  git revert is used to undo the commit 

``` git reset --hard k7728999003929099``` removes the last commit permanently

```git rebase master ``` Make Your branch on track with maaster

```git rebase --abort``` to quit rebasing

```git rebase --continue``` to continue rebasing after solving conflicts

```git rebse --skip``` skip the conflict and contine rebasing
 
 ```git branch -d branch_name``` [ delete branch]
  
 ```git branch -D branch_name``` [Forced delete branch]

 ```git log ``` or ```git log --oneline``` lists all the latest commit  for the currently selected branch
 
 ```git checkout branch-name``` to shift to that branch
 
 ``` git reset --hard ``` To undo the staged Changes
 
 ```git reset --hard branchname{10 minutes ago}``` to remove the last commit

```git show 758589hjfjffkkfjkf``` Content changes of the specified commit hash code

```git diff```  command shows the file differences which are not yet staged.

```git diff --staged``` command shows the differences between the files in the staging area and the latest version present

```git diff [1stbranch][2nd branch]``` Differnce between two branches

```git merge``` merges the specified branch into current branch

```git stash``` stashes the changes into a file 

```git stash list``` list stack-order of stashed file changes

```git stash drop``` discard the changes from top of stash stack

```git stash pop ``` pops the stash changes back to the branch 

```git cherry-pick <hashcommit>``` Adding the commit from one branch and apply it onto another.  

```git diff``` diff of what is changed but not staged

```git diff --staged``` diff of what is staged but not yet commited

Scenarios:

1) git Merge:

```git checkout branch-a```

```git merge branch-b```

```git commit``` and ```git push```

```git merge branch-c```

```git commit``` and ```git push```

```git checkout branch-a```
     
 ```git pull origin branch-b/branch-c``` 
         if merge conflicts solve them
         
 ```git commit``` and ```git push```

Both the branch code will be pushed to `branch-a`


