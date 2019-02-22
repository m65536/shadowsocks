shadowsocks搭建和使用

# 在Linux上搭建shadowsocks服务
* 安装 [https://github.com/shadowsocks/shadowsocks/tree/master](https://github.com/shadowsocks/shadowsocks/tree/master)
* 启动
````aidl
sudo ssserver -p 443 -k password -m aes-256-cfb --user nobody -d start
````
* 停止
````aidl
sudo ssserver -d stop
````
* 日志
````aidl
sudo less /var/log/shadowsocks.log
````


# windowns 安装客户端
* [https://github.com/shadowsocks/shadowsocks-windows/releases](https://github.com/shadowsocks/shadowsocks-windows/releases)

# andriod 安装客户端
* [https://github.com/shadowsocks/shadowsocks-android/releases](https://github.com/shadowsocks/shadowsocks-android/releases)

# ios 安装客户端
* [https://github.com/herzmut/shadowsocks-iOS](https://github.com/herzmut/shadowsocks-iOS)
* SuperRocket

# mac安装客户端
* [https://github.com/shadowsocks/ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)

# Linux 安装 shadowsocks 客户端
* [https://segmentfault.com/a/1190000011224139](https://segmentfault.com/a/1190000011224139)
* [CentOS命令行使用shadowsocks代理的方法](https://blog.csdn.net/yanzi1225627/article/details/51121507)
* [命令行中使用shadowsocks搭梯子](https://daryl.moe/2016/03/26/%E5%91%BD%E4%BB%A4%E8%A1%8C%E4%B8%AD%E4%BD%BF%E7%94%A8shadowsocks%E6%90%AD%E6%A2%AF%E5%AD%90/)
* 运行
````aidl
sslocal -c /etc/shadowsocks.json -d start 
sslocal -c /etc/shadowsocks.json -d stop 

privoxy /usr/local/etc/privoxy/config
````

# 其他
官方客户端:https://shadowsocks.org/en/download/clients.html
### Ubuntu安装
```

```
