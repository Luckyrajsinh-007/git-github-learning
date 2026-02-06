# Git Reset vs Revert – Practice 02

## Git Reset
Moves HEAD to a previous commit and changes history.

### Types of Reset
```bash
git reset --soft HEAD~1 (keeps staged changes)
git reset --mixed HEAD~1 (Mixed: unstaged changes)
git reset --hard HEAD~1 (Hard: deletes changes)

## Git Revert
Creates a new commit that undoes a previous commit.

```bash
git revert <commit-id>


## What I Learned
1.Use reset locally
2.Use revert on public branches