# 全自动一键网络重装脚本（DD脚本）
安装重装系统的前提组件：
Debian/Ubuntu:


apt-get install -y xz-utils openssl gawk file wget screen && screen -S os
RedHat/CentOS:


yum install -y xz openssl gawk file glibc-common wget screen && screen -S os
如果出现异常，请刷新Mirrors缓存或更换镜像源。

RedHat/CentOS:


yum makecache && yum update -y
Debian/Ubuntu:


apt update -y && apt dist-upgrade -y
 

DD 命令：

wget --no-check-certificate -O NewReinstall.sh https://git.io/newbetags && chmod a+x NewReinstall.sh && bash NewReinstall.sh
