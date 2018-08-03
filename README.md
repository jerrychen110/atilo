# Atlio
A bash script to install linux on termux  
在Termux安装Linux的bash脚本

## Download/下载
```
pkg in wget 
git clone https://github.com/jerrychen110/atilo
chmod +x ~/atilo
```

## Usage/使用方法
```
./atilo [option/选项] [parameter/参数]

arch           Install/安装 archlinux
fedora         Install/安装 fedora
alpine         Install/安装alpine
aosc           Install/安装aosc
ubuntu         Install/安装ubuntu
debian         Install/安装debian
kali           Install/安装kali
-r             Deletee installed Linux/删除已安装的Linux

# e.g
./atilo kali
# 等待安装/Wait
```

1、修改无法安装kali的bug
2、修改gpg public key失效的问题

fork from:https://github.com/YadominJinta/atilo