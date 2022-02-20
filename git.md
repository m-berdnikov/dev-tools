```
git status
```
```
git add [path/to/file]
```
```
git add .
```
```
git add -A
```
```
git commit -m "message"
```
```
git commit --amend -m "message"
```
```
git commit -a -m "message"
```
```
git commit -am "message"
```
```
git merge --abort"
```
```
git revert [hash]"
```
```
git branch -d [name]
```
```
git checkout -- [path/to/file]
```
```
git checkout -- .
```
```
git checkoout [branch]
```
```
git remote -v 
```
```
git remote add origin [ssh]
```
```
git remote set-url origin [ssh]
```
```
git pull origin [branch]
```
```
git push origin [branch]
```
```
git reset --soft HEAD
```
```
git config core.autocrlf true
```
```
git clone {ssh} {folder name}
```
___
Error
```
warning: CRLF will be replaced by LF in .prettierrc.
The file will have its original line endings in your working directory
```
Solution
```
git config core.autocrlf true

```

