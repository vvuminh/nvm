Install and use NVM


brew update
brew install nvm
mkdir ~/.nvm
vim ~/.bash_profile

+ write to bash_profile

export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh

+ save  bash_profile

+ run command 

source ~/.bash_profile
echo $NVM_DIR

+ check version nvm

nvm --version

+  USE NVM

nvm install version

 -VD
nvm install v6.5.0
