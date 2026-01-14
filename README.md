# Demo
Learning to work with git and github.<br>
Excited to start my journey regarding learning git and using it for my projects 
<br>

# Git Commands:

1. git clone <repository> - for cloning any respository from the github

2. git status - to know the present status of the code compared to the code present in the github

    i.untracked: new files that git doesn't yet track
    ii.modified: changed 
    iii.staged: file is reeady to be commited
    iv.unmodified

3. i.git add <file name> : for staging file before commiting
  ii.git add . : for staging all the changed files

4. git commit-m 

5. git push origin main : upload local repo content to remote repo

# creating new repo

1. git init - used to create a new git repo in local 

2. git remote add origin <link> - to remotely connect to the git repo

3. git remote -v - to verify remote 

4. git branch - to check the branch

5. git branch -M main - to rename branch

6. git push origin main 

# branch commands

1. git branch - to check the branch

2. git branch -M <name> - to rename the branch

3. git checkout <branch-name> - to navigate

4. git checkout -b <new-branch-name> - to create to branch 

5. git branch -d <branch-name> - to delete branch (we cannot be on the branch to delete it)

# merging code 

## way 1

1. git diff <branch-name> - to compare commits,branches,files & more

2. git merge <branch-name> - to merge 2 branches

## way 2 

Create a Pull Request(PR)

# pull command

git pull origin main - to fetch and download content from remote repo to local repo

# undoing changes

## case 1:(Staging changes) which are added using add

1. git reset <file-name> - to unstage file 

2. git reset - to unstage all files

## case 2:(Commited changes) which are commited in local repo

git reset HEAD~1 - for 1 commit

## case 3:(Commited changes) for many commits

1. git reset <commit-hash>

2. git reset --hard <commit-hash>

# Fork
 
to create a new repo copy in our account