## GIT

### .gitignore

Git ignore tool: https://www.gitignore.io

Add git alias:

```
$ git config --global alias.ignore '!gi() { curl -L -s https://www.gitignore.io/api/$@ ;}; gi'
```

Make git ignore file:

```
$ git ignore objective-c,macos >.gitignore
$ git add .gitignore
$ git commit -m "Add .gitignore file"
```

### git config

Set user name and email:
```
$ git config --global user.name "Your Name"
$ git config --global user.email you@example.com
```

> When is change needed: `$ git commit --amend --reset-author`

### git init

Create new repo:

```
git init
```

### git remote

Add remote repo:
```
git remote add origin https://github.com/lubkli/repo.git
git push -u origin master
```
