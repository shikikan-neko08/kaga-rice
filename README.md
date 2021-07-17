# kaga-rice

![enter image description here](https://github.com/shikikan-neko08/kaga-rice/blob/main/2021-07-16-161046_1360x768_scrot.png)


# Details
* Font Used : Iosevka Custom
* GTK Theme : Magenta-GTK
* Icons     : Papirus
* OS        : Artix Linux
* Terminal  : Kitty
* Bar       : Polynar

# Installation
* Clone this repository
* install the required fonts
* copy all .config files to your .config directory
* copy all .themes, .icons folders to your home directory
* install oh-my zsh then manually then move .zshrc into your home directory
* install pywal and move .cache/wal into your .cache directory
* install [vim-plug](https://github.com/junegunn/vim-plug)
* copy vimrc into .vim directory
* manually install the plug by opening vimrc using vim then instal the plugin using :PlugInstall

# Notes
* If you are installing this on systemd , don't forget to change the loginctl
 command to systemctl on clearine.conf and polybar config
* Polybar is disabled by default. to enable it run "launchbar" if you are on zsh shell. or uncomment the launch.sh on i3/config
