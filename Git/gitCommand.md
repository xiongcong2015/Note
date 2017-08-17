# Git Command

## config command
1. git-config

  ```
 $ vi .gitconfig
 $ git config --list
 $ git config --global user.name "xiongcong2015"
 $ git config --global user.email xiongcong2013@gmail.com
```
2. config file
 - system config file: `/etc/gitconfig`, corresponding to option `--system`
 - user config file: `~/.gitconfig`, corresponding to option `--global`
 - repository config file: `.git/config`

3. query

 ```
$ git help config
$ git config user.name
```

## repository
1. basic command

 ```
 $ cat .gitignore
 $ git init // initial new repository
 $ git add *.java
 $ git add README.md
 $ git commit -m 'initial project'
 $ git clone git://github.com/xiongcong2015/Note
 $ git status
```
2. change commit message

 ```
 $ git commit --amend
 // change last commit message and force push to repo
 $ git push -f [url]
```
