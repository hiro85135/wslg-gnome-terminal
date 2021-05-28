1. Follow the instruction
    https://github.com/microsoft/wslg
2. Install GNOME:
```powershell
   sudo apt install ubuntu-desktop gnome
```
3. Start dbus
```powershell
   sudo mkdir -p /run/dbus
   sudo dbus-daemon --system
```
4. Add these lines in ~/.bashrc
```
   export GTK_IM_MODULE=ibus
   export XMODIFIERS=@im=ibus
   export QT_IM_MODULE=ibus
```
5. Shut down wsl
```powershell
    wsl --shutdown
```
6. Start up Ubuntu and start gnome-terminal
```powershell
    gnome-terminal
```

* reference

https://github.com/microsoft/wslg

https://github.com/Microsoft/WSL/issues/2941
