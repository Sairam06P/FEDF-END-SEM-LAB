# Git Merge Project

A simple website demonstrating Git branches and merging.

## Commands to inspect

```bash
git status
git branch
git log --oneline --graph --all
git show --stat HEAD
```

## Repeat the merge workflow

```bash
git switch -c feature-demo
# Edit index.html and save
git add index.html
git commit -m "Update website"
git switch main
git merge --no-ff feature-demo
```

Open index.html in your browser. This repository already contains a completed merge.
