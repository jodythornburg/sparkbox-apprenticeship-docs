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

Git is all about organizing changes and lining them up on a graph


