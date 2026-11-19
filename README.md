# Proxy notes from Northleaf Studio

This repository collects a short set of evergreen notes on proxy IP types, connection methods, and a practical buying checklist. It is published by **Northleaf Studio**, which also operates [ProxyVendors](https://proxyvendors.com/), a directory and comparison site for proxy providers.

These notes are first-party companion material. They are not an unaffiliated third-party review, and they are not an independent endorsement of any vendor. Where a point comes from a provider's documentation, treat that vendor's current page as the source of truth. Plan pages and help articles can disagree with each other, and both can change.

## What this repository is for

The notes restate a few distinctions already explained on ProxyVendors: a network type is not a connection protocol, an ASN is not a country or an IP type, and several checks matter before you purchase traffic. They are a short adaptation of that background, written so the distinctions can be read on their own, with links to the longer pages on the main site.

## Files

- [Proxy types](guides/proxy-types.md) — residential, datacenter, ISP, and mobile exits, plus static versus rotating assignment.
- [Buying checklist](guides/buying-checklist.md) — cost, session, protocol, and verification checks before you buy.

## Further reading on ProxyVendors

These public pages go into more detail than the notes here:

- [ASN and ASN targeting](https://proxyvendors.com/glossary/asn) — an ASN names a routing operator, not a country or an IP type.
- [HTTP CONNECT tunnel](https://proxyvendors.com/glossary/http-connect) — how an HTTP proxy reaches an HTTPS site, and why a 407 comes from the proxy.
- [SOCKS5 proxy protocol](https://proxyvendors.com/glossary/socks5) — a connection method that relays bytes; it is not a class of exit IP.
- [Exit IP check](https://proxyvendors.com/ip-check) — inspect the public IP, organisation, and ASN you received, with optional DNS and WebRTC checks.

## How to use the notes

Read the [proxy types guide](guides/proxy-types.md) first if the product labels are unclear, then use the [buying checklist](guides/buying-checklist.md) against a vendor's current pricing page, terms, and a small real-task trial. After you connect, confirm the exit on the IP check page rather than trusting only the plan description.

If you find an error in these notes, prefer the live ProxyVendors glossary and provider pages over this snapshot.

— Northleaf Studio
