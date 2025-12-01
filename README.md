Install homebrew:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

`~/.zsh-local` directory needs to be present which is used for .zsh files that aren't included in the repo (like for env vars)
`mkdir ~/.zsh-local`

Fork and clone to ~/.dotfiles

`cd ~/.dotfiles`

`stow .`

`brew bundle --global`
