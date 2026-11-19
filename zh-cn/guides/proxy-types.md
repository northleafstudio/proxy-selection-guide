# 代理类型：网络、分配方式与协议

本指南由 Northleaf Studio 发布。Northleaf Studio 同时运营 [ProxyVendors](https://proxyvendors.com/zh-cn/)，这是一个按任务、会话、地区和费用比较服务商的目录。本文是第一方背景说明，不是对该站或任何服务商的独立第三方评测。产品名称会变，同一家服务商的两个官方页面也可能互相矛盾。请把它当作术语地图，再以服务商的当前文档核对细节。

## 语言

- [English](../../guides/proxy-types.md)
- **简体中文**
- [Español](../../es/guides/proxy-types.md)
- [Deutsch](../../de/guides/proxy-types.md)
- [Français](../../fr/guides/proxy-types.md)
- [日本語](../../ja/guides/proxy-types.md)
- [Português](../../pt/guides/proxy-types.md)
- [한국어](../../ko/guides/proxy-types.md)
- [اردو](../../ur/guides/proxy-types.md)
- [Bahasa Indonesia](../../id/guides/proxy-types.md)
- [Türkçe](../../tr/guides/proxy-types.md)
- [العربية](../../ar/guides/proxy-types.md)
- [Polski](../../pl/guides/proxy-types.md)
- [Italiano](../../it/guides/proxy-types.md)
- [ไทย](../../th/guides/proxy-types.md)
- [Українська](../../uk/guides/proxy-types.md)
- [Tiếng Việt](../../vi/guides/proxy-types.md)
- [Русский](../../ru/guides/proxy-types.md)

## 三个不同的问题

人们常常把三个问题都叫成一个词：“代理”。

1. **出口 IP 来自哪一类网络？** 这通常就是住宅、数据中心、ISP 和移动的含义。
2. **同一个出口会分配多久？** 这是静态与轮换的区别，有时也叫粘性会话。
3. **客户端怎样连接？** 这是 HTTP，包括用于 HTTPS 的 [HTTP CONNECT](https://proxyvendors.com/zh-cn/glossary/http-connect) 隧道，或者 [SOCKS5](https://proxyvendors.com/zh-cn/glossary/socks5)。

静态 IP 仍可能与其他客户共用。SOCKS5 端点是一种连接方式，不是一种 IP。同一个住宅或数据中心出口，往往可以通过不止一种协议到达，也有产品只支持 HTTP 或 HTTPS。

## 网络类型

**住宅。** 出口与家庭宽带或消费者网络相关联。目标对机房地址段较敏感，或者需要看起来像普通家庭连接的位置时，通常选这种。住宅流量常按吉字节计费。地址池是共享的，除非另买粘性或独享选项，否则会轮换。这个标签来自服务商或第三方数据库的分类，并不是 IP 本身携带的字段。

**数据中心。** 出口来自托管或云网络。这类产品按流量或按 IP 的单价往往更低，大批量请求时吞吐也可能更高。许多网站对数据中心地址段更严格。大量购买之前，先确认目标通过这种出口能否返回有效内容。

**ISP，有时被当成静态住宅来卖。** 地址通常登记在住宅互联网服务提供商名下，而代理主机本身常常放在数据中心。ISP 说的是这层登记关系，它本身并不表示出口保持不变。服务商经常把这个标签和较长的分配时间放在一起卖，适合登录、IP 白名单和固定地区。请确认 IP 是独享还是共享、断开或续费时会发生什么，以及是否需要身份核验。

**移动。** 出口来自移动运营商网络，通常是 4G 或 5G。用途包括移动广告、运营商特定页面，以及蜂窝网络上内容不同的地区页面。计费可能按吉字节、按天或按端口。要核对运营商和国家库存、轮换规则与用量限制，因为移动库存往往比住宅池更薄。

这些标签都不是质量评分。目标是否接受请求，取决于出口、请求方式，以及目标自己的策略。

## 分配：静态、轮换与粘性

轮换通常指每个请求或每隔很短的时间换一个出口。粘性或静态通常指同一次会话或整个租期内保持同一个出口。各家对这几个词的用法并不一致，官方页面有时会给出两个不同的会话时长。如果任务需要同一个 IP，请拿到确切的保持时间、会打断它的条件，以及掉线后是否保证更换。

## ASN 不是第四种类型

[ASN](https://proxyvendors.com/zh-cn/glossary/asn) 标识的是宣告某段地址的路由运营商。需要某一家运营商的网络时，它比只选国家更精确。它不是国家，也不能说明 IP 是住宅还是数据中心。指定一个 ASN 还会缩小地址池；如果没有可用出口，请求可能失败。

## 选定类型之后，检查出口

套餐页描述的是你打算购买的产品。[IP 检查](https://proxyvendors.com/zh-cn/ip-check) 显示你实际拿到的公网 IP、机构和 ASN，并可选择做 DNS 与 WebRTC 检查。如果结果和所购产品不一致，先停下来查清，再扩大用量。

比较具体套餐时，使用[购买核对清单](./buying-checklist.md)。

— Northleaf Studio
