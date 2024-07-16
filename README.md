# 永久免费节点搭建！通过Cloudflare Worker部署免费的VLESS节点，4K高速，解锁Netflix、ChatGPT

本文是通过 zizifn 大佬的一个开源项目[ edgetunnel](https://github.com/zizifn/edgetunnel) ，使得我们可以免费的在 Cloudflare 上面通过部署 Worker ，来创建一个免费 VLESS 节点！

视频教程：

## 准备工作：

**1、注册 Cloudflare 账号**，注册地址：[点击注册](https://dash.cloudflare.com/1fd6ef1f052a191089c7a5628aa6f5a7)

**2、CloudFlare 部署免费节点**

Workers代码：[点此查看>>](https://raw.githubusercontent.com/zizifn/edgetunnel/main/src/worker-vless.js) 

UUID在线生成：[点击进入>>](https://1024tools.com/uuid/)

ProxyIP： 可以替换成域名或优选IP（附后：更多 ProxyIP 列表）  
proxyip.us.fxxk.dedyn.io


**3、翻墙软件**  
Windows电脑：v2rayN下载 [点击下载>>](https://github.com/2dust/v2rayN/releases/download/6.45/zz_v2rayN-With-Core-SelfContained.7z)  
安卓：v2rayNG [点击下载>>](https://github.com/2dust/v2rayNG/releases)  
iOS/MAC：使用Shadowrocket小火箭

**4、节点设置**  
acsg3.cloudflarest.link  
acsg.cloudflarest.link  
acjp2.cloudflarest.link  
添加两个节点，一个是443端口，将节点地址换成优选域名，删除SNI，443端口节点需启用分片；另一个节点端口2082，关闭TLS。

**5、IP 优选工具**  
CF 优选 IP Windows 工具：[点击下载](https://github.com/badafans/better-cloudflare-ip/releases/download/20221201/batch.zip)  
若是速度不理想，可以自行优选 CF IP ，来进行提速！运行 IP 优选的时候，请关闭代理，这样会更准确！记得不要使用 TLS 优选！


**更多 proxyIP 列表：**

<code> **CM 维护** </code>  
proxyip.us.fxxk.dedyn.io  
IP落地区域: 美国 维护频率: 12小时/次  
proxyip.sg.fxxk.dedyn.io  
IP落地区域: 新加坡 维护频率: 12小时/次  
proxyip.jp.fxxk.dedyn.io  
IP落地区域: 日本 维护频率: 12小时/次  
proxyip.hk.fxxk.dedyn.io  
IP落地区域: 香港 维护频率: 12小时/次  
proxyip.aliyun.fxxk.dedyn.io  
IP落地区域: 阿里云 维护频率: 4小时/次  
proxyip.oracle.fxxk.dedyn.io  
IP落地区域: 甲骨文 维护频率: 4小时/次  
proxyip.digitalocean.fxxk.dedyn.io  
IP落地区域: 数码海 维护频率: 4小时/次

<code> **白嫖哥维护** </code>  
workers.cloudflare.cyou

<code> **Mingyu维护** </code>  
my-telegram-is-herocore.onecf.eu.org  
sg.ipdb.rr.nu  
nl.ipdb.rr.nu  
hk.ipdb.rr.nu  
jp.ipdb.rr.nu  
us.ipdb.rr.nu

<code> **小一维护** </code>  
hk.cf.zhetengsha.eu.org  
sg.cf.zhetengsha.eu.org  
us.cf.zhetengsha.eu.org  
jp.cf.zhetengsha.eu.org


**详细教程请访问**：[科技小露博客](https://www.kejixiaolu.com/)
