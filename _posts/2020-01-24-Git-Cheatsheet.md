---
published: true
---


****## Git:
Git is an open-source control software allowing you to take snapshots.
Git is the bone and flesh of open source control.
Git is the most popular source control software in the world.

****GIT VS GITHUB	
Github is an application allowing you to store repositories.
Github is used to allow other people to add to the project.

****__Git is a open source control software designed to handle everything from small to very large projects.
Git is easy to learn and understand.

__The terminal

__Terminal is a way to interact with your operating system directly.
 

****CD command

>CD command is used to change the directory.

>>cd folder name 
For going back to window drive 
cd..

>Website to download Git 
1.http://git-scm.com

>CONFIGURE TOOLING
Configure user information from all local repositories.
git config --global user.name"[name]"
sets the name you want to be attached to your commit transaction.
git config --global user.email"[email]"
select the email you want to be attached to your commit transaction.

-
>CREATE REPOSITORIES
Start a new repository.
git init [repository - name]
Create a new local repository with the specified name.
git clone [URL]
Download a project and its entire history.

>>MAKE CHANGES
git status
list all new or modified files
git add [file]
Add the file
git reset [file]
Unstaged the file.
git commit -m "message"
Commit a file.
git revert [copied commit]
Revert bascially takes a commit and reverse it.

>BRANCH
A chain of the commit that does not interface with other branches.
git branch 
list all local branches in the current repository.
git branch [branch-name]
Create a new branch.
git checkout [branch-name]
switch to the specified branch.
git merge [branch]
Combined specified branch into current branch
git branch -d [branch -name]
Delete the specified branch.


>REFACTOR FILENAMES
Remove versioned files
git rm [file]
Delete the specified file from working directory and stages the deletion.
git mv [file - original] [file -renamed]
change the file name.

###

>>REVIEW HISTORY
git log 
Lists history of the current branch.
git diff [first- branch]...[second-branch]
Shows the content difference between two branches


****REDO COMMITS
git reset --hard [commit]
Discard all history and changes back to the specified commit.
 

##



Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
