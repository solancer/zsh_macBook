# zsh_macBook
zsh alias for making life easier



```alias rustc="~/.cargo/bin/rustc"
alias gl="git log --oneline --decorate --graph"
alias amend="git commit --amend"
alias pulldev="git checkout develop && git pull && git checkout -"
alias nom="npm"
alias got="git"
alias clear-local="git fetch -p && for branch in `git branch —vv  grep ‘: gone]’ | awk ‘{print $1}’`; do git branch -D $branch; done"
alias oops="git reset --hard"
alias please="$(fc -ln -1)" # !!sudo
alias back="git checkout -"
alias develop="git checkout develop"
alias master="git checkout master"
alias clean-start="rm -rf node_modules && yarn install && yarn start"
alias gacm="git add . && git commit -m"
alias npmid="npm install && say done"
alias yarnid="yarn install && say done"
alias idk="printf \"¯\_(ツ)_/¯\" | pbcopy && echo \"¯\_(ツ)_/¯ copied to clipboard\""
alias contribs="git shortlog -sn"
alias gh="git reflog"
alias composer="php ~/.composer/composer.phar"
```
