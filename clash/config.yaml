port: 7890
socks-port: 1080 # SOCKS5代理端口，DNS请求会中转
redir-port: 3333 # 透明代理端口
allow-lan: true
mode: Rule
log-level: info # 日志显示级别： debug-问题调试，info-基本信息
external-controller: 0.0.0.0:9090
secret: route
hosts:
  router.asus.com: 192.168.50.1
# 透明代理开启DNS
dns:
  enable: true
  ipv6: false
  listen: 0.0.0.0:1053
  enhanced-mode: redir-host # redir-host or fake-ip
  fake-ip-range: 198.18.0.1/16 # Fake IP addresses pool CIDR
  use-hosts: false # lookup hosts and return IP record
  nameserver:
  - 114.114.114.114
  # 提供 fallback 时，如果GEOIP非 CN 中国时使用 fallback 解析
  fallback:
  - 8.8.8.8   # Google DNS over TCP
  - 1.1.1.1   # cloudflare DNS over TCP
  - tls://8.8.8.8:853   # Google DNS over TLS
  - tls://1.1.1.1:853   # cloudflare DNS over TLS
  - https://dns.google/dns-query   # Google DNS over HTTPS
  - https://cloudflare-dns.com/dns-query   # cloudflare DNS over HTTPS
  # 强制DNS解析使用`fallback`配置
  fallback-filter:
    # true: CN使用nameserver解析，非CN使用fallback
    geoip: true
    # geoip设置为false时有效： 不匹配`ipcidr`地址时会使用`nameserver`结果，匹配`ipcidr`地址时使用`fallback`结果。
    ipcidr:
    - 240.0.0.0/4
# 个人节点
proxies:
- name: 🇯🇵:日本-ss-45.66.134.176:811-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  type: ss
  server: 45.66.134.176
  password: G!yBwPWH3Vao
  port: 811
  cipher: chacha20-ietf-poly1305
- name: 🇯🇵:日本-ss-45.66.134.176:806-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  type: ss
  server: 45.66.134.176
  password: G!yBwPWH3Vao
  port: 806
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-162.251.61.221:805-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 162.251.61.221
  password: G!yBwPWH3Vao
  port: 805
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-167.88.62.68:8881-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.62.68
  password: kDWvXYZoTBcGkC4
  port: 8881
  cipher: aes-256-gcm
- name: 🇯🇵:日本-ss-45.66.134.176:807-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  type: ss
  server: 45.66.134.176
  password: G!yBwPWH3Vao
  port: 807
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-167.88.63.99:2375-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.63.99
  password: faBAoD54k87UJG7
  port: 2375
  cipher: aes-256-gcm
- name: 🇺🇸:美国-ss-167.88.63.99:7307-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.63.99
  password: FoOiGlkAA9yPEGP
  port: 7307
  cipher: aes-256-gcm
- name: 🇺🇸:美国-ss-162.251.61.221:800-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 162.251.61.221
  password: G!yBwPWH3Vao
  port: 800
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-167.88.62.68:8000-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.62.68
  password: KixLvKzwjekG00rm
  port: 8000
  cipher: aes-256-gcm
- name: 🇺🇸:美国-ss-162.251.61.221:812-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 162.251.61.221
  password: G!yBwPWH3Vao
  port: 812
  cipher: chacha20-ietf-poly1305
- name: 🇯🇵:日本-ss-45.66.134.176:810-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  type: ss
  server: 45.66.134.176
  password: G!yBwPWH3Vao
  port: 810
  cipher: chacha20-ietf-poly1305
- name: 🇯🇵:日本-ss-193.38.139.203:807-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  type: ss
  server: 193.38.139.203
  password: G!yBwPWH3Vao
  port: 807
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-167.88.63.99:8090-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.63.99
  password: PCnnH6SQSnfoS27
  port: 8090
  cipher: aes-256-gcm
- name: 🇯🇵:日本-ss-193.38.139.203:809-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  type: ss
  server: 193.38.139.203
  password: G!yBwPWH3Vao
  port: 809
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-167.88.62.68:5600-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.62.68
  password: Y6R9pAtvxxzmGC
  port: 5600
  cipher: aes-256-gcm
- name: 🇺🇸:美国-ss-167.88.62.68:9102-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.62.68
  password: e4FCWrgpkji3QY
  port: 9102
  cipher: aes-256-gcm
- name: 🇺🇸:美国-ss-167.88.62.68:4444-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.62.68
  password: pKEW8JPByTVTLtM
  port: 4444
  cipher: aes-256-gcm
