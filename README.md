# VPN-Route
Linux 使用的VPN路由表，用于分流国内外流量，国内网络走网关，国外网络走VPN

ip-pre-up and ip-down 用于路由自动设置，ip-pre-up 放在/etc/ppp/文件夹中，ip-down放在/etc/ppp/ip-down/文件夹中

chnroutes.py是可以自动生成ip-pre-up和ip-down的python脚本，这个脚本可以兼容mac，linux，openvpn。原脚本来自jimmyxu，不过已经很久没有更新了。linux的OLDGW获取有点问题，稍微修改了一下，现在可以使用了。
