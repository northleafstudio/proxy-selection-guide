# Proxy types: network, assignment, and protocol

This guide is published by Northleaf Studio, which also operates [ProxyVendors](https://proxyvendors.com/), a directory for comparing providers by task, session, location, and cost. It is first-party background material, not an unaffiliated third-party review of that site or of any vendor. Product labels change, and two official pages from the same vendor can disagree. Use this as a map of the terms, then confirm details on the provider's current documentation.

## Languages

- **English**
- [简体中文](../zh-cn/guides/proxy-types.md)
- [Español](../es/guides/proxy-types.md)
- [Deutsch](../de/guides/proxy-types.md)
- [Français](../fr/guides/proxy-types.md)
- [日本語](../ja/guides/proxy-types.md)
- [Português](../pt/guides/proxy-types.md)
- [한국어](../ko/guides/proxy-types.md)
- [اردو](../ur/guides/proxy-types.md)
- [Bahasa Indonesia](../id/guides/proxy-types.md)
- [Türkçe](../tr/guides/proxy-types.md)
- [العربية](../ar/guides/proxy-types.md)
- [Polski](../pl/guides/proxy-types.md)
- [Italiano](../it/guides/proxy-types.md)
- [ไทย](../th/guides/proxy-types.md)
- [Українська](../uk/guides/proxy-types.md)
- [Tiếng Việt](../vi/guides/proxy-types.md)
- [Русский](../ru/guides/proxy-types.md)

## Three different questions

People often collapse three questions into one word, "proxy":

1. **What kind of network does the exit IP come from?** This is the usual meaning of residential, datacenter, ISP, and mobile.
2. **How long does the same exit stay assigned?** This is static versus rotating, sometimes called sticky sessions.
3. **How does the client connect?** This is HTTP, including the [HTTP CONNECT](https://proxyvendors.com/glossary/http-connect) tunnel used for HTTPS, or [SOCKS5](https://proxyvendors.com/glossary/socks5).

A static IP can still be shared with other customers. A SOCKS5 endpoint is a connection method, not a type of IP. The same residential or datacenter exit can often be reached over more than one protocol, and some products support only HTTP or HTTPS.

## Network types

**Residential.** The exit is associated with a consumer or broadband network. This is the usual choice when a target is sensitive to hosting ranges, or when you need a location that looks like an ordinary household connection. Residential traffic is often billed per gigabyte. Pools are shared and rotate unless you buy a sticky or dedicated option. The label is a classification from the provider or from third-party databases; it is not a field carried by the IP itself.

**Datacenter.** The exit comes from a hosting or cloud network. These products are often cheaper per unit of traffic or per IP, and they can offer higher throughput for large request volumes. Many sites treat datacenter ranges more strictly. Before you buy a large plan, check whether the target actually returns valid content through that kind of exit.

**ISP, sometimes sold as static residential.** The address is typically registered to a residential internet service provider, while the proxy host itself often sits in a data center. ISP names that registration; it does not, by itself, mean the exit stays fixed. Vendors often pair the label with a longer-lived assignment, which is a common fit for logins, IP allowlists, and a fixed location. Confirm whether the IP is dedicated to you or shared, what happens on disconnect or renewal, and whether identity checks apply.

**Mobile.** The exit comes from a mobile carrier network, usually 4G or 5G. This is used for mobile ads, carrier-specific pages, and regional content that differs on cellular networks. Billing may be per gigabyte, per day, or per port. Check carrier and country stock, rotation rules, and usage limits, because mobile inventory is often thinner than residential pools.

None of these labels is a quality score. Whether a target accepts the request depends on the exit, the request pattern, and the target's own policy.

## Assignment: static, rotating, and sticky

Rotating usually means a new exit is chosen per request, or at a short interval. Sticky or static usually means the same exit is held for a session or a rental term. Providers do not all use these words the same way, and official pages sometimes give two different session lengths. If your task needs the same IP, get the exact hold time, the conditions that break it, and whether a replacement IP is guaranteed.

## ASN is not a fourth type

An [ASN](https://proxyvendors.com/glossary/asn) identifies the routing operator that announces an address block. It can be more precise than a country when you need one carrier's network. It is not a country, and it does not tell you whether the IP is residential or datacenter. Asking for one ASN also shrinks the pool; if no exit is available, the request can fail.

## After you pick a type, check the exit

Plan pages describe the product you intended to buy. The [IP check](https://proxyvendors.com/ip-check) shows the public IP, organisation, and ASN you actually received, plus optional DNS and WebRTC checks. If those results do not match the product you purchased, stop and resolve that before you scale up.

When you compare a specific plan, use the [buying checklist](./buying-checklist.md).

— Northleaf Studio
