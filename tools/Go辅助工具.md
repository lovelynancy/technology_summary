## 定位问题利器

1)perf代理工具,支持内存,cpu,堆栈查看,并支持火焰图.

perf工具和go-torch工具,快捷定位程序问题.

https://github.com/uber-archive/go-torch

https://github.com/google/gops

 

2)dlv远程调试. 

基于goland+dlv可以实现远程调式的能力.

https://github.com/go-delve/delve

提供了对golang原生的支持,相比gdb调试,简单太多。

 

3)网络代理工具.

goproxy代理,支持多种协议,支持ssh穿透和kcp协议.

https://github.com/snail007/goproxy

 

4)抓包工具. 

go-sniffer工具,可扩展的抓包工具,可以开发自定义协议的工具包. 现在只支持了http,mysql,redis,mongodb.

基于这个工具,我们开发了qapp协议的抓包。

https://github.com/40t/go-sniffer

 

5)反向代理工具,快捷开放内网端口供外部使用。

ngrok 可以让内网服务外部调用.

https://ngrok.com/

https://github.com/inconshreveable/ngrok

 

6)高效翻墙代理.

x2ray 自己搭建翻墙工具,从未如此简单. 配合一个海外服务器,你懂的。

https://github.com/v2ray/v2ray-core

 

7)配置化生成证书.

从根证书,到业务侧证书一键生成.

https://github.com/cloudflare/cfssl

 

8)免费的证书获取工具.

基于acme协议,从letsencrypt生成免费的证书,有效期1年,可自动续期。

https://github.com/Neilpang/acme.sh

 

9)开发环境管理工具,单机搭建可移植工具的利器。支持多种虚拟机后端。

vagrant常被拿来同docker相比,值得拥有。

https://github.com/hashicorp/vagrant

 

10)轻量级容器调度工具.

nomad 可以非常方便的管理容器和传统应用,相比k8s来说,简单不要太多.

https://github.com/hashicorp/nomad

 

11)敏感信息和密钥管理工具.

https://github.com/hashicorp/vault

 

12)高度可配置化的http转发工具。基于etcd配置.

https://github.com/gojek/weaver

 

13).进程监控工具 supervisor.

https://www.jianshu.com/p/39b476e808d8

 

14).基于procFile进程管理工具. 相比supervisor更加简单.

https://github.com/ddollar/foreman

 

15)基于http,https,websocket的调试代理工具,配置功能丰富。在线教育的nohost web调试工具,基于此开发.

https://github.com/avwo/whistle

 

15).分布式调度工具.

https://github.com/shunfei/cronsun/blob/master/README_ZH.md

https://github.com/ouqiang/gocron



16)自动化运维平台.Gaia.

https://github.com/gaia-pipeline/gaia