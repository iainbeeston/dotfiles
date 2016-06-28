# Iain's dotfiles

These are the dotfiles I use. Symlink them into place to use them.

## Extras

### Ubuntu

Setup MacBook Pro broadcom wifi drivers

    sudo apt install bcmwl-kernel-source

Install mbpfan, to enable MacBook fan control

    wget https://github.com/dgraziotin/mbpfan/archive/master.zip

Install tlp, to enable better laptop power savings

    sudo apt install tlp

Remap caps lock and command to control

    gsettings set org.gnome.desktop.input-sources xkb-options "['ctrl:nocaps', 'altwin:ctrl_win']"
