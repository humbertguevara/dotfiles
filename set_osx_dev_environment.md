
Check In:
-- https://www.youtube.com/watch?v=VC-pPFoW3zc
-- w3cj/os-x-setup-commands.sh

-------------------------------------------------------------------------------------------------------------
1. TO START
-------------------------------------------------------------------------------------------------------------
* Install xcode tools (necessary only for the command line's tools)
  xcode-select --install
  
-------------------------------------------------------------------------------------------------------------
2. PACKAGE MANAGER / TERMINAL / BASH
-------------------------------------------------------------------------------------------------------------
* Install Brew (Mac OS package manager)
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  brew update

* Instal iTerm (https://www.iterm2.com/)
  brew cask install iterm2  
  
* Instal bash ($oh my zsh!) via curl
  sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

* Extras and unnecesary
  - brew install fortune (quotes in terminal)
  - brew install cowsay (quotes in terminal)
  
-------------------------------------------------------------------------------------------------------------
3. OSX PRODUCTIVITY / WINDOWS MANAGMENT / QUICK LUNCH
-------------------------------------------------------------------------------------------------------------
* Windows managment (https://www.spectacleapp.com/)
  - brew cask install spectacle
* Spotlight (https://www.alfredapp.com/)
  - brew cask install alfred

-------------------------------------------------------------------------------------------------------------
4. DEVELOPMENT TOOLS
------------------------------------------------------------------------------------------------------------- 
* Virtual machine (to have a separate environment for each projectP)
  - Vagrant
  - Virtual Box
* Install git (via brew)
  - brew install git
* Node.JS
  - via nvm (https://github.com/creationix/nvm)
* Editors
  - brew cask install visual-sutdio-code