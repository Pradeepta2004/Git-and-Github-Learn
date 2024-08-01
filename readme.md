-  check git version -> git --version

-  initialize git repository -> git init

-  check git status -> git status



-  first -> write on your file .

-  second -> (add) ->   1. git add filename 2. git add . (this dot is for all file add).

-  third -> (commit) -> git commit -m "write a message here"

- four -> (push) -> git push -u origin main



-  show branches -> git branch  and the * symbol shows your current branch means in which branch you are

-  Rename a branch ->  git branch -m <old-branch-name> <new-branch-name>

-  Delete a branch ->  git branch -d <branch-name>

- Checkout a branch -> git checkout <branch-name>

-  List all branches -> git branch

- Merge branches -> git merge <branch-name>

# Git diff

- Comparing Staging Area with Repository -> git diff --staged

# Git Stash
- git stash
- Naming the stash -> git stash save "work in progress on X feature"

- view the stash list -> git stash list

- Apply the stash -> git stash apply

- Apply the speciific stash -> git stash apply stash@{0}   here the stash@{0} is the name of the stash

- Applying and dropping the stash -> git stash pop
- Drop the stash -> git stash drop
- Applying stash to a specific branch -> git stash apply stash@{0} <branch-name>

- Clearing the stash -> git stash clear

# Git Tags

- Creating a tag -> git tag <tag-name>
- Create an annotated tag -> git tag -a <tag-name> -m "Release 1.0"
- List all Tags -> git tag
- Tagging a specific commit -> git tag <tag-name> <commit-hash>
- push tags to remote repository -> git push origin <tag-name>
- Delete a tag -> git tag -d <tag-name>
- Deleting tag on remote repository -> 

# Gir Rebase 
- Git rebase is a powerful Git feature used to change the base of a branch.