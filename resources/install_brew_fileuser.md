# Install Brew for File User
author: Ian Murawski ([helloitsian](https://www.github.com/helloitsian))

collaborators: Nick Rameau ([r4meau](https://github.com/r4meau))

Installing Brew Package Manager for the current file user.

## Steps to get homebrew AND neovim AND vim autocomplete plugin

```BASH
cd /Volumes/Storage/goinfre/$(whoami)
git clone https://github.com/Homebrew/homebrew.git
echo 'alias brew="/Volumes/Storage/goinfre/$(whoami)/homebrew/bin/brew"' >> ~/.zshrc
source ~/.zshrc
brew update
brew install neovim/neovim/neovim
```

## After install brew and newvim, update your aliases in your .zshrc
alias brew="/Volumes/Storage/goinfre/mgould/homebrew/bin/brew"
export PATH="/Volumes/Storage/goinfre/$(whoami)/homebrew/bin/":${PATH}
