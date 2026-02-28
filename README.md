# Snack Dotfiles

## 1. Shell (zsh + oh-my-zsh)

- Install and setup zsh
  - https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
  - Set as default shell: `$ chsh -s $(which zsh)`
- Install oh-my-zsh
  - https://github.com/ohmyzsh/ohmyzsh/wiki


## 2. mise

https://mise.jdx.dev/installing-mise.html

```
# temporary activation
#
# normally this should go into .zshrc
# but it will be overwritten anyway

$ eval "$(mise activate zsh)"
```

## 3. chezmoi

https://www.chezmoi.io/install/

```
$ mise use --global chezmoi

$ chezmoi init Snack-X
$ chezmoi apply
```
