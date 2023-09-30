# Mangopi-MQ-Quad-srv
Lightweight version of Debian Bullseye [kernel 5.16.17] for MangoPi MQ-Quad (ARM H616)

![alt text](https://mangopi.org/_media/img_0406_2048.jpg?w=800&tok=561923)

## Downloads
<https://github.com/showsoft/Mangopi-MQQuad-srv/blob/master/Debian_bullseye_srv_linux5.16.17_mqquad_mangopi.img.xz>

### Credentials:
user: orangepi
pass: orangepi

**SSH Enabled**  

**Please change this as soon as you can!**

## Install
- Burn image file to sd card (at least 16GB)
- If you have an usb-c Eth Port shh to **mangopi.lan**
- or Plug monitor and keyboard and log in
- Connect to wifi AP: **sudo nmcli device wifi connect YOURSSID password YOURPASS**
- Extend rootfs with the script **extend_rootfs**
- Enjoy it!

## After install
Open **~/.bashrc** in text editor and uncomment line:
**#force_color_prompt=yes**
then add this to the end of file
**export PATH="/sbin:$PATH"**
save then execute **source ~/.bashrc**
