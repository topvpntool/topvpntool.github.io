---
layout: post
title:  "SSR是什么？SSR与SS、VPN、V2Ray有什么区别？"
author: sal
image: assets/images/2.jpg
---
SS 全称 shadowsocks，作者是 clowwindy。一开始为个人独立开发并用作“科学上网”，后被大家所熟知和广泛使用。再后来，作者被请去“喝茶”，停止了该项目。

## SSR 是什么？

SSR 全称 shadowsocks-R，网民是 breakwa11 的帐号，声称 ss 容易被防火墙检测到，所以在混淆和协议方面做了改进，更加不容易被检测到，而且兼容 ss，改进后的项目叫 shadowsocks-R。 SS 和 SSR 两者原理相同，都是基于 socks5 代理。

客户端与服务端没有建立专有通道，客户端和实际要访问的服务端之间通过代理服务器进行通信，客户端发送请求和接受服务端返回的数据都要通过代理服务器。SSR 目的是为了能让流量通过防火墙。

## VPN 是什么？

vpn 在很多人心目中就是用来科学上网的工具，其实不是。vpn 最主要的功能，并不是用来科学上网，只是它可以达到科学上网的目的。

vpn–虚拟专用网络，它的功能是：在公用网络上建立专用网络，进行加密通讯。在企业网络和高校的网络中应用很广泛。你接入 vpn，其实就是接入了一个专有网络，你的网络访问都从这个出口出去，你和 vpn 之间的通信是否加密，取决于你连接 vpn 的方式或者协议。

立即免费试用 VPN

## V2Ray 是什么？

V2Ray 是 Project V 下的一个工具。Project V 是一个包含一系列构建特定网络环境工具的项目，而 V2Ray 属于最核心的一个。 简单地说，V2Ray 是一个与 Shadowsocks 类似的代理软件，可以用来科学上网（翻墙）学习国外先进科学技术。

SS 和 SSR 二者原理一样，都在基于 socks5 代理。客户端与服务端沒有创建专有通道，客户端和实际要浏览的服务端之间通过代理服务器进行通讯，客户端上传请求和接收服务器端反回的数据必须通过代理服务器。SSR 目地是为了能让流量利用防火墙。

客户端请求服务端数据步骤(SSR)：

(1)浏览器发送请求(基于 socks5 协议)， 通过 ssr 客户端将 sock5 协议通过协议插件和混淆插件进行转换加密，使得来自客户端的流量和基于 HTTP 协议的流量无差别;

(2)SSR 服务端(代理服务器)收到请求后，通过混淆插件、协议插件将数据解密并还原协议，最终转发到目标服务器。服务端反回数据到客户端同理。

立即免费试用 VPN

1.如果你非常注重隐私，那么在保证能够翻墙的情况下，VPN 是首选。因为，从 VPN 加密协议、主要的使用场景来看，VPN 就是用来保护传输数据的安全，而翻墙只是辅助功能。

2.SSR：就是 ShadowSocksR，是专门为翻墙而生的协议，它属于代理翻墙。它的前身是 ShadowSocks，由于作者被请喝茶，已经不在维护，并且目前 ss 的协议指纹已经被防火长城精准识别了，ss 协议翻墙基本是处于裸奔状态。  
而 SSR 可以看作是它的升级版，增加了一些混淆功能，翻墙效果更好。当然 SSR 只是开源翻墙协议中最具代表的一个，其中还有比较新的 V2Ray 协议等

3.如果只是翻墙看看 YouTube 等流媒体、逛逛网页的话，选择一个价格合理、速度快的 V2Ray 机场才是王道！机场不仅可以用来科学上网满足您任何上国外网站的需求，还可以用来作为外服游戏加速器使用。

立即一键翻墙

## vpn 和 ss/ssr 的优缺点

通过上面的介绍，其实基本已经能看出 vpn 和 ss/ssr 的区别了，那么他们到底孰优孰劣。

因为 vpn 是走的专用通道，它是用来给企业传输加密数据用的，所以 vpn 的流量特征很明显，以 openvpn 为例，流量特征明显，防火墙直接分析你的流量，如果特征匹配，直接封掉。目前就翻墙来说，PPTP 类型的 vpn 基本死的差不多了，L2TP 大部分地区干扰严重很不稳定。

ss/ssr 的目的就是用来翻墙的，而 vpn 的目的是用来加密企业数据的，对于 vpn 来说安全是第一位的，而对于 ss/ssr 来说穿透防火墙是第一位，抗干扰性强，而且对流量做了混淆，所有流量在通过防火墙的时候，基本上都被识别为普通流量，也就是说你翻墙了，但是政府是检测不到你在翻墙的。

两者的出发点和着重点就不同，ss/ssr 更注重流量的混淆加密。如果要安全匿名上网，可以用 vpn+tor 或者 ss/ssr+tor。

