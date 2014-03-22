# Eric Clemmons' Dotfiles

> Fork of [Mathias's dotfiles](https://github.com/mathiasbynens/dotfiles) primarily for Node/PHP development. [Compare the differences](https://github.com/ericclemmons/dotfiles/compare/mathiasbynens:master...ericclemmons:master).


Dotfiles (`~/.*`) are environment & application configuration files.

## Installation

First, we need to pull down this repository & sync it's dotfiles into our home (`~/`) directory.

### With Git

Clone this repository into `~/.dotfiles`.

*This should prompt you to install Xcode Tools.*

```bash
$ git clone https://github.com/ericclemmons/dotfiles.git .dotfiles
$ cd .dotfiles
$ ./install
```

### Without Git

To install these dotfiles without Git:

```bash
cd; curl -#L https://github.com/ericclemmons/dotfiles/tarball/master | tar -xzv --strip-components 1 --exclude={README.md,install,LICENSE-MIT.txt}
```

To update later on, just run that command again.

### Updating

```bash
$ ./install
```

Alternatively, to update while avoiding the confirmation prompt:

```bash
set -- -f; ./install
```

## Setup OS X

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
$ source ~/.osx
```

## Install Homebrew formulae

These are housed in `~/Brewfile`.

```bash
$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
$ brew bundle
```

## Install native apps with `brew cask`

You could also install native apps with [`brew cask`](https://github.com/phinze/homebrew-cask):

```bash
$ source ~/.cask
```

## Author

[Eric Clemmons](https://github.com/ericclemmons)
