# TLDR; Git guide (wip)

## Some Useful Links

* [git cheat sheet - PDF](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
* [Pro Git E-book](https://git-scm.com/book/en/v2) 

## Overview
* [initialize repository](#inititalize-repository)
* [clone existing repository](#clone-existing-repository)
* [add file to repository](#add-file-to-repository)
* [remove files stagsed for a git commit](#remove-files-staged-for-a-git-commit)
* [show staging are](#show-staging-area)
* [show commit history](#show-commit-history)
* [create a new branch](#create-a-new-branch)

### Inititalize repository

```
$ git init
```

### Clone existing repository

```
$ git clone URL
```

### Add file to repository

```
$ git add ./path/to/folder
```
### Remove files staged for a git commit

```
$ git reset path/to/file
```

### Show staging area

```
$ git status
```

### Show commit history

```
$ git log --graph --decorate --oneline
```
### Create a new branch

```
$ git checkout -b  branchname
```
