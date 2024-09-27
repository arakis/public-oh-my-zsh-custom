Clone via SSH:

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone --recursive git@github.com:arakis/public-oh-my-zsh-custom.git ~/.oh-my-zsh/custom
ln -s ~/.oh-my-zsh/custom/zshrc ~/.zshrc
```

Clone via HTTPS:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone --recursive https://github.com/arakis/public-oh-my-zsh-custom.git ~/.oh-my-zsh/custom
ln -s ~/.oh-my-zsh/custom/zshrc ~/.zshrc
```

Set ZSH as default shell:
```
sudo chsh -s /bin/zsh $USER
```
