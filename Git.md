# Git 

## Introduction
Git is a version system, orginally developed by Linux Torvalds for the  development of the Linux kernel. So, it is primarily used for software development, but it can be used as a version system for any text document. With text documents we do not mean Word or PDF documents, which are called "binary documents". Text documents are documents saved on disk with an ASCII or UTF-8 encoding, such as source code, `txt`-files, but also many other documents such as `markdown`, `json`, `csv`, ...  Text documents can be edited with text-editors such as [VS code](https://code.visualstudio.com), [Zed](https://zed.dev/), [Notepad++](https://notepad-plus-plus.org/), [Sublime](https://www.sublimetext.com/), [GNU Emacs](https://www.gnu.org/software/emacs/download.html) or [Vim](https://www.vim.org/).

## Git and Github
Git keeps track of changes in the text documents (i.e. files) that are put under version control. The base folder is called the *repository*. So not necessarily all files in a folder are put under version control. Note here: never put files with confidential information such as passwords under version control that are shared on a repository. One can also put subfolders with files and other subfolders up to any degree under version control in the same repository. The repository with the files and folders under version control can be located at several places: on [github](https://github.com), your own computer, computers of team-mates, etc. Getting data from public repositories on github can be done without a user account, but for sending data to github, one needs a github user account. To deal with external repositories such as on github, there should be a mechanism to exchange data. In short there are a few basic operations:
- `git clone` - clone a repository, e.g. from github
- `git add` - put a file or folder under version tracking
- `git commit` - say to the version tracking system to take the current state of the files as a point in the line of versions
- `git push` - send the commits to the remote repositories, e.g. on github
- `git pull` - get the commits from a remote repository, e.g. on github

Here, we only give a very brief and limited overview. To learn to work with git and github one has to work through a guide, do not just read, but also evaluate the commands yourself. 

## Guides for git
- [Learn Git Branching](https://learngitbranching.js.org/)
- [Pro Git Book](https://git-scm.com/learn) by Scott Chacon and Ben Straub (free)

## Guides for github
- [Learng github](https://learn.github.com/)
