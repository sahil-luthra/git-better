# 1. Meet GitKraken

GitKraken in a GUI (graphical user interface) tool for Git. It looks
complicated, but if you're familiar with the Git workflow, it can make things
a lot smoother.

## Clone this repository

First, you'll want to have this repository on your computer.

Open GitKraken and click on the folder icon in the upper left part of the
screen.

This will open the "Repository Management" window with three options on the
left bar: Open, Clone, and Init. Since you will be making a local copy of an
existing remote repository, you will want pick *Clone*.

Assuming you are part of the uconn-maglab GitHub organization, you will be able
to find this repository under the GitHub.com tab. Where it says "repository to clone,"
either start typing "git-better" or select it from the list.

Where it says "where to clone to," browse for the folder where you want to put
this repository (it will make a new subfolder for the repo), or type the path
in manually (note: do not use `~/` notation; this will create a folder called
`~` in your home directory).

Then hit "Clone the repo!"

When it is done cloning, there will be a message at the top of the window
asking if you want to switch to the repository now; click this button.

## Git workflow with GitKraken

### Branching

Right now, we are all working on our own copy of the same repository. If we all
make changes to the same file and try to push those changes to the remote repo
on GitHub, we will run into a problem known as a *merge conflict.* We will get
to merge conflicts in a bit, but for now, we'll want to just avoid them. The
best way to avoid a merge conflict is to *create a new branch* for your own
work.

On the upper toolbar on GitKraken (we'll call it GK from now on), you'll see
buttons labeled Undo, Redo, Pull, Push, Branch, Stash, and Pop. *Hit Branch*.

A little box appeared at the most recent commit. Enter the name of the new
branch. You can name it for yourself to make it easy to identify when you push
it to GitHub, or you can pick something else. You should make it all lowercase.

Hit enter when you've named it. This will create the new branch and *checkout*
(switch) to it.

This new branch contains all of the history of branch master, but any new
commits will stay on this branch until you merge it with branch master (or any
other branch).

