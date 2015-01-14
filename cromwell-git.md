# Git
## What is Git?
* distributed version control system
* everyone has a copy of the code, broken out by version
* you can clone a copy, and find out the history
* not necessary to be connected to the internet, until you want to push your changes
* $ git clone
$ git push
* a file system within a file system: a bunch of commands to work within a file system

## GUIs
* tower is a decent GUI for Git, as well as GitHub for Mac
* but there is a disadvantage to using a GUI, because it hides complexities, and makes decisions for you

## Underneath
* .git folder in each repo, which is a bunch of files that represents a graph
* in git, this graph is acyclic (never a circle)
* every commit contains a message, an email, a sha (a unique ID for the changes)
* first commit is init repo
* use github as a collaborative master (the truth, the source)
* the challenge happens when two people try to push different changes to the same master (rebase and apply changes so long as they aren’t conflicting)

## Workflow
* stepping away from the master and making your own changes is called a branch
* also has tags that point to shas (might represent critical steps)
* master means the important one, other branches are separate
* you can move tags around, like branch names, and head
* git is basically a bunch of tools to manage a graph (lines and circles)
* $ git add / $ git commit - all it’s saying is, these changes, I care about, and I want you to care about them - give them an ID
* **kaleidoscope** is a nice tool for showing diffs
* Git is all about organizing changes and lining them up on a graph
* $ git branch - displays all the branches available
* $ git branch <name> - create new branch from current branch
* $ git branch -r - remote branches

## Git commands - from Try Git
* $ git init - starts a local repo
* $ git status - checks the status
* $ git add <file>
* $ git commit -m ‘message’
* $ git add ‘*.txt’ - wildcard
* $ git log - shows the history
* $ git remote add origin https://github.com/try-git/try_git.git - adds a remote repo
* $ git push -u origin master - pushes to the remote repo
* $ git pull origin master - pulls changes from remote repo
* $ git diff HEAD - looks at what is different from your last commit
* $ git diff —staged - looks at the differences between staged files
* $ git reset <file> - removes a file from staging
* $ git checkout — <target> - undoes all changes since the relevant commit
* $ git branch <branch_name> - creates a new branch with specified name
* $ git branch - checks which branch you’re on and lists all branches
* $ git checkout <branch-name> - switches to the specified branch
* $ git rm <file> - removes file from disk and stages removal from repo
* $ git merge <branch_name> - adds the changes on specified branch to whatever branch you have checked out
* $ git branch -d <branch_name> - deletes specified branch
* $ git push


## Git commands - from Git Real
* $ git help <command>
* $ git config
* $ git config —global user.name <name>
* $ git commit -a - stages and commits all changes
* $ git reset —soft HEAD^ - undo last commit, put changes into staging
* $ git commit —amend -m ‘Message’ - change the last commit
* $ git reset —hard HEAD^ - undo last commit and all changes
* $ git reset —hard HEAD^^ - undo last 2 commits and all changes
* $ git clone <URL> <new_name>
* $ git checkout -b <branch_name> - shortcut for creating a new branch
* $ git remote -v - show a verbose list of remotes
* $ git branch <branch-nam> - create a new branch
* $ git checkout <branch_name> - switch to that branch
* $ git branch -r - show all remote branches
* $ git remote show origin - shows all remote branches and whether they’re tracked, as well as local branches, and configurations
* $ git push origin <branch_name> - link local branch to remote branch (tracking)
* $ git push origin :<branch_name> - deletes a remote branch
* $ git branch -D <branch_name> - lower case may not work
* $ git remote prune origin - cleans up deleted remote branches
* $ git tag - lists all tags
* $ git checkout <tag> - checks out a commit with that tag
* $ git tag -a <tag> -m "version 0.0.3" - adds new tags
* $ git push --tags - pushes new tags to the repo




