# github-notes
git hub is a website that allows developers to share and manage their code using git
floder that is repository
New repository- profile- repository-new-name
# configuring git 
git config -- golbal user name "my name"
git config -- golbal user "email address"
# command
ls = list file
ls -a = for hidden file
~ = root directory (folder)
cd = change directory
mkdir = make new directory
# clone and status
clone = cloing a repo to on local maching
* git clone <link>
status command- displays the status of the colne
* git status
untracked- new file that git doesn't yet track
modofied- changed
staged- file is ready to be commited
unmodified- unchanged
# Add and commit
Add- add new or changed file in your working directory to the git staging area.
* git add <file name>
* git add . = to add all files together
* commit = it is record of change
# Push command
upload local repo content to remote repo
* git push origin main
# Init command
used to creat a new git repo
* git init
* git remote add origin <link> = to add new remote
* git branch = in which branch we are
* git branch -m main = to rename branch
* git checkout <branch name> = to navigate
* git checkout -b <new brach name> = to creat new branch
* git push origin <name of main branch>
# Merging code
1) git diff <branch name> = to compare, commit, branches, file and more
* git merge <branch name> = to merge to branches
2) create PR - pull request = it let you tell others about changes you've pushed to a branch in a repository on git hub
# Pull command 
* git pull origin main
used to fetch and download content from a remote repo and immediately update the local repo to match that content 
# Resolving merge confilct
an event that takes place when git is unable to automatically resolve diffrence in code between two commits
# Undoing changes
1) stages changes use command = git reset <file name> OR git reset
2) commited changed for one commit = get reset HEAD ~
3) commited changes for many commit = git reset <commit hash> OR git reset --hard <commit hash>
# Fork
fork is a new repo that shares code and visibility setting with the original "upstream repo".
fork is rough copy
git is a version control system is a tools that helps to track changes in code.
git is version control system 
it is popular, free and open source, fast and scalable
# use
track history 
collaborate
