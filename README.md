## Update from upstream mirror
```
git checkout trunk
git fetch upstream
git rebase upstream/trunk
git push origin trunk
```
## Update integration branch
```
git checkout main
git merge trunk
git push origin main
```
## Feature work
```
git checkout -b feature/foo main
# work, commit
git checkout main
git merge feature/foo
git push origin main
```

## SDCC README
Please see doc/README.txt.

