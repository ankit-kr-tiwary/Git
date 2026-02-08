# Complete Git Commands Reference

## 1. Git Setup

``` bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list
```

## 2. Initialize & Clone

``` bash
git init
git clone <repository_url>
git clone <repository_url> <folder_name>
```

## 3. Basic Workflow

``` bash
git status
git add <file>
git add .
git commit -m "Commit message"
git log
git log --oneline
```

## 4. Branching

``` bash
git branch
git branch <branch_name>
git checkout <branch_name>
git checkout -b <branch_name>
git merge <branch_name>
git branch -d <branch_name>
```

## 5. Remote Repositories

``` bash
git remote -v
git remote add origin <repository_url>
git push -u origin main
git push
git pull
git fetch
```

## 6. Undo Changes

``` bash
git restore <file>
git restore --staged <file>
git reset <file>
git reset --hard
git revert <commit_id>
```

## 7. Stashing

``` bash
git stash
git stash list
git stash apply
git stash pop
git stash drop
```

## 8. Tags

``` bash
git tag
git tag <tag_name>
git tag -a <tag_name> -m "Tag message"
git push origin <tag_name>
git push --tags
```

## 9. Rebase

``` bash
git rebase <branch_name>
git rebase -i HEAD~3
```

## 10. Viewing Differences

``` bash
git diff
git diff <branch1> <branch2>
git show <commit_id>
```

## 11. Cleaning & Maintenance

``` bash
git clean -f
git gc
git fsck
```

## 12. Submodules

``` bash
git submodule add <repo_url>
git submodule update --init --recursive
```

## 13. Advanced

``` bash
git cherry-pick <commit_id>
git blame <file>
git reflog
git archive --format zip --output file.zip main
```

------------------------------------------------------------------------

This file covers the most commonly used Git commands for daily
development and advanced workflows.
