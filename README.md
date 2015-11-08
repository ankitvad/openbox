# Openbox WM
This repo regroups all the config files needed to create a clean Openbox desktop. 

![OpenBox desktop](dok.png)

### .config folder
* _tint2rc_: Tint2 panel configuration
* _conkywine_: Conky inline configuration
* _compton.conf_: Compton configuration
* _autostart_: OB autostart file
* _menu.xml_: OB menu configuration
* _rc.xml_: OB setting and shortcuts
* _dmenu-bind.sh_: Dmenu shortcut launcher

### Openbox folder
* _.bashrc_: Terminal configuration
* _.Xresources_: Font hinting


### OB menu note:
To add title to your Openbox menu, edit the ~/.config/openbox/menu.xml and add a label parameter to the separator. Weirdly, this can't be done through the obmenu tool.

    <separator label="Title"/>
