# Linux goodies
这里整理了一些我自己常用的好的Linux软件，分享给大家。
环境：Thinkpad X230，Archlinux，CK内核

* aria2：强大的下载工具，支持多协议
* [webui-aria2](https://github.com/ziahamza/webui-aria2)： aira2网页界面，功能丰富
* blueman：蓝牙管理器
* ~~[infinality](https://bohoomil.com/)：字体渲染优化，提供Archlinux的repo。[Wiki](https://wiki.archlinux.org/index.php/Infinality)~~
* compton：窗口过渡管理器
* [electronic-wechat](https://github.com/geeeeeeeeek/electronic-wechat)：使用[electron](https://github.com/electron/electron)编写的微信客户端，AUR包：electronic-wechat-git
* fcitx：国人开发的中文输入法，支持五笔拼音（这对我很重要）
* [arc-theme](https://github.com/horst3180/arc-theme)：个人比较喜欢的GTK主题，AUR包：gtk-theme-arc-git
* i3-wm：平铺式窗口管理器，小巧精致，Geek最爱
* [i3-lock-fancy](https://github.com/meskarune/i3lock-fancy)：美化版i3锁屏，[截图](https://raw.githubusercontent.com/meskarune/i3lock-fancy/master/screenshot.png)
* lightdm：小巧的登录管理器
* [linux-ck](https://wiki.archlinux.org/index.php/linux-ck)：使用[BFS调度器](http://ck.kolivas.org/patches/bfs/)的Linux内核，针对多线程进行优化，实际测试性能提升明显
* lxapperance：GTK外观设置
* lxrandr：xrandr的GUI界面，多屏幕管理
* [MEOW](https://github.com/renzhn/MEOW)：GO语言编写的HTTP代理软件，可以使用Shadowsocks作二级代理
* [moka-icon-theme](https://github.com/snwh/moka-icon-theme)：漂亮的GTK图标包，AUR包：moka-icon-theme-git
* [musicbox](https://github.com/darknessomi/musicbox)：网易云音乐的命令行版本，又是Geek最爱，Archlinuxcn的Repo收录了该软件包
* [nerd-fonts](https://github.com/ryanoasis/nerd-fonts)：添加Powerline、Glyph Icon等符号的常用字体包
* psd：profile sync daemon，将浏览器缓存文件移动到tmpfs中以减少物理磁盘的读写，同时提高运行速度，[Wiki](https://wiki.archlinux.org/index.php/Profile-sync-daemon)
* pdnsd：本地DNS服务器，通过强制修改DNS记录的TTL值（一周甚至更长），加速DNS查询
* pacaur：AUR包管理，替代yaourt，Archlinuxcn的repo中有收录
* parcellite: 剪贴板管理器，可以保存历史
* [powerpill](https://wiki.archlinux.org/index.php/powerpill)：实现了pacman的多线程下载，后端使用aria2
* [remarkable](https://github.com/jonschlinkert/remarkable)：好用的Markdown编辑器
* [rofi](https://davedavenport.github.io/rofi/)：dmenu的替代者，可以通过脚本实现自定义菜单
* [rofi-tools](https://github.com/okraits/rofi-tools)：一些用rofi实现的脚本，如电源菜单
* screenfetch：很酷炫的命令行欢迎界面
* supervisor：进程管理器，常用开设置开机启动程序
* [teiler](https://github.com/carnager/teiler)：屏幕截图&录像工具（需安装rofi），AUR包：teiler-git
* tmux：著名的Linux终端管理程序，不多介绍
* tsocks：使所有程序都能使用SOCKS代理的小工具
* volumeicon：托盘音量调节程序
* zsh：bash的替代品，功能强大

下面是几个非常有用的Archlinux Repo：

* [Archlinuxcn](https://www.archlinuxcn.org/archlinux-cn-repo-and-mirror/)：Archlinux中文社区仓库
* [repo-ck](http://repo-ck.com/)：CK内核仓库
* ~~[infinality](https://bohoomil.com/#)：infinality仓库~~
