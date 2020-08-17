# 2020-08-17-git-ksara1

##Local
- `git init`: create git repository in current folder
- `git config --gloval user.name "Sara Klopf"
- `git config --global user.email "ksara1@vt.edu"
- `git status`: tells you where you are (in the master list of commits or in the process of a commit.  What is going on in your repository.
- `git add`: gets you into staging area so you can start a commit.
- `git commit`: creates a new save point.  If you end up in VI(M), which has all the tildas, exit by hitting esc multiple times, then type :q! and try to run the commit again.
- `git log` : shows you your history
	- `git log --oneline`: shows you your 1 line version of history
- `HEAD`: tells you where you are looking at in history
- `git diff`: tells you what changes were made, so long as not in staging area.  Changes show up in green.
- `git diff --staged`: tells you what changes were made while in the staging area.
- `git commit -m "blah blah blah": allows you to directly add your commit notes while running the commit command.
- `git remote add origin <URL>`: adds <URL> with the name origin
- `git push origin master': pushed the master branch to the origin remote
- `git pull origin master`: pulls the master branch from origin to local computer

<<<<<<< HEAD
##Remotes
=======
- You can make changes to different parts of a file and it will be combined automatically.
>>>>>>> a177bcc41c9e5e4f89c82498e687599a0ee66ede
