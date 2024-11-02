<pre>
     __       __    ___ __ __             
 .--|  .-----|  |_.'  _|__|  .-----.-----.
 |  _  |  _  |   _|   _|  |  |  -__|__ --|
 |_____|_____|____|__| |__|__|_____|_____|
                                          
</pre>
---
dotfiles gw saat ini di Arch Linux (32-bit)
Tutorial install Arch Linux (32-bit) in <a href="https://fnlqxz.my.id/blog/posts/panduan-install-arch-linux.html">di sini</a>, connect internet dulu pake Network Manager <code>nmcli device wifi connect "Nama SSID" password passphrase</code>
<br><br><br>
<h4>catatan</h4>
Setelah install arch linux upgrade dulu <code>pacman -Syu</code>, abis itu install dulu ini dengan <code>root</code> user
<pre>
pacman -S xorg-server xorg-init xorg-xrandr xorg-xsetroot
pacman -S xorg-xinit
pacman -S xorg-xfd
</pre>
Mungkin bakalan ada error pas mau <code>startx</code>, solusinya :
<pre>
pacman -Syu xterm
</pre>
Install beberapa aplikasi yang di butuhin aja, misal :
<pre>
pacman -S firefox
pacman -S thunar
pacman -S mpv
pacman -S git
pacman -S wget
pacman -S feh
pacman -S NetworkManager
pacman -S nano
pacman -S vim
pacman -S pipewire pipewire-pulse
pacman -S pavucontrol
</pre>
<h4>system information</h4>
System information pake <a href="https://github.com/dylanaraps/pfetch">ini</a>
<h4>screenshoot</h4>
<img src="https://raw.githubusercontent.com/febnug/dotfiles/main/screenshoot/ss.png"/>
<h4>grub theme</h4>
untuk tema grub pake <a href="https://github.com/Lxtharia/minegrub-theme">minegrub theme</a>
<h4>shell promt</h4>
<p>Pake <a href="https://starship.rs/">ini</a>, cara installnya <a href="https://starship.rs/guide/">di sini</a></p>
<h4>font pake <a href="https://drive.google.com/file/d/11S6FTcb_Y-Z4BdvE7Vif5aPFrVNOzP8V/view?usp=sharing">ini</a></h4>