- name: 🇺🇸:美国-ss-162.251.61.221:804-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 162.251.61.221
  password: G!yBwPWH3Vao
  port: 804
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-138.68.248.130:811-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 138.68.248.130
  password: Ultr@r00t_2017
  port: 811
  cipher: chacha20-ietf-poly1305
- name: 🇯🇵:日本-ss-45.66.134.176:802-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  type: ss
  server: 45.66.134.176
  password: G!yBwPWH3Vao
  port: 802
  cipher: chacha20-ietf-poly1305
- name: 🇺🇸:美国-ss-167.88.63.99:7306-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.63.99
  password: FoOiGlkAA9yPEGP
  port: 7306
  cipher: aes-256-gcm
- name: 🇺🇸:美国-ss-162.251.61.221:802-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 162.251.61.221
  password: G!yBwPWH3Vao
  port: 802
  cipher: chacha20-ietf-poly1305
- name: 🇬🇧:英国-ss-83.229.73.60:50003-被墙-直连-解锁以色列地区NF非自制剧
  type: ss
  server: 83.229.73.60
  password: '8460400130'
  port: 50003
  cipher: aes-256-cfb
- name: 🇺🇸:美国-ss-167.88.63.99:2376-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 167.88.63.99
  password: faBAoD54k87UJG7
  port: 2376
  cipher: aes-256-gcm
- name: 🇯🇵:日本-ss-193.38.139.204:806-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  type: ss
  server: 193.38.139.204
  password: G!yBwPWH3Vao
  port: 806
  cipher: chacha20-ietf-poly1305
- name: 🇮🇱:以色列-ss-185.162.126.217:50004-被墙-直连-解锁以色列地区NF非自制剧
  type: ss
  server: 185.162.126.217
  password: '4415934295'
  port: 50004
  cipher: aes-256-cfb
- name: 🇺🇸:美国-ss-107.182.177.136:256-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 107.182.177.136
  password: bwhskrskr05
  port: 256
  cipher: aes-256-cfb
- name: 🇺🇸:美国-ss-35.91.237.33:443-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 35.91.237.33
  password: amazonskr05
  port: 443
  cipher: aes-256-cfb
- name: 🇯🇵:日本-ss-193.38.139.203:803-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  type: ss
  server: 193.38.139.203
  password: G!yBwPWH3Vao
  port: 803
  cipher: chacha20-ietf-poly1305
- name: 🇯🇵:日本-ss-193.38.139.204:809-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  type: ss
  server: 193.38.139.204
  password: G!yBwPWH3Vao
  port: 809
  cipher: chacha20-ietf-poly1305
- name: 🇨🇦:加拿大-ss-38.64.138.53:1035-被墙-直连-解锁美国地区NF非自制剧
  type: ss
  server: 38.64.138.53
  password: )1N1E6v0SU_rGTpg
  port: 1035
  cipher: chacha20-ietf-poly1305
- name: 🇮🇱:以色列-ss-185.162.125.91:50004-被墙-直连-解锁以色列地区NF非自制剧
  type: ss
  server: 185.162.125.91
  password: '4415934295'
  port: 50004
  cipher: aes-256-cfb
- name: 🇯🇵:日本-ss-52.197.66.243:443-被墙-直连-解锁日本地区NF非自制剧
  type: ss
  server: 52.197.66.243
  password: amazonskr05
  port: 443
  cipher: aes-256-cfb
- name: 🇺🇸:美国-ss-mf01.xmss.vip:18888-被墙-中转:94.131.107.12-解锁美国地区NF非自制剧
  type: ss
  server: mf01.xmss.vip
  password: 35b0f578-8961-4a2b-99a1-db9555e522e4
  port: 18888
  cipher: chacha20-ietf-poly1305
- name: 🇮🇱:以色列-ss-31.133.100.49:50004-被墙-直连-解锁以色列地区NF非自制剧
  type: ss
  server: 31.133.100.49
  password: '4415934295'
  port: 50004
  cipher: aes-256-cfb
- name: 🇨🇳:中国-vmess-106.12.168.13:13156-可用-直连-完全不支持NF
  type: vmess
  server: 106.12.168.13
  network: ws
  port: 13156
  uuid: 9bf4cba4-9e9e-4da4-8e65-f7c487c539df
  alterId: 4
  cipher: auto
  udp: false
  tls: false
  ws-path: /
