## Thunar  
  
Thunar is a modern file manager  
  
requires:    
apt: ```apt install thunar```  
yum: ```yum install thunar```  
pacman: ```pacman -S thunar```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/Thunar/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/Thunar" "$HOME/.config/Thunar.bak"
git clone https://github.com/dfmgr/Thunar "$HOME/.config/Thunar"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/Thunar" target="_blank">Thunar wiki</a>  |  
  <a href="https://docs.xfce.org/xfce/thunar/start" target="_blank">Thunar site</a>
</p>  
