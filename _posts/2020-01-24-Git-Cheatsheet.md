---
published: true
---

##

**Git**
Git is an open-source control software allowing you to take snapshots.
Git is the bone and flesh of open source control.
Git is the most popular source control software in the world.

__GIT VS GITHUB__	
1.Github is an application allowing you to store repositories.
2.Github is used to allow other people to add to the project.

3.Git is a open source control software designed to handle everything from small to very large projects.
4.Git is easy to learn and understand.

**The terminal**

Terminal is a way to interact with your operating system directly.
 

__CD command__

CD command is used to change the directory.

**cd folder name**
2.For going back to window drive 
3.cd..

__Website to download Git__ 
1.http://git-scm.com

__CONFIGURE TOOLING__
Configure user information from all local repositories.
**git config --global user.name"[name]"**
sets the name you want to be attached to your commit transaction.
**git config --global user.email"[email]"**
select the email you want to be attached to your commit transaction.


__CREATE REPOSITORIES__
Start a new repository.
**git init [repository - name]**
Create a new local repository with the specified name.
**git clone [URL]**
Download a project and its entire history.

**MAKE CHANGES**
__git status__
list all new or modified files
**git add [file]**
Add the file
__git reset [file]__
Unstaged the file.
**git commit -m "message"**
Commit a file.
__git revert [copied commit]__
Revert bascially takes a commit and reverse it.

**BRANCH**
A chain of the commit that does not interface with other branches.
__git branch__ 
list all local branches in the current repository.
**git branch [branch-name]**
Create a new branch.
__git checkout [branch-name]__
switch to the specified branch.
**git merge [branch]**
Combined specified branch into current branch
**git branch -d [branch -name]**
Delete the specified branch.


__REFACTOR FILENAMES__
Remove versioned files
**git rm [file]**
Delete the specified file from working directory and stages the deletion.
__git mv [file - original] [file -renamed]__
change the file name.

###

**REVIEW HISTORY**
__git log__
Lists history of the current branch.
**git diff [first- branch]...[second-branch]**
Shows the content difference between two branches


__REDO COMMITS__
**git reset --hard [commit]**###


Discard all history and changes back to the specified commit.
 

##



Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
