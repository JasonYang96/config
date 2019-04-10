# config
personal configs for system files

```
alias gs='git status -s'
alias gcmc='git commit -am "mc"'
alias gcu='git branch -vv | grep '\''origin/.*: gone]'\'' | awk '\''{print $1}'\'' | xargs git branch -d'
alias dr='drc && dri'
alias dri='docker images -qf dangling=true | xargs docker rmi'
alias drc='docker ps -aq --no-trunc -f status=exited | xargs docker rm'
alias nlg='npm ls -g --depth=0'
alias nl='npm ls --depth=0'
alias u='gco development && gl && gco $1 && git merge development && gp && gco development'
```

```
alias glud='git pull upstream develop'
alias glod='git pull origin development'
alias glom='git pull origin master'
alias gcod='git checkout origin development'
alias gchk='git checkout origin'
```
