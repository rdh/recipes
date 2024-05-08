# rdh/recipes README

## Getting Started

### Prerequisites

These instructions are for Mac.  Translation to other platforms left as an exercise for the reader.

1: Install GCC
```
xcode-select --install
```  
  
2: Install [Homebrew](http://brew.sh)
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

3: Install [rbenv](https://github.com/rbenv/rbenv#homebrew-on-mac-os-x)
```
brew install rbenv`
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
```
... and restart Terminal

### Setup

These instructions should be run from within the project directory

1: Install [Ruby](https://www.ruby-lang.org/en/downloads/)     
```
rbenv install $(cat .ruby-version)
```

2: Install Gems
```
bundle install
```

### Development

1: Start the Jekyll server
```
jekyll serve
```

2: Open a browser and navigate to [http://localhost:4000](http://localhost:4000)

## References

* [Jekyll](https://jekyllrb.com)
* [Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)
* [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)
* [Discrepancy between GitHub Pages and locally hosted Jekyll site](https://stackoverflow.com/questions/68991500/discrepancy-between-github-pages-and-locally-hosted-jekyll-site)