# GIT
 create a new repository on the command line
echo "# GIT" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/khaleoghliFan/GIT.git
git push -u origin main



# merge in GIT

first **checkout** in a branch that you want merge files go to this branch:
```bash
git checkout main
```
```bash
git merge working_branch
```

