# install-guide-for-archlinux
written for personal use

首先
输入archinstall

设置各类选项 语言选zh_cn.utf8

完成后chroot

pacman -S wqy-microhei (也可以是别的字体)

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

设置代理
paru -S clash-for-windows-chinese

等待比较久

启动之后前往我的梯子网站复制订阅连接

7890是clash默认的端口

首先设置系统代理

例外填写localhost, 127.0.0.0/8, ::1

firefox设置 http 代理 127.0.0.1 端口7890

vscode搜索proxy 输入http://127.0.0.1:7890

git设置

git config http.proxy http://127.0.0.1:7890

git config https.proxy http://127.0.0.1:7890
