1. Follow the instruction
    https://github.com/microsoft/wslg
2. Install GNOME:
```powershell
   sudo apt install ubuntu-desktop gnome
```
3. Add these lines in ~/.bashrc
```
   export GTK_IM_MODULE=ibus
   export XMODIFIERS=@im=ibus
   export QT_IM_MODULE=ibus
```
4. Shut down wsl
```powershell
    wsl --shutdown
```
5. Start up Ubuntu and start gnome-terminal
```powershell
    gnome-terminal
```
