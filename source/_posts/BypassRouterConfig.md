---
title: 旁路由设置
date: 2021-02-16 20:42:03
tags:
 - 动态
---

今天在家里面折腾旁路由, 设置来设置去发现B站一直不走直连通道, 急得我上蹿下跳的.
后面发现是憨批Firefox开启了DNSSec(DNS Over Https), 还把provider锁成了Cloudflare, 坑爹啊, 这跟我家网络环境一点关系都没有!
把DNS改成旁路由的IP地址就解决了问题.