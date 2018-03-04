<div align="center">

### CLI utility for autogenerating .gitignore files to STDOUT

[![GitHub release](https://img.shields.io/github/release/jakewmeyer/Brewfile-Generator.svg)]()
[![Build Status](https://travis-ci.org/jakewmeyer/Brewfile-Generator.svg?branch=master)](https://travis-ci.org/jakewmeyer/Brewfile-Generator)

</div>

## Purpose
* Written to provide an easy way of generating a [brewfile](https://github.com/Homebrew/homebrew-bundle) from currently installed brews/casks
* Generating brewfiles makes it easy to migrate to a new mac without forgetting [Homebrew](https://brew.sh/) packages

## Install / Setup
```bash
$ gem install brewfile
```

## Usage
### Overwrite existing brewfile
```bash
$ brewfile > ~/brewfile
```

### Append existing brewfile
```bash
$ brewfile >> ~/brewfile
```

### Install brews/casks from brewfile
```bash
$ cd ~
$ brew bundle
```

### Sample Output
```ruby

tap 'caskroom/cask'

# Core Homebrew
brew 'autoconf'
brew 'automake'
brew 'bats'
brew 'bdw-gc'
brew 'cmake'
brew 'coreutils'
brew 'crystal-lang'
brew 'curl'
brew 'dosbox'
brew 'findutils'
brew 'fish'
brew 'gdbm'
brew 'geo'
brew 'gettext'
brew 'git'
brew 'gmp'
brew 'go'
brew 'gradle'
brew 'grep'
brew 'gzip'
brew 'icu4c'
brew 'jq'
brew 'libevent'
brew 'libffi'
brew 'libgpg-error'
brew 'libidn2'
brew 'libksba'
brew 'libogg'
brew 'libpng'
brew 'libtool'
brew 'libunistring'
brew 'libvorbis'
brew 'libyaml'
brew 'libzip'
brew 'llvm'
brew 'mas'
brew 'maven'
brew 'nasm'
brew 'nginx'
brew 'nmap'
brew 'node'
brew 'oniguruma'
brew 'openssl'
brew 'openssl@1.1'
brew 'pcre'
brew 'pcre2'
brew 'perl'
brew 'pkg-config'
brew 'python'
brew 'python3'
brew 'readline'
brew 'redis'
brew 'ruby'
brew 'sdl'
brew 'sdl_net'
brew 'sdl_sound'
brew 'sqlite'
brew 'terraform'
brew 'tldr'
brew 'tmux'
brew 'unrar'
brew 'vim'
brew 'w3m'
brew 'wget'
brew 'xz'

# Cask Apps
cask 'docker-toolbox'
cask 'google-chrome'
cask 'hyper'
cask 'java'
cask 'robo-3t'
cask 'sequel-pro'
cask 'slack'
cask 'spotify'
cask 'vagrant'
cask 'virtualbox'
cask 'wireshark'

```