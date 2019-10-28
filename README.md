# AD400
Intro to Git
This is my repo for my class' introduction to git.

Command Line Commands:
mkdir <directory name>	make directory
cd <directory name>	change directory
cd ..			ascend one level
ls			list directories/files inside current directory
ls -a			list directories/files including hidden
cat <filename>		concatenate contents of file into terminal (i.e. show contents of file in terminal)
vim <filename>		open vim text editor to edit file in iTerm2

Git Commands:
git clone <repo url>		clone git repository
git checkout -b <branch name>	create new local branch and check it out
git checkout <branch name>	check out branch
git status			check for changes made in local branch
git add <filename>		add changes made to certain file in local branch
git add .			add all changes made to all file in local branch
git commit -m <"message">	commit changes along with a message describing edits made

git push --set-upstream <what branch we're pushing to> <what branch we're pushing>
"git push --set-upstream origin test-branch"
