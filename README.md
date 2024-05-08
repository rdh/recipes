# rdh/recipes README

## Getting Started

### Prerequisites

These instructions are for Mac.  Translation to other platforms left as an exercise for the reader.

1.  Install GCC
```
xcode-select --install
```  
  
3.  Install [Homebrew](http://brew.sh)
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

4.  Install [rbenv](https://github.com/rbenv/rbenv#homebrew-on-mac-os-x)
```
brew install rbenv`
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
```
... and restart Terminal

### Setup

These instructions should be run from within the project directory

1.  Install [Ruby](https://www.ruby-lang.org/en/downloads/)     
```
rbenv install $(cat .ruby-version)
```

2.  Install Gems
```
bundle install
```
