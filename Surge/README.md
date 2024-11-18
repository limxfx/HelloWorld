# Surge 配置

## Usage

1. 找到配置文件中的 **policy-path=机场订阅链接**
2. 将 **机场订阅链接** 替换为你实际的机场订阅链接地址
3. 保存并重新加载配置文件

## Modules

1. [always-real-ip](https://ruleset.skk.moe/Modules/sukka_common_always_realip.sgmodule): 确保访问特定服务时，使用真实 IP

2. [DNS Mapping](https://ruleset.skk.moe/Modules/sukka_local_dns_mapping.sgmodule): 为本地域名指定解析规则，提升解析效率或解决解析错误

## 其他推荐技巧

1. 模块加载顺序：确保 always-real-ip 模块优先加载
2. 分流规则优化：根据 Sukka 提供的规则集合，可以进一步优化分流策略

如果需要更详细的配置或其他模块介绍，可以参考 [Sukka](https://blog.skk.moe/) 的原文：[我有特别的 Surge 配置和使用技巧](https://blog.skk.moe/post/i-have-my-unique-surge-setup)
