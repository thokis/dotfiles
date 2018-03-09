## Openbox config and some scripts ##

This repo represents my OpenBox dotfiles and some little scripts i wrote.
To install this config of mine, simply copy the content of the repo directly into your home directory after modifying them.
I also provied a applications.txt, containing all applications to run my scripts. Obviously if you dont have a nVidia gpu that supports h264 encode (h264_nvenc) dont install nvidia or nvidia-utils.

## Alyways treat copying foreign files with caution! ##

Begin by cd into your home directory and clone this repo

    $ cd ~
    $ git clone https://github.com/thokis/dotfiles.git .thokis_dotfiles
    $ cd .thokis_dotfiles/home_dir
    
Now you should be able to edit the files in the .config and .script_dir directorys. After editing the files run

    $ cp -r ~/.thokis_dotifles/home_dir/* ~/
    
Now you should have a working Openbox config.

## A little introduction of my Openbox rc.xml ##

The "modkey" so to say is pretty default : Super_L or better known as the left Windows Key. It is the main key for executing shortcuts in this config. I will call it from now on W as defined in the rc.xml.

shortcut  | keyboard
------------- | -------------
Toggle Fullscreen | W-f
Close Window | W-q
Terminal | W-Return
Launcher | W-d
Filemanager | W-r
Screencapture with gpu  | W-n
Screencapture with cpu | W-i
End Screencapture | End
Screenshot | Print
Lockscreen | Scroll_lock
Lockscreen and suspend | Pause

The Volume and cmus-remote scripts only work if you have multimediakeys on your keyboard and they are recognized as XF86Audio*
Keys.

## Screenshots ##

**clean**

![picture alt](https://raw.githubusercontent.com/thokis/dotfiles/master/screens/clean.jpg)

**neofetch**

![picture alt](https://raw.githubusercontent.com/thokis/dotfiles/master/screens/clean_neofetch.jpg)

**cmus and dosbox**

![picture alt](https://raw.githubusercontent.com/thokis/dotfiles/master/screens/cmus_blood.jpg)

**lockscreen**

![picture alt](https://raw.githubusercontent.com/thokis/dotfiles/master/screens/.lock.jpg)

## Wallpaper ##

![picture alt](https://raw.githubusercontent.com/thokis/dotfiles/master/home_dir/.config/wall.jpg)
