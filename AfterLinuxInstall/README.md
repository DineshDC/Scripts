# Scripts for installing all neccessay software to start developing(Ubuntu/Debian/LinuxMint/LinuxLite)

> **Note**

> Open Terminal
```
Ctrl+Alt+T # Shortcut to open terminal
```
> Make executable the script using following command
```
chmod +x InstallAll_deb.sh
```
> To run Type
```
 ./InstallAll_deb.sh
```

# Must  for c/c++
```sh
# '-y' is given so that it should not ask always yes/no for installation
sudo apt -y install vim # vim editor reccommended for terminal based editor
apt -y install ctags  # for vim editor tags automation
apt -y install gcc    # gcc compiler for c
apt -y install g++    # g++ compiler for c++
apt -y install clang  # clang compiler
```
# For Atom text Editor (Most Hackable editor) for 32 bit linux
```
#For 32 bit linux
sudo add-apt-repository ppa:webupd8team/atom

#Type in password when it prompts and hit Enter.
#Update system package index and install the text editor via command:

sudo apt update; sudo apt install atom
````

# Qt sdk for GUI development in C++/QML
```
apt -y install qt-sdk  # install Qt creator + qmake latest vesrion
```

# Optional software
```
apt -y install emcas  # emacs GNU text Editor
```