- name: 🇨🇳:中国-vmess-47.93.231.218:53022-可用-直连-完全不支持NF
  type: vmess
  server: 47.93.231.218
  network: ws
  port: 53022
  uuid: 95fd7642-2160-4528-e909-3d526b533013
  alterId: 4
  cipher: auto
  udp: false
  tls: false
  ws-path: /
- name: 🇯🇵:日本-vmess-146.56.40.117:27675-被墙-直连-解锁韩国地区NF非自制剧
  type: vmess
  server: 146.56.40.117
  network: ws
  port: 27675
  uuid: 053ca0f4-057e-493d-ad30-5ba51f00f59c
  alterId: 4
  cipher: auto
  udp: false
  tls: false
  ws-path: /
- name: 🇺🇸:美国-vmess-ca.0112233.xyz:8443-被墙-中转:199.87.210.186-解锁新加坡地区NF非自制剧
  type: vmess
  server: ca.0112233.xyz
  network: ws
  port: 8443
  uuid: c3000e9d-bee7-4fdb-b312-dd07030f325d
  alterId: 4
  cipher: auto
  udp: false
  tls: true
  ws-path: /home
- name: 🇺🇸:美国-vmess-gaio.miaoge110.cf:443-被墙-中转:104.28.205.111-解锁美国地区NF非自制剧
  type: vmess
  server: gaio.miaoge110.cf
  network: ws
  port: 443
  uuid: 4893ed3e-8a5f-48dc-aa1e-bbc2e67a065b
  alterId: 0
  cipher: auto
  udp: false
  ws-path: /jcnf
- name: 🇨🇳:中国-vmess-8.214.33.158:80-被墙-直连-解锁新加坡地区NF非自制剧
  type: vmess
  server: 8.214.33.158
  network: ws
  port: 80
  uuid: cb81e6ab-1d83-4ac1-f0ad-ae5c2a7c29ef
  alterId: 0
  cipher: auto
  udp: false
  ws-path: /
- name: 🇺🇸:美国-vmess-jparm.fineyoo.cf:443-被墙-中转:152.70.81.66-解锁日本地区NF非自制剧
  type: vmess
  server: jparm.fineyoo.cf
  network: ws
  port: 443
  uuid: bd5ee249-fe7b-4669-a6d9-b3f5eecb98e6
  alterId: 4
  cipher: auto
  udp: false
  tls: true
  ws-path: /123
- name: 🇺🇸:美国-vmess-jparm.fineyoo.ml:443-被墙-中转:138.2.33.90-解锁日本地区NF非自制剧
  type: vmess
  server: jparm.fineyoo.ml
  network: ws
  port: 443
  uuid: 10ba478e-9de1-4aa9-c09e-7707025334d3
  alterId: 4
  cipher: auto
  udp: false
  tls: true
  ws-path: /123
- name: 🇺🇸:美国-vmess-jpamd.fineyoo.ml:443-被墙-中转:138.2.33.102-解锁日本地区NF非自制剧
  type: vmess
  server: jpamd.fineyoo.ml
  network: ws
  port: 443
  uuid: 35e5e2ea-1372-4745-dff8-fb2bd11016c4
  alterId: 4
  cipher: auto
  udp: false
  tls: true
  ws-path: /123
- name: 🇺🇸:美国-vmess-amdkr.ptuu.ga:443-被墙-中转:152.69.229.222-解锁韩国地区NF非自制剧
  type: vmess
  server: amdkr.ptuu.ga
  network: ws
  port: 443
  uuid: a612b67f-a79b-4a71-a82b-a46906752023
  alterId: 4
  cipher: auto
  udp: false
  tls: true
  ws-path: /408
- name: 🇺🇸:美国-vmess-amdkr.ptuu.ml:443-被墙-中转:146.56.96.75-解锁韩国地区NF非自制剧
  type: vmess
  server: amdkr.ptuu.ml
  network: ws
  port: 443
  uuid: e2cdc305-dda7-465e-b675-ba0468d2a8b3
  alterId: 4
  cipher: auto
  udp: false
  tls: true
  ws-path: /987

# 类型选择 简介
# select : 用于选择代理或代理组, 可以通过 RESTful API 来切换代理，建议在 GUI 中使用
# load-balance : 相同eTLD+1的请求将拨号到同一个代理。
# url-test : 通过对 URL 的速度进行基准测试来选择将使用哪个代理。
# fallback : 按优先级选择可用的策略。通过访问 URL 来测试可用性，就像自动 url-test 组一样。
# relay : 中继链接代理。代理不应包含中继。不支持 UDP。 流量：Clash <-> http <-> vmess <-> ss1 <-> ss2 <-> Internet 
#  
# 推荐选择：
#   命令行服务建议选择 url-test / fallback / load-balance
#   GUI窗口 官方建议选择 select ，当然也推荐使用url-test 自动检测可用性。
proxy-groups:
  # 保留的自定义节点
