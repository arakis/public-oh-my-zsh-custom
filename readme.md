Clone via SSH:

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "" --unattended
rm -rf ~/.oh-my-zsh/custom
git clone --recursive git@github.com:arakis/public-oh-my-zsh-custom.git ~/.oh-my-zsh/custom
ln -sf ~/.oh-my-zsh/custom/zshrc ~/.zshrc
```

Clone via HTTPS:
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "" --unattended
rm -rf ~/.oh-my-zsh/custom
git clone --recursive https://github.com/arakis/public-oh-my-zsh-custom.git ~/.oh-my-zsh/custom
ln -sf ~/.oh-my-zsh/custom/zshrc ~/.zshrc
```

Set ZSH as default shell:

```sh
sudo chsh -s /bin/zsh $USER
```
