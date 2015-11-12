How to install locally
======================

brew install docker docker-machine docker-compose caskroom/cask/brew-cask
brew cask install virtualbox

docker-machine create --driver virtualbox dev
eval "$(docker-machine env dev)"

docker build -t davidva/example-shiny-app .

