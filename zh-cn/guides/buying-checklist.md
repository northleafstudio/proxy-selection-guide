# 购买代理套餐前的简短核对清单

这份清单由 Northleaf Studio 发布。Northleaf Studio 同时运营 [ProxyVendors](https://proxyvendors.com/zh-cn/)。它是第一方配套材料，不是无关第三方的推荐。请拿它对照服务商当前的价格页、条款，并做一次小规模试用。它不能保证某个套餐对你的目标一定有效。

## 语言

- [English](../../guides/buying-checklist.md)
- **简体中文**
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- [日本語](../../ja/guides/buying-checklist.md)
- [Português](../../pt/guides/buying-checklist.md)
- [한국어](../../ko/guides/buying-checklist.md)
- [اردو](../../ur/guides/buying-checklist.md)
- [Bahasa Indonesia](../../id/guides/buying-checklist.md)
- [Türkçe](../../tr/guides/buying-checklist.md)
- [العربية](../../ar/guides/buying-checklist.md)
- [Polski](../../pl/guides/buying-checklist.md)
- [Italiano](../../it/guides/buying-checklist.md)
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- [Tiếng Việt](../../vi/guides/buying-checklist.md)
- [Русский](../../ru/guides/buying-checklist.md)

## 1. 先写清任务，再选网络

写下出口要完成的事：长期登录、特定地区的公开数据、大请求量，或移动运营商测试。再按[代理类型指南](./proxy-types.md)对应到一种网络：住宅、数据中心、ISP 或移动。如果服务商首页和价格页宣传的起步价或国家数量不同，两处都记下来，并问清你实际要买的那一档适用哪一个数字。

## 2. 核对会话行为

确定你需要同一个出口保持数分钟、数小时或整个租期，还是每个请求换一个出口。确认粘性或静态的时长、什么情况会打断它，以及 IP 掉线后是否更换。官方文档有时会写出两个不同的保持时间；在服务商确认之前，把这一点视为尚未确定。

## 3. 确认协议和身份验证

HTTP，包括访问 HTTPS 网站时使用的 [HTTP CONNECT](https://proxyvendors.com/zh-cn/glossary/http-connect)，与 [SOCKS5](https://proxyvendors.com/zh-cn/glossary/socks5) 不是一回事。有些住宅产品只支持 HTTP 和 HTTPS。如果需要 SOCKS5，或需要通过 SOCKS5 传输 UDP，请确认产品和你的客户端都支持。确认入口主机、端口和验证方式：用户名和密码、IP 白名单，或两者都有。CONNECT 过程中的 407 响应来自代理。这个状态的含义是 Proxy Authentication Required：代理要求进行身份验证，或者没有接受它收到的身份验证。隧道没有建立，目标网站也没有看到这次请求。

## 4. 把真实费用加总

不要只看标题上的单价。记下最低购买量、流量包有效期或过期时间、超量费、重试浪费、精细定向附加费、增值税，以及自动充值或自动续费。标题价格可能属于大流量档，而不是你一开始会买的那一包。如果试用要绑卡并默认打开自动充值，先决定要不要在试用开始前关掉。

## 5. 阅读试用、退款和访问规则

查看试用的额度和时长、退款窗口、用量上限，以及退款是否必须先证明网络故障。注意身份或 KYC 核验、银行或政府网站等被禁止的类别，以及静态或独享产品的公平使用限制。如果来源或合规对你重要，向服务商索取说明，不要只看营销文案。

## 6. 查清网络，然后实测

如果需要指定运营商，确认是否支持 [ASN 定向](https://proxyvendors.com/zh-cn/glossary/asn)，以及没有可用出口时会发生什么。然后做一次小规模的真实任务：目标是否返回有效响应、会话是否中断、地区是否准确、实际消耗了多少流量。连上之后，用 [IP 检查](https://proxyvendors.com/zh-cn/ip-check) 对照所购产品，比较公网 IP、机构和 ASN；如果 DNS 和 WebRTC 路径也重要，就把这两项检查也做了。

然后再决定买多少。

— Northleaf Studio
