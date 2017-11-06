# README

This is repo for notes, dot files, scripts, ats.

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
git add .gitignore
git commit -m "Add .gitignore file"
```
