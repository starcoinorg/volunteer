# 中文版

## 为什么需要志愿者项目
一些朋友想要参与项目，但不知道该怎么入手，那最简单的方式可以从运行一个节点开始，以此作为开端，来开启自己的探索之路，随着越来越多的seed节点加入，也可以使项目本身更加去中心化。

## 怎么参与seed节点志愿者

### 什么是seed节点
对于区块链系统来说，在节点第一次启动加入网络时，需要知道网络中的其他节点的信息，这时候需要一个节点告诉它，该和哪些节点建立链接，所以seed节点维护了这样的信息网。这样的seed节点数越多、越去中心化当然对于整个系统来说，就越好。

### 怎么运行seed节点
可以通过运行如下命令，也可以参见文档，[运行/加入网络](https://starcoin.org/zh/developer/setup/runnetwork/)
> starcoin -n main

在日志里可以找到类似这样的记录
> Self address is: /ip4/127.0.0.1/tcp/9840/p2p/12D3KooWPePRG6BDdjgtEYmPDxNyJfMWpQ1Rwgefuz9eqksLfxJb

把其中的IP地址部分，换成公网IP地址，配置好防火墙访问控制策略后，就可以把上面的地址，以提交PR的方式，添加到本项目中。

### 怎么使用seed节点
可以通过在启动时增加--seed参数 多个seed，以英文逗号,分割
> starcoin -n main --seed /ip4/公网IP地址/tcp/9840/p2p/12D3KooWPePRG6BDdjgtEYmPDxNyJfMWpQ1Rwgefuz9eqksLfxJb

最后通过Pull Request提交到 seedlist.md文件中即可

# 英文版

Todo
