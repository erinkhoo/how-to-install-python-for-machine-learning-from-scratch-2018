# How to install Python 3 for 🎶 machine learning 🎶 from scratch 2018
Are you reading super nerdy but missing step install instructions how-to's online to get the latest Python setup on Mac OSX? 

Holla at your boy!

# Steps

## [Open Terminal](https://en.wikipedia.org/wiki/Terminal_(macOS))
*Terminal is how any self respecting nerd interacts with the Internet*

## [Install Homebrew](https://brew.sh/)
*Homebrew is the long lost package manager for Mac*

Command:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)
```

Place the Homebrew directory at the top of the PATH

Command:
```
nano ~/.bash_profile
```
- THEN inside this little weird GNU type
```
export PATH=/usr/local/bin:$PATH
```
- Save by holding CONTROL (^ looking key) AND "o"
- THEN press return key
- Exit by holding CONTROL AND "x"
- Once back in Terminal
Command:
```
source ~/.bash_profile
```
to complete the bash_profile move

> Installing is Baller

- Check Homebrew is ready
Command:
```
brew doctor
```

> Your system is ready to brew.

*you might get a warning, in which case you need to*

Command:
```
brew update
```

## [Install Python 3](https://docs.python.org/3/)
Command:

```
brew install python3
```

*pip (Python package manager) comes with Python3, to use you'll need to use "pip3"*

## [Install NumPy for the craic](http://www.numpy.org/)
Command:

```
pip3 install numpy
```

# :shipit:
