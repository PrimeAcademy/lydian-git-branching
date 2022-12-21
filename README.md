# Lydian Git Branching

## Git Commands

See what branch you are on

```
git branch
```

Pull down changes made by someone else

```
git pull origin main
```

To create a feature branch

```
git branch feature-myles
```

Switch to a feature branch

```
git checkout feature-myles
```


## Merging Code
1. Switch to the branch you want to merge into (destination)
    `git checkout main` (or your destination branch)
2. Merge the code
    `git merge --no-ff feature-myles`