如果想要简单方便还安全的翻墙工具，还是建议大家使用 VPN,同样是付费，减少了很多复杂的操作，可持续性和可操作性强，VPN 推荐使用 PrivateVPN，价格便宜，线路多，3000+高速服务器遍布全球，快速实现匿名翻墙，特殊时期也能用的 VPN.

立即获取 PrivateVPN

## SSR 翻墙提醒

### 1. SSR 并不完美

普通人用 SSR 科学上网的最大困难有两个，一是找到可靠的服务器，二是配置客户端。很多 SSR 用户不愿意花钱买商业 SSR 节点，用免费服务器的结果就隔几天就要手动更新，因为免费的服务器大家都想用，所以免费节点总是很快过载失去实用价值。

即使是某些宣称自己是免费高速 SSR 的流行网站，也无法持续提供高质量的 SSR 节点。

非技术用户碰到的另一个问题是客户端配置，与成熟的 VPN 客户端不同，目前的 ShadowSocksR 客户端的还需要一点手动配置，在使用方便程度上还差一点，普通用户误打误撞配置成功还好，要是发现配置了没法用，就会很头痛。

### 2. 不要在公网分享 SSR

在国内公网绝对不要做 SSR 分享当大好人，特别是自己架设的服务器，之前已经有因为这个被请喝茶交罚款的个人，男子因销售 SS 被判刑。

SSR 服务器端开源和技术上更灵活的特性让**它比 VPN 更好扩散，但也因此让它更危险**。不要在国内网络上提供任何 SSR 下载相关的东西，不管是节点地址，订阅地址还是 SSR 脚本，切记！

### 3. 慎用免费 SSR 节点

如果你想长期比较稳定的用 SSR 翻墙，还是不要用免费 SSR 吧。并非免费 SSR 节点不能用，而是它们绝大多数无法长期使用，连通率和速度都无法保障。因为这些节点 IP 地址都被分享到公共网站上，用的人很多，IP 被封得也很快，所以往往需要频繁手动更新，很多免费 SSR 机场都不提供订阅，频繁地手动更新非常麻烦。

### 4. 明白自建的局限

自己搭建 SSR 有特别的优势，比如在某些敏感时期往往因为自建服务器的私密性和流量特征小等原因反而不会被墙 —— 此时绝大多数知名翻墙工具基本都会歇菜。

但自建服务器也有很大的局限性，自建服务器单 IP 很难长期和防火墙抗衡，哪怕现在运气好，未来被封的概率仍然很大，虽然 VPS 厂商都提供换 IP 服务，但是换 IP 不是无限的，最多给你免费换一次 IP，然后就要付费了，不仅花钱而且费时间，哪怕换好了 IP，仍然是单 IP 翻墙，未来的麻烦并没有小多少。

## SSR 节点类型

### 1. 免费 SSR 节点

网上到处都是免费 SSR 节点分享，特别是码农圈，有时候打开一些个人博客，菜单里就有 SSR 相关的页面，可惜的是，基本上当你看到这些页面的时候，里面分享的免费 SSR 节点已经不能用了，这是我们不推荐用 SSR 免费节点的原因，光是要找到能用的就不容易，找到的大多数又没法用，简直浪费时间。即使是当时能用的，也会因为服务器过于拥挤而失去可用性。

### 2. 用 SSR 订阅地址（自动更新）

pythonic.life上推荐的各种订阅源地址，没有仔细测试过可用情况，就评论看，这些免费公开的节点失效得很快。SSR 订阅地址活跃在很多个站和电报群里，如果你能访问 Google，搜“SSR 订阅”能搜出一大堆。

### 3. 购买 SSR 帐号，SSR 机场推荐

我们认为这是目前**最靠谱的获取 SSR 节点的方法：直接购买 SSR 账号，用付费 SSR 机场。**

越来越多的人开始意识到开 SSR 机场是门有利可图的生意，事实上也是这两年大量厂商进入这个市场展开厮杀，目前知名和不知名的 SSR 机场估计有几百家，绝大多数由中国人运营，都提供中文服务，有一些甚至已经在国内完成了注册并运营（不知道他们是如何办到的）。

付费 SSR 账号在饱和竞争之下正变得越来越便宜，因为厂商架设服务器可以高效复用，所以个人用户购买 SSR 节点的成本往往低于个人单独购买 VPS 自己搭建的成本。

立即一键翻墙

## 总结

最快捷简单高效的翻墙工具是使用成熟的 VPN，这样的 VPN 使用稳定，不需要额外的设置，安全性高，保证你的翻墙之旅高枕无忧，推荐使用 PrivateVPN，VPN 界的性价比之王。

立即获取 PrivateVPN