# cheetsheet #
nvidia driver is broken:
- error msg: Xlib: extension "GLX" missing on display ":0
- fix: update system
  ```
  sudo apt-get update
  sudo apt-get -y dist-upgrade
  ```
  - ref: https://askubuntu.com/questions/223501/ubuntu-gets-stuck-in-a-login-loop

changing keyboard layout from command line:
``` 
loadkeys us
```
```
setxkbmap us
```
- possible location to find keymaps (us, il)
```
/usr/share/keymaps/i386/
/usr/share/kbd/keymaps/i386/
/usr/share/X11/xkb/symbols/
```
- ref: https://askubuntu.com/questions/209597/how-do-i-change-keyboards-from-the-command-line
