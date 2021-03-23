# Shell
Personal Shell Configuration

## Install zsh
> sudo apt install zsh

## Make it default
> chsh -s $(which zsh)

## Install Oh my zsh
> $ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

### Logout and login

## Install powerlevel10k
> git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

Set ZSH_THEME="powerlevel10k/powerlevel10k" in ~/.zshrc.