- name: PROXY
  type: select   # load-balance, select, relay, fallback, url-test
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - DIRECT
  - 🇨🇳:中国-vmess-47.93.231.218:53022-可用-直连-完全不支持NF
  - 🇨🇳:中国-vmess-106.12.168.13:13156-可用-直连-完全不支持NF
- name: 被墙代理组
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - DIRECT
  - 🇺🇸:美国-vmess-jparm.fineyoo.ml:443-被墙-中转:138.2.33.90-解锁日本地区NF非自制剧
  - 🇺🇸:美国-vmess-jparm.fineyoo.cf:443-被墙-中转:152.70.81.66-解锁日本地区NF非自制剧
  - 🇺🇸:美国-vmess-jpamd.fineyoo.ml:443-被墙-中转:138.2.33.102-解锁日本地区NF非自制剧
  - 🇺🇸:美国-vmess-gaio.miaoge110.cf:443-被墙-中转:104.28.205.111-解锁美国地区NF非自制剧
  - 🇺🇸:美国-vmess-ca.0112233.xyz:8443-被墙-中转:199.87.210.186-解锁新加坡地区NF非自制剧
  - 🇺🇸:美国-vmess-amdkr.ptuu.ml:443-被墙-中转:146.56.96.75-解锁韩国地区NF非自制剧
  - 🇺🇸:美国-vmess-amdkr.ptuu.ga:443-被墙-中转:152.69.229.222-解锁韩国地区NF非自制剧
  - 🇺🇸:美国-ss-mf01.xmss.vip:18888-被墙-中转:94.131.107.12-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-35.91.237.33:443-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.63.99:8090-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.63.99:7307-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.63.99:7306-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.63.99:2376-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.63.99:2375-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.62.68:9102-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.62.68:8881-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.62.68:8000-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.62.68:5600-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-167.88.62.68:4444-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-162.251.61.221:812-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-162.251.61.221:805-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-162.251.61.221:804-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-162.251.61.221:802-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-162.251.61.221:800-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-138.68.248.130:811-被墙-直连-解锁美国地区NF非自制剧
  - 🇺🇸:美国-ss-107.182.177.136:256-被墙-直连-解锁美国地区NF非自制剧
  - 🇯🇵:日本-vmess-146.56.40.117:27675-被墙-直连-解锁韩国地区NF非自制剧
  - 🇯🇵:日本-ss-52.197.66.243:443-被墙-直连-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-45.66.134.176:811-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-45.66.134.176:810-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-45.66.134.176:807-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-45.66.134.176:806-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-45.66.134.176:802-被墙-中转:185.168.20.250-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-193.38.139.204:809-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-193.38.139.204:806-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-193.38.139.203:809-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-193.38.139.203:807-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  - 🇯🇵:日本-ss-193.38.139.203:803-被墙-中转:193.38.139.201-解锁日本地区NF非自制剧
  - 🇮🇱:以色列-ss-31.133.100.49:50004-被墙-直连-解锁以色列地区NF非自制剧
  - 🇮🇱:以色列-ss-185.162.126.217:50004-被墙-直连-解锁以色列地区NF非自制剧
  - 🇮🇱:以色列-ss-185.162.125.91:50004-被墙-直连-解锁以色列地区NF非自制剧
  - 🇬🇧:英国-ss-83.229.73.60:50003-被墙-直连-解锁以色列地区NF非自制剧
  - 🇨🇳:中国-vmess-8.214.33.158:80-被墙-直连-解锁新加坡地区NF非自制剧
  - 🇨🇦:加拿大-ss-38.64.138.53:1035-被墙-直连-解锁美国地区NF非自制剧
- name: 仅支持Netflix自制剧
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - DIRECT
- name: 解锁Netflix非自制剧
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - DIRECT
- name: 入口代理组
    # 中继代理组,不支持UDP协议。线路: clash <-> vmess <-> ss1 <-> ss2 <-> Internet
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - 仅支持Netflix自制剧
  - 解锁Netflix非自制剧
  - PROXY
- name: 出口代理组
    # 中继代理组,不支持UDP协议。线路: clash <-> vmess <-> ss1 <-> ss2 <-> Internet
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - 被墙代理组
  - 仅支持Netflix自制剧
  - 解锁Netflix非自制剧
