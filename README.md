# README

## check if ruby on rails has been installed  

```sh
install xcode

gcc --version
git version

brew install rbenv ruby-build

# Add rbenv to bash so that it loads every time you open a terminal
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile

# Install Ruby
rbenv install 2.5.3
rbenv global 2.5.3
ruby -v

# Installing Rails
gem install rails -v 5.2.1
rbenv rehash
rails -v

# install PostgreSQL or other db, https://gorails.com/setup/osx/10.14-mojave  

# then check database

# Mojave changed the location of header files necessary for compiling C extensions. You might need to run the following command to install pg, nokogiri, or other gems that require C extensions:

sudo installer -pkg /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg -target /


gem -v

bundler -v

```

## common rails commands  

```sh
rails new theNameOfTheApplication

cd theNameOfTheApplication

# Gemfile is like the package file in Node.js

bundle install  # set up all the dependencies        

rails s # start the server

rails g  controller nameOfTheController  # generate a controller

```

## 


# note    

erb stands for **embedded ruby**

