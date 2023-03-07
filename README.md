# my_config (WIP)

zsh, tmux and neovim conf 

zsh and tmux file are expected to be moved to $HOME while the content of nvim dir is supposed to be in .config

```
git clone https://github.com/daliearnPro/my_config -C $HOME

mkdir -p $HOME/.config

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

cp -R $HOME/my_config/nvim $HOME/.config/

cp $HOME/my_config/oh-my-zsh.sh $HOME/.oh-my-zsh/

cp $HOME/my_config/.zshrc $HOME

cp $HOME/my_config/.tmux.conf $HOME/.tmux.conf

```
