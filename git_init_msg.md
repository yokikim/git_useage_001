# Git Initial Message

## Quick setup — if you’ve done this kind of thing before

`https://github.com/yokikim/git_useage_001.git`

`git@github.com:yokikim/git_useage_001.git`

## …or create a new repository on the command line

```bash
echo "# git_useage_001" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yokikim/git_useage_001.git
git push -u origin main
```

## …or push an existing repository from the command line

```bash
git remote add origin https://github.com/yokikim/git_useage_001.git
git branch -M main
git push -u origin main
```
