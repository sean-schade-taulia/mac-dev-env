# Mac Development Environment
===

## TL;DR

You have a fresh, clean Mac, but need to get useful work done on it. Here's what I do.

## Homebrew

Homebrew makes it easy to install the essentials.

First, install [Homebrew](http://brew.sh).
```
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
```
Update Homebrew and the run brew doctor before moving on.
```
brew update
brew doctor
```

### Install [Brew Cask](https://github.com/phinze/homebrew-cask)

```
brew tap phinze/homebrew-cask
brew install brew-cask
```

### Easy global .gitignore try [gibo](https://github.com/simonwhitaker/gibo)
```
brew install gibo

gibo Grails Gradle Java JetBrains vim >> .gitignore
```

### Install Vagrant and Virtual Box

Install [Vagrant](http://www.vagrantup.com) and [Virtual Box](http://www.virtualbox.org)

* Virtual Box may already be installed. If so you don't need to install it again here.

```
brew cask install virtualbox
brew cask install vagrant
```

### Install IntelliJ Ultimate

```
brew cask install intellij-idea-ultimate
```

### Install iterm2
```
brew cask install iterm2
```

### Install rbenv
```
brew install rbenv
rbenv global 2.1.0
```

