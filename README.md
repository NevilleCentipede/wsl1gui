# wsl1gui
Tutorial to run a gui DE such as xfce and lxde

1. so first of all install both xfce4 and lxde
2. Install some fonts
3. Install xorg and Xephyr
4. Install a X server for your windows.
5. Do export DISPLAY=:0
6. run these commands on your preffered distro. Mine is void as it is stable.
Xephyr -ac -screen 1024x768 :1 & DISPLAY=:1 startlxde
Xephyr -ac -screen 1024x768 :1 & DISPLAY=:1 startxfce4

edit these screen resulutions according to your needs.

Note : for void and some rolling release distros, it is good to install the lxde and xfce4 for fonts related issues.
