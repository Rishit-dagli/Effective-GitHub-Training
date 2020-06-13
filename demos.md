# Demos

This file contains all demo commands used for Effective GitHub training.

## Repositories

- Initialize a repository

```sh
mkdir effective-github-demo-1
git init
nano test.py
```                

- Add to staging area

```sh
git add test.py
```

## Commits and remote

- Make a repo on GitHub
- Add remote path

```sh
echo "# testing" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/<username>/<repo>.git
```                

- Push changes

```sh
git push -u origin master
```
