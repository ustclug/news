---
layout: post
title: 服务器宕机通知
image: http://hfs.mirrors.asia/829903743512ecd7eb17338c727c0282e34396afc0606752b80b1d479faa7c16?type=image/png
author: hejiyan
date: '2018-06-14 01:10:50 +0800'
categories:
- LUG服务器
tags: []
---

今天早些时候，由于我们的虚拟机宿主机 3 号节点的某些问题，LUG 内网包括网关与统一认证在内的部分关键服务器宕机，进而导致一部分服务不能正常提供，我们已经知悉并且开始处理这些问题。



以下服务因为此事件暂时不能正常运行，正在抢修中：

- 代码托管平台：[https://git.ustclug.org/](https://git.ustclug.org/)
- 网络加速服务：vpn.ustclug.org
- 防污染 DNS
- 主页 (wiki)：[https://lug.ustc.edu.cn/](https://lug.ustc.edu.cn/)
- 反向代理：*.proxy.ustclug.org
- VPN 在线申请系统：[https://getvpn.ustclug.org/](https://getvpn.ustclug.org/)
- 轻量级网络加速服务：[https://light.ustclug.org/](https://light.ustclug.org/)
- 服务器统一认证：ldap.ustclug.org
- 内网 VPN
- LUG FTP：[https://ftp.ustclug.org/](https://ftp.ustclug.org/)
- Ganglia 监控：[https://status.ustclug.org/](https://status.ustclug.org/)
- LDAP 配置管理系统（GOSA2）


以下服务暂不受此次事件影响：

- 开源镜像站（HTTP 访问）：[https://mirrors.ustc.edu.cn/](https://mirrors.ustc.edu.cn/)
- 开源镜像站（定时同步；rsync、FTP访问；帮助页面）：[https://mirrors.ustc.edu.cn/](https://mirrors.ustc.edu.cn/)
- 权威DNS：ns-a.ustclug.org. ns-b.ustclug.org. ns-c.ustclug.org.
- 网络启动：pxe.ustc.edu.cn
- 图书馆透明计算系统
- PGP密钥同步：[https://pgp.ustc.edu.cn/](https://pgp.ustc.edu.cn/)


受影响服务的恢复时间有待我们进一步查明事件原因后给出，给您带来的不便敬请谅解！



USTCLUG

2018-06-14 01:10:50