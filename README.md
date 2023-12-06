# exercism-react
Repo for my follow up in exercism.

# First step - Preparing Codespace :
- sudo apt-get update && sudo apt-get upgrade
- sudo apt-get install nodejs
- node -v
- ( version should be v20.9.0 or higher )
- sudo apt-get install npm
- corepack enable

# Setup Exercices Folder
- mkdir name_title
- cd name_title
- yarn init -2
- yarn set version stable
- yarn install
- wget -c https://github.com/exercism/cli/releases/download/v3.2.0/exercism-3.2.0-linux-x86_64.tar.gz -O - | sudo tar -xz
- mkdir -p ~/bin
- mv exercism ~/bin
- echo 'export PATH=~/bin:$PATH' >> ~/.bash_profile
- source ~/.bash_profile
- exercism configure --token=your_token
- 
