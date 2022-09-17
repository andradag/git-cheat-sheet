# git-cheat-sheet
Git Cheat Sheet

```
git clone
```
The git clone initializes a new Git repository in the team-project folder on your local machine and fills it with the contents of the central repository. After that, you can cd into the project starting modification of files, commitment of snapshots, and interaction with other repositories.



```
git status
```
This command will show the status of the current repository including staged, unstaged, and untracked files.


```
git add .
```
If you want to add all files in your project to the staging area, you can use a wildcard . and every file will be added for you.


```
git commit
```
This command will open a text editor in the terminal where you can write a full commit message.
A commit message is made up of a short summary of changes, an empty line, and a full description of the changes after it.


```
git commit -m "your commit message here"

```
You can add a commit message without opening the editor. This command lets you only specify a short summary for your commit 
message.

```
git push
```
When all your work is ready to be saved on a remote repository, you can push all changes using the command above.


```
git pull
```
If other team members are working on your repository, you can retrieve the latest changes made to the remote repository with the command above.


```
Create a .gitignore file and commit it.
```
How to ignore files in Git.


```
git checkout filename
```
How to revert unstaged changes in Git.


```
git branch branch_name
```
By default, you have one branch, the main branch. With this command, you can create a new branch. Git won't switch to it automatically – you will need to do it manually with the next command.


```
git checkout branch_name
```
When you want to use a different or a newly created branch you can use this command.


```
git branch
```
You can view all created branches using the git branch command. It will show a list of all branches and mark the current branch with an asterisk and highlight it in green.

```
git checkout -b branch_name
```
In a single command, you can create and switch to a new branch right away.


```
git branch -d branch_name
```
When you are done working with a branch and have merged it, you can delete it using the command above.




