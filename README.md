# kaga-rice


![enter image description here](https://github.com/shikikan-neko08/kaga-rice/blob/main/2021-07-17-234906_1360x768_scrot.png) 

![enter image description here](https://github.com/shikikan-neko08/kaga-rice/blob/main/2021-07-18-053443_1360x768_scrot.png)  
      
![enter image description here](https://github.com/shikikan-neko08/kaga-rice/blob/main/2021-07-16-161046_1360x768_scrot.png)      

![enter image description here](https://github.com/shikikan-neko08/kaga-rice/blob/main/2021-07-17-214858_1360x768_scrot.png)  

![enter image description here](https://github.com/shikikan-neko08/kaga-rice/blob/main/2021-07-17-234710_1360x768_scrot.png) 

**Kaga - Azur Lane (アズールレーン)**


# Details
* Font Used : Iosevka Custom (Included), Font Awesome
* GTK Theme : Magenta-GTK
* Icons     : Papirus
* OS        : Artix Linux
* Terminal  : Kitty
* Shell     : zsh with [Starship Prompt](https://starship.rs/) 
* Bar       : Polybar
* Icon      : [Papirus Folders (Install it from here)](https://github.com/PapirusDevelopmentTeam/papirus-folders)

# Dependecies
 * [Clearine (Power Menu)](https://github.com/okitavera/clearine)
 * [Rofi](https://github.com/davatorium/rofi)
 * [kitty](https://github.com/kovidgoyal/kitty)
 * [i3-gaps](https://github.com/Airblader/i3)
 * [Polybar](https://github.com/polybar/polybar)
 * [betterlockscreen](https://github.com/pavanjadhaw/betterlockscreen)    
 * nitrogen 
 
 Some of this packages might not be available on your distro's repository, please refer to your distro package manager.     
 If you are using Arch Linux Based Distro (Alter Linux, Manjaro, EndeavourOS, etc...), You can use AUR For Those Packages.

# Installation

**Important : Make sure to backup your existing configuration files before installing to avoid loss**     

* Install the dependencies
* Clone this repository
* Install [Starship Prompt](https://starship.rs/)
* install the required fonts by copying .fonts directory to your home directory      
> **Note : for Source han and ttf-font-awesome, install it from your repository**          
> **Arch : sudo pacman -S adobe-source-han-sans-jp-fonts ttf-font-awesome**
* copy all .config files to your .config directory
* copy all .themes, .icons folders to your home directory
* install oh-my zsh then manually then move .zshrc into your home directory
* install pywal and move .cache/wal into your .cache directory
* install [vim-plug](https://github.com/junegunn/vim-plug)
* copy vimrc into .vim directory
* manually install the plug by opening vimrc using vim then instal the plugin using :PlugInstall   
* Set the wallpaper using nitrogen  
* Set Lockscreen Wallpaper using this command      
> betterlockscreen -u /path/to/wallpaper_kaga.png

To apply The GTK Theme and icons, you can use LXappearance    


# Notes
* If you are installing this on systemd , don't forget to change the loginctl
 command to systemctl on clearine.conf and polybar config
* Polybar is disabled by default. to enable it run "launchbar" if you are on zsh shell. or uncomment the launch.sh on i3/config

#Changelog
**v0.9**
Initial version, with oh-my-zsh prompt not released on github
**v0.9.5**
Initial version, with starship prompt
**v1.0 (current)**
Version released to github, with polybar
