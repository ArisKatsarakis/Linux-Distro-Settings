# Author: Katsarakis Aris
    
# Basic Installation Commands     
```
sudo apt install xmonad  libghc-xmonad-contrib-dev 
xmonad-contrib for Arch Linux Based Distros
libghc-xmonad-contrib-dev for Ubuntu/Debian based distros 
```

Also 2 following packages are needed
xterm dmenu so the final installation will be 

```
sudo apt install xmonad  libghc-xmonad-contrib-dev dmenu xterm 
```


Following Login to a xmonad session through loggin out and using xmonad 
in order to ented a terminal 
Alt+Shfit+Enter
In order to open d menu
alt+shfit+p 


Create a .xmonad directory at your root directory ~/ 

```
mkdir .xmonad/xmonad.hs
or 
mkdir .xmonad 
mv xmonad.hs ~/.xmonad

```

Alt+ Q restarts xmonad 
mod4Mask = Super Key 
mod1Mask = Alt key 


Also a libary must be Imported at first for using Spawn Ownce 
also we need to install xmobar for using a bar for our bar holders and etc 
```
sudo apt-get install xmobar
```

After installing xmobar we searching using 
sudo find / -iname xmobar to find any results in our root directory
we find the usr/share/xmobar folder 
and in there we can find an example .config file
Then we create a directory in .config directory called xmonbar