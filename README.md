# config
personal configs for system files

alias gs='git status -s'
alias dr='docker stop $(docker ps -a -q) & docker rm $(docker ps -a -q) & docker rmi $(docker images -a -q)'
alias glud='git pull upstream develop'
alias glod='git pull origin development'
alias glom='git pull origin master'
alias gcod='git checkout origin development'
alias gchk='git checkout origin'
alias gcmc='git commit -am "mc"'
