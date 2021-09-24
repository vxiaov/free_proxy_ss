# 说明

分享来自互联网上的shadowsocks(SS)/ShadowsocksR(SSR)/V2ray(vmess)代理

定期更新，每次分享少量可用代理,偶尔出现不可用也是有可能的。

欢迎大家Star !

可以订阅 [@free_proxy_001](https://t.me/free_proxy_001) Telegram电报频道，这里会定期发布可用代理。

## Clash订阅配置(新增)
> 小猫咪Clash提供了远程自动更新结点的功能，非常容易使用。因此这里也提供了一份远程订阅地址。


配置文件下载：
- GitHub原始链接(可能下载失败)： https://raw.githubusercontent.com/learnhard-cn/free_proxy_ss/main/clash/config.yaml
- 使用CDN加速链接(推荐)： https://cdn.jsdelivr.net/gh/learnhard-cn/free_proxy_ss@main/clash/config.yaml


### Clash订阅节点更新地址(每小时更新)
> 代理节点包含ss/ssr/vmess,均来源于网络

- Clash订阅地址(使用CDN链接,有延迟): https://cdn.jsdelivr.net/gh/learnhard-cn/free_proxy_ss@main/clash/clash.provider.yaml
- Clash订阅地址(原地址，需要通过代理访问): https://raw.githubusercontent.com/learnhard-cn/free_proxy_ss/main/clash/clash.provider.yaml

### Linux客户端使用方法:
```
# 以配置目录为`~/clash`为例
mkdir ~/clash

# 下载基础配置文件
wget -O ~/clash/config.xml -c https://cdn.jsdelivr.net/gh/learnhard-cn/free_proxy_ss@main/clash/config.yaml

# 启动clash客户端
clash-cli -d ~/clash

```

正常情况下输出内容为：
```
INFO[0000] Start initial provider provider01            
INFO[0002] Start initial provider provider02            
INFO[0002] HTTP proxy listening at: :7890               
INFO[0002] SOCKS5 proxy listening at: :1080             
INFO[0002] RESTful API listening at: 127.0.0.1:9090 
```
如果看到上面信息，就说明已经正确下载了远程订阅地址的配置信息了，默认设置是一小时更新一次(100+可用结点)。

小猫咪客户端下载地址：
- Arm路由器(斐逊K3可用-Armv5): [clash premium](https://github.com/Dreamacro/clash/releases/tag/premium)
- 斐讯K3路由器梅林AM380固件可用的Clash插件： [Clash for meilin 380](https://github.com/learnhard-cn/clash)
- openwrt固件可用KoolClash插件: [Koolshare-Clash](https://github.com/SukkaW/Koolshare-Clash)
- Linux/Win/Mac : [官方Clash](https://github.com/Dreamacro/clash/releases/latest)
- Android客户端 : <a href="https://play.google.com/store/apps/details?id=com.github.kr328.clash"><img width="200px" alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png"/></a> or [Releases](https://github.com/Kr328/ClashForAndroid/releases)

## 客户端
> 客户端工具很多，为安全期间尽量从Github、GooglePlay等平台下载安装包。


| 代理类型| PC端-Windows| PC端-MacOS| PC端-Linux| 移动端-Android| 移动端-iOS|
|:---|:---|:---|:---|:---|:---|
| ss| [shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases),[客户端地址列表](https://shadowsocks.org/en/download/clients.html)| [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG/releases/),[客户端地址列表](https://shadowsocks.org/en/download/clients.html)| [客户端地址列表](https://shadowsocks.org/en/download/clients.html)| [客户端地址列表](https://shadowsocks.org/en/download/clients.html)| [客户端地址列表](https://shadowsocks.org/en/download/clients.html)|
| ssr| [SSR-native版本-跨平台](https://github.com/ShadowsocksR-Live/shadowsocksr-native/releases/latest)| [SSR-native版本-跨平台](https://github.com/ShadowsocksR-Live/shadowsocksr-native/releases/latest)| [SSR-native版本-跨平台](https://github.com/ShadowsocksR-Live/shadowsocksr-native/releases/latest)| [SSR安卓-个人维护的版本](https://github.com/HMBSbige/ShadowsocksR-Android/releases)| [shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118),[potatso-lite](https://apps.apple.com/us/app/potatso-lite/id1239860606)|
| v2ray| [v2rayN-支持ss/v2ray](https://github.com/2dust/v2rayN/releases),[Qv2ray客户端](https://github.com/Qv2ray/Qv2ray/releases),<a href="https://play.google.com/store/apps/details?id=com.v2ray.ang"><img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" width="165" height="64" /></a>| [v2ray官方客户端](https://github.com/v2fly/v2ray-core/releases),[Qv2ray客户端](https://github.com/Qv2ray/Qv2ray/releases)| [v2ray官方客户端](https://github.com/v2fly/v2ray-core/releases),[Qv2ray客户端](https://github.com/Qv2ray/Qv2ray/releases)| [v2rayNG](https://github.com/2dust/v2rayNG/releases/latest)| [Kitsunebi客户端](https://itunes.apple.com/us/app/kitsunebi-proxy-utility/id1446584073?mt=8)|


> SSR客户端更新订阅如果有问题就换个版本吧，可以使用 `SSR安卓个人维护版本` 是没问题的。


更多客户端支持可以访问 [https://www.v2ray.com/awesome/tools.html](https://www.v2ray.com/awesome/tools.html) 了解。

## 订阅源使用方法

1. 安装v2ray客户端(支持ss和v2ray配置)
2. 添加订阅源地址 `https://raw.githubusercontent.com/learnhard-cn/free_proxy_ss/main/free`
3. 更新订阅源


完成更新后客户端就会显示可用结点了,选择一个启用试试吧。

- 优质代理 **不在多,在于可用** ,分享的代理都是经过PC客户端验证过可用的。
- 免费资源虽好，也是有人分享获得，希望这样的朋友越多越好。如果您有资源链接可以留言。

免费资源是网友们共同构建起来的。

## 安全说明

- 免费资源中无法保证代理服务端是否会记录用户访问信息, 原则上代理是可以知道你的位置和你正在访问哪个网址，所以使用免费资源不要涉及非法操作哦。访问谷歌或者油管还是可以的。

- 使用这些免费代理访问暗网也是不安全的，不要做这样的尝试就对啦。

- 免费资源有写是机场开放的，服务端地址本来写着的都是域名，经过处理后都变成了实际的IP地址了。这些机场真的有点贵，能自己搭建梯子的还是自己动手，毕竟也不难。



> 如果帮助到了您，希望可以给个Star! 


---

