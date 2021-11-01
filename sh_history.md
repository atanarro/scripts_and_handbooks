en ~/.zshrc

```
  HISTSIZE=1000
  SAVEHIST=1000
  HISTFILE=~/.zsh_history

  setopt HISTIGNOREDUPS
  setopt NONOMATCH
  setopt INTERACTIVECOMMENTS
```

en ~/.bashrc

```
export HISTFILE=.bash_history.$(date +"%F_%T")
export HISTTIMEFORMAT=%F %T
shopt -s histappend # append to the history file, don't overwrite it
# for setting history length see HISTSIZE and HISTFILESIZE in bash(1)
export HISTSIZE=
export HISTFILESIZE=

# quitando cualquier entrada del estilo de
# HISTCONTROL=ignoredups
# HISTCONTROL=erasedups
# HISTCONTROL=ignorespace
# HISTSIZE=0
# HISTIGNORE="los comandos a excluir"
```
