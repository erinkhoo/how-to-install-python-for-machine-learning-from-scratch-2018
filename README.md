# How to install Python 3 for 🎶 machine learning 🎶 from scratch 2018
Are you reading super nerdy but missing step install instructions how-to's online to get the latest Python setup on Mac OSX? 

Holla at your boy!

<h2>Steps</h2>

<h4>Open Terminal</h4>
https://en.wikipedia.org/wiki/Terminal_(macOS)

</h4>Install Homebrew</h4>
https://brew.sh/
Command: "/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
"

Place the Homebrew directory at the top og the PATH
Command: "nano ~/.bash_profile" THEN "export PATH=/usr/local/bin:$PATH"
Save by holding CONTROL (^ looking key) AND "o" THEN press return
Exit by holding CONTROL AND "x"
Once back in Terminal "source ~/.bash_profile" to complete bash_profile move

#Coding is Baller

Check Homebrew is ready
Command: "brew doctor"

#Your system is ready to brew.
(you might get a warning, in which case you need to run "brew update"

<h4>Install Python 3</h4>
https://docs.python.org/3/
Command: "brew install python3"

pip (Python package manager) comes with Python3, to use you'll need to use "pip3"

<h4>Install NumPy for the craic</h4>
http://www.numpy.org/
Command: pip3 install numpy

#Such Hacker
