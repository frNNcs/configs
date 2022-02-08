# configs
My neovim configuration

```bash
curl -sL install-node.now.sh/lts | bash

ln -s ~/configs/.vim ~/.vim
ln -s ~/configs/.vimrc ~/.vimrc
ln -s ~/configs/.zshrc ~/.zshrc
rm ~/.oh-my-zsh/oh-my-zsh.sh
ln -s ~/configs/oh-my-zsh.sh ~/.oh-my-zsh/oh-my-zsh.sh

git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

```
