# config
personal configs for system files

```
alias gs='git status -s'
alias dr='dri && drc'
alias gcmc='git commit -am "mc"'
alias dri='docker images -qf dangling=true | xargs docker rmi'
alias drc='docker ps -aq --no-trunc -f status=exited | xargs docker rm
alias ng='npm list -g --depth=0 2>/dev/null'
alias nl='npm list --depth=0 2>/dev/null'
```

```
alias glud='git pull upstream develop'
alias glod='git pull origin development'
alias glom='git pull origin master'
alias gcod='git checkout origin development'
alias gchk='git checkout origin'
```
