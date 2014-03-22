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

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi
install homebrew/dupes/grep
install josegonzalez/homebrew-php/php53
install josegonzalez/homebrew-php/php54
install josegonzalez/homebrew-php/php55

# Install other useful binaries
install ack
install autoconf
install pv
install git
install imagemagick --with-webp
install mongodb
install mysql
install node
install redis
install rename
install ssh-copy-id
install tree
install webkit2png
install wget
install zlib

# Remove outdated versions from the cellar
cleanup
