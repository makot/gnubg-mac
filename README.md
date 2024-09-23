# How to run gnubg on Mac

## Install Homebrew

## Using Homebrew, install the followings
- xquartz
- readline
- bison
- pkg-config
- libtool
- automake
- autoconf
- gtk+

## Build
```
./configure
make
sudo make install
```

or

```
./configure --prefix=$HOME/.local
make
make install
```

## Run

```
gnubg 
```

or

```
~/.local/bin/gnubg -P ~/.local/share/gnubg -w
```
