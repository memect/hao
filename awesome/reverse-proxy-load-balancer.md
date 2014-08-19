# 提高页面响应速度: 反向代理及负载均衡
contributors @mahak, BUPTGuo , 情非得已小屋, 新世界_玉兔 , 52cs

keywords:
 负载均衡(load balancer),
 反向映射 (reverse proxy),

https://github.com/memect/hao/blob/master/awesome/reverse-proxy-load-balancer.md


## 资源
http://webmasters.stackexchange.com/questions/10927/using-multiple-a-records-for-my-domain-do-web-browsers-ever-try-more-than-one 最简单的设置, DNS设置, 在一个域名下设置多个 "A" record, 即一个域名映射多个IP地址, 然后由域名服务器与浏览器共同选择其中的一个IP访问

http://yijiu.blog.51cto.com/433846/1408443 基于Nginx反向代理及负载均衡

http://fournines.wordpress.com/2011/12/02/improving-page-speed-cdn-vs-squid-varnish-nginx/ Improving page speed: CDN vs Squid/Varnish/nginx/mod_proxy



## 讨论
<b>@52cs 一个域名貌似只能绑定一个IP，这么多服务器怎么都可以被域名找到呢？</b>

mahak: 域名服务的A记录可以是多个ip做循环（round roubin），请求到了ip之后，可以是负载均衡设备，具体均衡策略可根据应用调整，比如是否会话保持等。

BUPTGuo：负载均衡？ (8月3日 17:17)

好东西传送门：[求助] 欢迎大家到这里去解答 http://t.cn/RPi5Prc 小声说一句：应该是通过load balancer或reverse proxy //@龙星计划: 求科普 (8月3日 17:51)

情非得已小屋：负载均衡+反向映射 (8月3日 19:24)

新世界_玉兔：DNS提供负载均衡 (8月4日 16:05)
