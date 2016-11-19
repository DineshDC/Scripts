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
sudo apt install -y  vim # vim editor reccommended for terminal based editor
sudo apt install -y git # Git version control system
apt install -y ctags  # for vim editor tags automation
apt install -y gcc    # gcc compiler for c
apt install -y g++    # g++ compiler for c++
apt install -y clang  # clang compiler
apt install -y cppcheck #check for cpp memory leaks and overflow
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
apt install -y qt-sdk  # install Qt creator + qmake latest vesrion
```

# Optional software
```
apt install -y emcas  # emacs GNU text Editor
```
