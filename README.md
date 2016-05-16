# CentOS_xfce_vnc_firefox_flash
1、查看LINUX操作系统是多少位的和版本
首先执行命令：cat /etc/redhat-release 和 getconf LONG_BIT，查看一下你的Linux版本和系统位数。
另外，也可以通过命令：uname -a 查看详细信息
附加：file /sbin/init 或者 getconf -a 均可查看系统是多少位的。

2.1 32 位系统

wget https://raw.githubusercontent.com/pzwl/CentOS64_xfce_vnc/master/x86/CentOS64_xfce_vnc.sh

sh CentOS32_xfce_vnc.sh

2.2 64 位系统
wget https://raw.githubusercontent.com/pzwl/CentOS64_xfce_vnc/master/x64/CentOS64_xfce_vnc.sh

sh CentOS64_xfce_vnc.sh
