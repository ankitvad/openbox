# Openbox WM
This repo regroups all the config files needed to create a clean Openbox desktop. 

### Xresources for font hinting

nano  ~/.Xresources

    ! Xft settings
    Xft.dpi:        96
    Xft.antialias:  true
    Xft.rgba:       rgb
    Xft.hinting:    true
    Xft.hintstyle:  hintslight


### Color script for terminal

nano ~/.config/scripts/colors.sh
chmod +x ~/.config/scripts/colors.sh

Put an alias on your .bashrc to execute it easely.

### Openbox menu
To add title to your Openbox menu, edit the ~/.config/openbox/menu.xml and add a label parameter to the separator. Weirdly, this can't be done through the obmenu tool.

    <separator label="Title"/>
