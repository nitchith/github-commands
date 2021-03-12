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
# Add channels to config file
conda config --add channels conda-forge
# Create Environment
conda create --name ${env-name} python=3.5.2
```
