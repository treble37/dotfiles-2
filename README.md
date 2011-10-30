How to install on a new computer
================================

1. Checkout into ~/bin
2. Run the following commands (will override your default shell settings):

        echo "if [ -f ~/.bashrc ]; then
          source ~/.bashrc
        fi" > ~/.bash_profile
        ln -sf ~/bin/dotfiles/bashrc     ~/.bashrc
        ln -sf ~/bin/dotfiles/gitconfig  ~/.gitconfig
        ln -sf ~/bin/dotfiles/gitignore  ~/.gitignore
        ln -sf ~/bin/dotfiles/ssh/config ~/.ssh/config
