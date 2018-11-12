yum -y install wget
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
chmod +x bbr.sh
./bbr.sh
运行下面代码检测是否成功开启bbr功能，
lsmod | grep bbr

出现 tcp_bbr           
