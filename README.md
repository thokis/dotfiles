# Openbox config and some scripts

This repo represents my OpenBox dotfiles and some little scripts i wrote.
To install this config of mine, simply copy the content of the repo directly into your home directory after modifying them.

# Alyways treat copying foreign files with caution!

Begin by cd into your home directory and clone this repo

    $ cd ~
    $ git clone https://github.com/thokis/dotfiles.git .thokis_dotfiles
    $ cd .thokis_dotfiles
    
Now you should be able to edit the files in the .config and .script_dir directorys. After editing the files run

    $ cp -r ~/.thokis_dotifles/* ~/
    
Now you should have a working Openbox config.

# A little introduction of my Openbox rc.xml

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
