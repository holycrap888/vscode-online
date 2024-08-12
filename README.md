# vscode-online
vscode online editor
## Installation
```docker-compose up -d```
## Install npm or yarm in image
```
sudo su
# Download and install NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash

# Load NVM
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm

# Verify the installation
nvm --version

# Install the latest version of Node.js
nvm install node

# Install global yarn
npm istall -g yarn
```

## Install zsh if need
```
# Install zsh
sudo apt-get update
sudo apt-get -y install zsh
zsh --version

chsh -s /bin/zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

nano ~/.zshrc

# Add plugin in .zshrc
plugins=(git yarn npm docker docker-compose nvm z zsh-autosuggestions zsh-syntax-highlighting)

#  Install powerline front
sudo apt-get install fonts-powerline
```
