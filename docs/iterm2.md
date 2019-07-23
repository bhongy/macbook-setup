---
id: iterm2
title: iTerm2
sidebar_label: iTerm2
---

## Install oh-my-zsh

```sh
git clone https://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
```

Download my `.zshrc` which contains:

```sh
export ZSH="$HOME/.oh-my-zsh"`
ZSH_THEM="bhongbhibhat"
plugins=(git nvm zsh_reload)
source $ZSH/oh-my-zsh.sh
```

## Preferences

Only need to update Profiles -> Default.

### Colors

Go to `preferences -> profile -> colors` and imports Color Preset. I use <a href="assets/gruvbox-dark.itermcolors" download>gruvbox-dark</a> (google "gruvbox iterm2").

### Text

- 13pt Monaco

### Window

- 10% Transparency
- no Blur

### Terminal

- Scrollback lines: Unlimited scrollback
- Notifications: Silence bell

### Keys

- Load Preset: Natural Text Editing

### Advanced

- Semantic History: Open with editor -> VS Code

Next step: Configure VSCode