- name: RELAY_PROXY
    # 中继代理组,不支持UDP协议。线路: clash <-> vmess <-> ss1 <-> ss2 <-> Internet
  type: relay
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - 入口代理组
  - 出口代理组
- name: NETFLIX_PROXY
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - 解锁Netflix非自制剧
  - 仅支持Netflix自制剧
  - RELAY_PROXY
  - DIRECT
- name: Tiktok_PROXY
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - PROXY
  - 解锁Netflix非自制剧
  - 仅支持Netflix自制剧
  - RELAY_PROXY
  - DIRECT
- name: Bili_PROXY
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - DIRECT
  - PROXY
  - 解锁Netflix非自制剧
  - 仅支持Netflix自制剧
  - RELAY_PROXY
- name: IQiyi_PROXY
  type: select
  url: http://www.gstatic.com/generate_204
  interval: 300
  proxies:
  - DIRECT
  - PROXY
  - 解锁Netflix非自制剧
  - 仅支持Netflix自制剧
  - RELAY_PROXY

# 黑名单模式，命中规则使用代理
rules:
- DOMAIN,clash.razord.top,DIRECT
- DOMAIN,yacd.haishan.me,DIRECT
  # > Netflix
- DOMAIN-SUFFIX,netflix.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflix.net,NETFLIX_PROXY
- DOMAIN-SUFFIX,nflxext.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,nflximg.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,nflximg.net,NETFLIX_PROXY
- DOMAIN-SUFFIX,nflxso.net,NETFLIX_PROXY
- DOMAIN-SUFFIX,nflxvideo.net,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest0.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest1.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest2.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest3.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest4.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest5.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest6.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest7.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest8.com,NETFLIX_PROXY
- DOMAIN-SUFFIX,netflixdnstest9.com,NETFLIX_PROXY
  # Netflix测速网站
- DOMAIN-SUFFIX,fast.com,NETFLIX_PROXY
  # - RULE-SET,video_netflix,NETFLIX_PROXY
  # > TikTok
- PROCESS-NAME,com.ss.android.ugc.trill,Tiktok_PROXY
- DOMAIN-SUFFIX,byteoversea.com,Tiktok_PROXY
- DOMAIN-SUFFIX,ibytedtos.com,Tiktok_PROXY
- DOMAIN-SUFFIX,ipstatp.com,Tiktok_PROXY
- DOMAIN-SUFFIX,muscdn.com,Tiktok_PROXY
- DOMAIN-SUFFIX,musical.ly,Tiktok_PROXY
- DOMAIN-SUFFIX,tiktok.com,Tiktok_PROXY
- DOMAIN-SUFFIX,tik-tokapi.com,Tiktok_PROXY
- DOMAIN-SUFFIX,tiktokcdn.com,Tiktok_PROXY
- DOMAIN-SUFFIX,tiktokv.com,Tiktok_PROXY
  # - RULE-SET,video_tiktok,Tiktok_PROXY
  # > iQIYI
- DOMAIN-SUFFIX,iq.com,IQiyi_PROXY
- DOMAIN,intl.iqiyi.com,IQiyi_PROXY
- DOMAIN,intl-rcd.iqiyi.com,IQiyi_PROXY
- DOMAIN,intl-subscription.iqiyi.com,IQiyi_PROXY
  # - RULE-SET,video_iqiyi,IQiyi_PROXY
  # > Bilibili
- PROCESS-NAME,com.bilibili.app.in,Bili_PROXY
- PROCESS-NAME,tv.danmaku.bili,Bili_PROXY
- DOMAIN-SUFFIX,acg.tv,Bili_PROXY
- DOMAIN-SUFFIX,acgvideo.com,Bili_PROXY
- DOMAIN-SUFFIX,b23.tv,Bili_PROXY
- DOMAIN-SUFFIX,biliapi.com,Bili_PROXY
- DOMAIN-SUFFIX,biliapi.net,Bili_PROXY
- DOMAIN-SUFFIX,bilibili.com,Bili_PROXY
- DOMAIN-SUFFIX,biligame.com,Bili_PROXY
- DOMAIN-SUFFIX,biligame.net,Bili_PROXY
- DOMAIN-SUFFIX,bilivideo.com,Bili_PROXY
- DOMAIN-SUFFIX,hdslb.com,Bili_PROXY
- DOMAIN-SUFFIX,im9.com,Bili_PROXY
- DOMAIN-SUFFIX,smtcdns.net,Bili_PROXY
  # 后面追加规则
