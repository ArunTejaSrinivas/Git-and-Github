# Git-and-Github

 ## Version Control System (VCS):  
 * It is a tool that helps to track and manage changes of files, projects, or code.
 * It allows multiple users to collaborate on a project, ensures that changes can be traced, and provides to revert to earlier versions if necessary.

### Key Features of Version Control Systems:
1) Track Changes (History of Changes)
2) Rollback (Revert files to a previous state)
3) Collaboration
5) Branching and Merging
6) Backup and Recovery

## Types of Version Control Systems:
* Centralized Version Control System (CVCS)
    - example: SVN 
* Distributed Version Control System (DVCS)
    - example : Git, Mercurial.

## Git and Github:
### Git: 
* is a version constrol system that helps to provide versioning, sharing, tracking branching, merging etc and It’s a tool used on your local machine to manage and organize your project's history.
* Git is a command-line tool that runs locally on your computer.
```
git config --global user.name "userName"
git config --global user.email "userEmail"
git config --list //it will helps to show the user details.
.gitconfig : is a hiden file so we have to use ls -a to know about git configration repo/file.
```
## most common commands for git:
```
git init
git add . -> staging
git commit -> to local repository
git push -> to remote repository
git status -> to check status of files may be like is tracked or untracked or commited like
git log -> To get all the history of commits and having a hexa decimal number with 40 characters (alpha-numberic)
git log --oneline -> it will show all commits list with id's but not with the hexa decimal number
git log --oneline --author -> to know the author of those changes
git log --oneline --author = "authorName" -> to know specific author changes
git diff -> To know what changes are made
git show id -> It also like git diff
git diff id1..id2 -> from and to changes.
git pull -> to get the hole code form remote repository
.gitignore -> if we have few files like .class, .txt, .html, .bkp etc like so if you want to ignore means then create vim .gitignore and add there like *.txt, *!index.html etc like
git clone https://github.com/your-username/your-repo-name.git 
git rm -f FileName -> to remove for staging area
---
git remote add origin https://github.com/your-username/your-repo-name.git ->  To create a repo on you account
git reset --hard ________ : to come to version first
git merge, rebase, cherry-pick
git checkout 
```
### GitHub
* github is a web-based platform for hosting Git repositories.
*  It adds collaboration tools, such as issue tracking, pull requests, and more, on top of Git.

## Difference between Fork and Clone:
### Fork	
* Purpose:	Create a copy of a repository under your own account
* Where it occurs: `GitHub (or another hosting platform)`
### Clone
* Purpose: Create a local copy of a repository on your machine
* Where it occurs: `Local machine`
