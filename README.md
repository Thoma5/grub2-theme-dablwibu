# grub2-theme-dablwibu
DArkBLueWIthBUbbles
A minimalistic, yet beautiful grub2 theme

![Screenshot](https://github.com/Thoma5/grub2-theme-dablwibu/blob/master/screenshot.png?raw=true)
## Installation
Create an new folder in your grub theme folder (e.g. /boot/grub/themes/dablwibu/) where you put in all the content of this repository. You may have to chown it to root:root. 
In your /etc/default/grub you have to set the following line:

    GRUB_THEME="/boot/grub/themes/dablwibu/theme.txt"

Afterwards run the following command as root (make sure you specify the correct path, since it depends on where you've installed grub)

    grub-mkconfig -o /boot/grub/grub.cfg

## Misc
If you want see icons in your grub menu, you need to put 32px png Icons into the icons folder. You will get the best experience if the icon itself is only 20px large and centered in the 32px box and white with transparent background. The icon pngs need to be named after the classes of the grub menu entries (see your grub.cfg). Some examples: arch.png ubuntu.png windows.png ...
I don't include those icons myself since those logos are copyrighted or protected by special trademarks. 
It shouldn't be too hard to find matching one yourself ;)
## Used as template
https://github.com/KDE/breeze-grub
## Inspired by
https://github.com/Se7endAY/grub2-theme-vimix

https://github.com/shvchk/poly-light
