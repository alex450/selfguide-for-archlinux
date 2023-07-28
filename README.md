# install-guide-for-archlinux
written for personal use

首先
输入archinstall
清华源
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinux/$repo/os/$arch
[archlinuxcn]
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch

上交源
Server = https://mirror.sjtu.edu.cn/archlinux/$repo/os/$arch
[archlinuxcn]
Server = https://mirrors.sjtug.sjtu.edu.cn/archlinux-cn/$arch

启用cn仓库后
pacman -Sy archlinuxcn-keyring
之后选择yay或paru作为aur助手即可
pacman -S paru

启用cn库后安装输入法
pacman -S fcitx5-chinese-addons fcitx5-git fcitx5-gtk fcitx5-qt fcitx5-pinyin-zhwiki kcm-fcitx5
paru -S fcitx5-input-support

reboot 之后ctrl+space即可开始愉快地输入汉字了
