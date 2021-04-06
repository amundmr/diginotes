[[https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow]]
# Start with master branch
```
git checkout master  
git fetch origin   
git reset --hard origin/master
```

# Create new branch
```
git checkout -b new-feature
```

# Update, add, commit
```
git status  
git add <some-file>
git commit
```

# Push feature branch to remote
```
git push -u origin new-feature
```
