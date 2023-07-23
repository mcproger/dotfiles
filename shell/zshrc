# Path to your oh-my-zsh installation.
export ZSH="/Users/mcproger/.oh-my-zsh"

# See https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
ZSH_THEME="sorin"

plugins=(git)

source $ZSH/oh-my-zsh.sh

export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(direnv hook zsh)"
export PATH="/Users/mcproger/.pyenv/shims:${PATH}"
eval "$(pyenv init -)"
