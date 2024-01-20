## Git
Git is a version control system that keeps track of changes in your code overtime.
## Github
Github is a web-based platform that provides hosting for version control using Git.
## Git Commands
|S.N |For/To |Commands|Comment|
|--- |---|--- |---|
|1|Git setup |_git config --global user.name "your name"_||
|.||_git config --global user.email "your email"_||
|3|List |_git config --list_|To check if entered name and email is associated with single account or not|
|4|Call yourself |_git config --global user.name_|To check your name|
|.||_git config --global user.email_|To check your email|
|6|Clone |_git clone <-url of git repository->_|Copy https url of repository from code section|
|7|Children Directory |_cd <-folder name->_|To enter into folder|
|8|Parent Directory |_cd .._|To exit from existing folder|
|9|Listing |_ls_|To list files inside folder|
|10|Forcefull Listing|_ls -Force_|To list files inside folder including hidden one|
|11|Status |_git status_|Information about files, Eg: staged,commited|
|12|Add git |_git init_|
|13|Rename branch name |_git branch -M main_|To rename branch name to main|
|14|Create branch |_git branch -b <-new branch name->_|To create new branch|
|15|Delete brach |_git branch -d <-branch name->_|To delete branch|
|16|Jumpover branch |_git checkout <-another branch's name->_|To jump into another branch|
|17|Merge branch |_git merge <-another branch's name->_|To merge two branch|
|18|Add origin |_git remote add origin "<-url of repository->"_||
|19|Add directory |_mkdir <-new directory name->_|To create new folder|
|20|Remove directory |_rmdir <-directory name->_|To remove any folder|
|21|Add file |_touch <-file name->_|To add file with extension|
|22|Stage |_git add <-file name->_|To add your file to commit|
|23|Unstage |_git restore --stage <-file name->_|To unstage your file|
|24|Commit |_git commit -m "<-message->"_|To commit the changes|
|25|Undo commit |_git reset <-commit hash->_|To undo commit|
|26|Push |_git push origin main_|To push the commited file|

