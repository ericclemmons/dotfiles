# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install some other useful utilities like `sponge`
install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash
install bash-completion

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
tap homebrew/dupes
install vim --override-system-vi
install homebrew/dupes/grep

# Databases
install mongodb
install mysql
install redis

# Node
install node --without-npm
install chromedriver
install phantomjs
install webkit2png

# PHP
tap homebrew/versions
tap josegonzalez/homebrew-php
install php54
install php55
install composer

# Install other useful binaries
install ack
install autoconf
install git
install hub
install imagemagick --with-webp
install rename
install ssh-copy-id
install tree
install wget
install zlib

# Remove outdated versions from the cellar
cleanup
