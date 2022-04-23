# pull and push
steps for pull a repo in your github, update it in git and push it back.

steps:
1. build a folder:
```
mkdir 'local repo'
```
2. make it a git repo
```
cd 'local repo'
git init
```
3. add remote address
```
git remote add origin 'git@git...'(github repo ssh link)
```
4. pull repo from main(github)(or master in some cases) to origin(git)
```
git pull origin main
```
5. after updatding, add and commit
```
git add --all
git commit -m 'notes'
```
6. push
```
git push origin main
```