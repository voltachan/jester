# Jester

## 软件特点

![](https://i.loli.net/2020/01/16/uGXy7WUz9FHxVnh.png)

1. 支持几乎所有的协议。
2. 转发高效。
3. 可以在系统底层获取数据。
4. 灵活的认证方式。
5. 提供代理、VPN 两种模式。代理不分配内网 IP，VPN 会分配内网 IP（如果 SecureDHCP 启用，则仅分配临时 IP）。

## 认证方式对比

![](https://i.loli.net/2020/01/16/bhXGHfewjVCY48B.png)

## 为什么不使用 V2Ray

1. 转发效率低，在低配电脑上速率下降至 1/2。
2. 不支持 SSR 以及传统 VPN。
3. 认证方式单一。
4. 不能便携地连入内网，管理较为麻烦。

## 为什么不使用 OpenVPN 或 SoftEther

1. 转发效率低，在低配电脑上速率下降至 1/4 ~ 1/10。
2. 不支持新型协议。
3. 认证方式传统。
4. 无混淆、伪装，易断流，断线难以瞬间重连。
5. 配置过于复杂。
