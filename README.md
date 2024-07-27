# dotfiles
dotfiles gw saat ini di Arch Linux (32-bit)
Tutorial install Arch Linux (32-bit) in <a href="https://fnlqxz.my.id/blog/posts/panduan-install-arch-linux.html">di sini</a>
<br><br><br>
Catetan :
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
pacman -S vlc
pacman -S git
pacman -S wget
pacman -S feh
</pre>
System information pake <a href="https://github.com/dylanaraps/pfetch">ini</a>
