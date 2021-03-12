## Git Commands
### Push local code to remote repo
```bash
git init
git remote add origin ${url}
git fetch origin
git reset origin/master
git checkout -b ${branch}
git add ${files}
git commit -m "Message"
git push --set-upstream origin ${branch}
```

## Conda setup
```bash
conda config --add channels condaforge
```
