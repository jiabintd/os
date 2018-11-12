
**root权限**
```
sudo -i
```

**查看时间**
```
date -R
```

**校准时间(上海)**
```
cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
```

**安装wget**
```
yum -y install wget
```

**安装bbr**
```
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
chmod +x bbr.sh
./bbr.sh
lsmod | grep bbr
```


**安装v2ray**
```
bash <(curl -L -s https://install.direct/go.sh)
```
**配置v2ray协议**
```
vi /etc/v2ray/config.json
```
**重启v2ray**
```
sudo systemctl restart v2ray
```
**启动v2ray**
```
service v2ray start
```

**客户端**
```
https://www.v2ray.com/download/
```
