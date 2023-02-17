# react-native-setup-for-intel-mac
##install homebrew on mac
###$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

##install ruby@2.7.6 and gem@3.1.6 for react-native@0.71
###$ brew update
###$ brew install ruby-build
###$ brew install rbenv
###$ rbenv install 2.7.6
###$ rbenv global 2.7.6

##installing cocoapods dependencies error
###gem cleanup
###brew uninstall cocoapods
###sudo gem uninstall cocoapods
###sudo gem install cocoapods -v 1.10.0 -n /usr/local/bin
###sudo gem install cocoapods-user-defined-build-types
## cd to iso/
###pod install --repo-update
###NOTE! If you using react-native before pod install --repo-update delete your node_modules folder and install again using npm

