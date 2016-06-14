#!/bin/bash
#
# speakBook v0.0.1
#
# Tested on Ubuntu 14.04 LTS

clear
## Pitch
echo "Welcome to speakBook 0.0.1"
echo ""
echo "Turn novels, business reports etc into audiobooks on-the-fly."
echo ""
### Install packages

sudo apt-get install espeak
sudo apt-get install xsel

## Configure key-board shortcut

gsettings set org.gnome.settings-daemon.plugins.media-keys.custom-keybinding:/org/gnome/settings-daemon/plugins/media-keys/custom-keybindings/custom0/ name 'espeak'
gsettings set org.gnome.settings-daemon.plugins.media-keys.custom-keybinding:/org/gnome/settings-daemon/plugins/media-keys/custom-keybindings/custom0/ command 'bash -c "xsel | espeak"'
gsettings set org.gnome.settings-daemon.plugins.media-keys.custom-keybinding:/org/gnome/settings-daemon/plugins/media-keys/custom-keybindings/custom0/ binding '<Super>r'

## Testing
echo ""
echo "Successfully Installed [=====================================>] 100%"
echo ""
echo "Usage: Highlight any text on the screen and press the keys super + R"
echo "Press any key to finish setup......................................."
read

