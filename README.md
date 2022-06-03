# ubuntu-post-installation

A post installation script made for Ubuntu 20.04 and 22.04.
Setting themes for various services and download relevant software.

To begin with, you need to make the scripts executable.
```bash
cd ubuntu-post-installation && chmod +x install settings
``` 
The start the [install](installation):
```bash
sudo ./install 
```
The installation script will call the other script, [settings](settings), when needed.  
  
Once the installation is complete, You will be asked wether you want to remove the temporary files or not. Answering yes to that question will remove the entire ubuntu-post-installation folder.
  
##### Printscreen Ubuntu 22.04
[![screen.png](https://i.postimg.cc/W3LpKgT2/screen.png)](https://postimg.cc/Z9Hhv9Wg)

***Note.*** *To use dash-to-panel extension you need to logout and back in again. Also, you need to edit the apperence manual. No custom icons are set for 20.04.*

## Software installed
- [vim](https://www.vim.org/download.php) - My favorite fexteditor
- [Terminator](https://terminator-gtk3.readthedocs.io/en/latest/) - Terminal emulator
- [texlive-extra](https://launchpad.net/ubuntu/+source/texlive-extra) - Needed for LaTeX
- [texlive-formats-extra](https://packages.ubuntu.com/bionic/texlive-formats-extra) - Needed for LaTeX
- [texlive-lang-english](https://packages.debian.org/sid/texlive-lang-english) - Needed for LaTeX
- [texstudio](https://www.texstudio.org/) - LaTeX editor
- [gnome-tweaks](https://gitlab.gnome.org/GNOME/gnome-tweaks) - For tweaking gnome settings
- [gnome-shell-extensions](https://extensions.gnome.org/) - For tweaking gnome extensions
- [gnome-shell-extension-dash-to-panel](https://extensions.gnome.org/extension/1160/dash-to-panel/) - A gnome shell extension
- [Pinta](https://www.pinta-project.com/) - Simple image editing

##### Snaps installed
- [Codium](https://github.com/VSCodium/vscodium) - Texteditor made for script and programming
- [Discord](https://discord.com/) - Communication platform
- [Telegram](https://telegram.org/) - Communication platform

## Color themes
- [Nordic "Gnome desktop"](https://www.gnome-look.org/p/1267246) - Gnome theme
- [Nordic "Firefox theme"](https://github.com/EliverLara/firefox-nordic-theme) - FireFox theme
