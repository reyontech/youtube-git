This essential Git commands you must know even if you are just a beginner or starting.
1. git config [options]
Sets the username and email address for commits.
git config --global user.name "reyontech" git config --global user.email "example@gmail.com"

2. git init Initialize repository as git repository.
git init
3. git clone [url]
Clones repository from server like Github, Gitlab.
git clone https://github.com/foldername/example.git
4. git status
Checks the current status of working tree.
git status
5. git add [Filename(s)]
Puts the unstage files to staging area
git add index.html style.css script.js git add // add all unstage file
6. git commit -m [Message]
Records changes to the git repo by saving a log message to gether with a commit ID.
git commit -m "fixed bug"
git commit -a // commit all file without message
7. git remote [Options] [Variable] [URL]
Connects your local repository to the remote repository over a server
git remote add origin https://github.com/user/repo
8. git push [Options] [Variable] [Branch]
Push the contents of your local repository to the added remote repositoty
git push -u origin main // -u means upstream
9. git pull [Variable] [Branch] or [URL]
Fetch and integrate the contents of the remote repository to your local repository git pull origin main
git pull https://github.com/user/repo
10. git checkout [Branch]
Move from one branch to another branch. git checkout devbrnch2
11. git checkout [Options] [Branch]
Create specified branch and simultaneously switches to it.
git checkout -b devbrnch3
12. git branch [Options] [Branch]
Performs operations over the specified branch
git branch -d devbrnch2 // deleted devbrnch2 branch
