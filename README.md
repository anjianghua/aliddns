# aliddns 安装

> 在服务器上安装基础组件
**CentOS:**
```shell
yum install -y wget curl cron
```
**Debian 8+/Ubuntu:**
```shell
apt install -y wget curl cron
```
> 然后下载AliDDNS脚本到你的服务器上：
```shell
wget -O /usr/sbin/AliDDNS-v2.0.sh https://ilemonrain.com/download/shell/AliDDNSv2.sh
```
> 为脚本文件加上可执行属性：
```shell
chmod +x /usr/sbin/AliDDNS-v2.0.sh
```
> 执行脚本，开始配置：
```shell
/usr/sbin/AliDDNS-v2.0.sh
```
