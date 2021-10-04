# Installing Python on macOS
This quick guide will show how to install Python 3 on macOS.
## Installing brew
First we'll install [[https://brew.sh/][brew]] which is "the missing Package Manager for macOS".
Start by opening the terminal, which can be found in Applications/utilities/terminal.app or Programmer/Hjælpeprogrammer/terminal.app.
Insert the following command and press enter:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
## Installing Python3
After installing brew, we're now ready to install Python3. Input the following command in your terminal and press enter:
```
brew install python3
```
## Confirming the installation
After installing python3 using brew, we can confirm that we have Python3 installed by running the following command in the terminal
```
python3 --version
```
This should output Python 3.8.2 (or higher). If it works you're ready and if it doesn't please reach out and we'll fix it before the lecture.
## Installing pip packages
Later during the course we will need to install packages to use with Python3.
There are tons of packages and they can be installed using the following command:
```
pip3 install <package-name>
```
Instead of <package-name>, you can try installing something like `numpy` or `pandas`.
