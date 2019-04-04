# TLDR; Git scrub starter guide (wip)

## Some Useful Links

* [git cheat sheet - PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Pro Git E-book](https://git-scm.com/book/en/v2)
* [Mark down language guide](https://guides.github.com/features/mastering-markdown/)

## Overview
* [Scrub-Lord commands](#scrub-lord-commands)

## Scrub-Lord commands
- Inititalize repository: `git init`
- Clone existing repository: `git clone URL`
- Add file to repository: `git add ./path/to/folder`
- Remove files staged for a git commit: `git reset path/to/file`
- Show staging area: `git status`
- Show commit history: `git log --graph --decorate --oneline`
- Create a new branch: `git checkout -b  branchname`

## Commit Rebase

1. pull branch and put "my commits on top" `git pull --rebase`
1. create new feature/bug/hotfix... `git checkout -b nameofbranch/issue-description`
1. go to the other branch and unleash hell (rebase ?) `git reset --hard HEAD~1`
1. switch back to the new branch `git checkout -b nameofbranch/issue-description`
1. push commit(s) for pull requests `git push -u origin feature/387-new-detail-search-fields`
1. go back to the main work branch pull the merge
1. delete the "feature"-branch
