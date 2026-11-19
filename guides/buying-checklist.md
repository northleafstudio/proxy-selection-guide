# A short checklist before you buy a proxy plan

This checklist is published by Northleaf Studio, which also operates [ProxyVendors](https://proxyvendors.com/). It is first-party companion material, not an unaffiliated third-party recommendation. Use it against the vendor's current pricing page, terms, and a small trial. It does not guarantee that a plan will work for your target.

## Languages

- **English**
- [简体中文](../zh-cn/guides/buying-checklist.md)
- [Español](../es/guides/buying-checklist.md)
- [Deutsch](../de/guides/buying-checklist.md)
- [Français](../fr/guides/buying-checklist.md)
- [日本語](../ja/guides/buying-checklist.md)
- [Português](../pt/guides/buying-checklist.md)
- [한국어](../ko/guides/buying-checklist.md)
- [اردو](../ur/guides/buying-checklist.md)
- [Bahasa Indonesia](../id/guides/buying-checklist.md)
- [Türkçe](../tr/guides/buying-checklist.md)
- [العربية](../ar/guides/buying-checklist.md)
- [Polski](../pl/guides/buying-checklist.md)
- [Italiano](../it/guides/buying-checklist.md)
- [ไทย](../th/guides/buying-checklist.md)
- [Українська](../uk/guides/buying-checklist.md)
- [Tiếng Việt](../vi/guides/buying-checklist.md)
- [Русский](../ru/guides/buying-checklist.md)

## 1. State the task, then pick the network

Write down what you need the exit to do: a long-lived login, geo-specific public data, high-volume requests, or a mobile-carrier test. Match that to a network type, as described in the [proxy types guide](./proxy-types.md): residential, datacenter, ISP, or mobile. If the vendor's homepage and pricing page advertise different starting prices or country counts, record both and ask which figure applies to the exact tier you would buy.

## 2. Check session behaviour

Decide whether you need the same exit for minutes, hours, or a full rental term, or a new exit on each request. Confirm the sticky or static duration, what breaks it, and whether a dropped IP is replaced. Official documentation sometimes gives two different hold times; treat that as unresolved until the vendor confirms it.

## 3. Confirm protocols and authentication

HTTP, including [HTTP CONNECT](https://proxyvendors.com/glossary/http-connect) for HTTPS sites, is not the same as [SOCKS5](https://proxyvendors.com/glossary/socks5). Some residential products support HTTP and HTTPS only. If you need SOCKS5, or UDP through SOCKS5, check that both the product and your client support it. Confirm the entry host, port, and authentication method: username and password, an IP allowlist, or both. A 407 response during CONNECT comes from the proxy. The status means Proxy Authentication Required: the proxy requires authentication, or it did not accept the authentication it received. The tunnel was not built, and the target site never saw the request.

## 4. Add up the real cost

Look past the headline unit price. Note the minimum purchase, pack validity or expiry, overage fees, retry waste, fine-targeting surcharges, VAT, and automatic top-ups or renewals. A headline price may belong to a large volume tier, not to the pack you would actually start with. If a trial requires a card and enables automatic top-ups, decide whether to switch those off before the trial starts.

## 5. Read the trial, refund, and access rules

Check the trial size and length, refund window, usage caps, and whether refunds require a documented network fault. Note any identity or KYC checks, blocked categories such as banking or government sites, and fair-use limits on static or dedicated products. If sourcing or compliance matters to you, ask the vendor for documentation rather than relying only on marketing copy.

## 6. Look up the network, then test

If you need a specific carrier, confirm that [ASN targeting](https://proxyvendors.com/glossary/asn) is supported and what happens when no exit is available. Then run a small, real task: valid responses from the target, session drops, location accuracy, and actual traffic consumed. After you connect, use the [IP check](https://proxyvendors.com/ip-check) to compare the public IP, organisation, and ASN with the product you purchased, and run the DNS and WebRTC checks if those paths matter.

Only then decide how much to buy.

— Northleaf Studio
