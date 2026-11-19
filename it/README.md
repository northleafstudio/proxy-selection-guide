# Note sui proxy di Northleaf Studio

Questo repository raccoglie note durature sui tipi di IP proxy, sui metodi di connessione e su una lista pratica per l’acquisto. Lo pubblica **Northleaf Studio**, che gestisce anche [ProxyVendors](https://proxyvendors.com/it/), una directory per confrontare i fornitori di proxy.

## Lingue

- [English](../README.md)
- [简体中文](../zh-cn/README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [日本語](../ja/README.md)
- [Português](../pt/README.md)
- [한국어](../ko/README.md)
- [اردو](../ur/README.md)
- [Bahasa Indonesia](../id/README.md)
- [Türkçe](../tr/README.md)
- [العربية](../ar/README.md)
- [Polski](../pl/README.md)
- **Italiano**
- [ไทย](../th/README.md)
- [Українська](../uk/README.md)
- [Tiếng Việt](../vi/README.md)
- [Русский](../ru/README.md)

Queste note sono materiale di accompagnamento della stessa parte. Non sono una recensione di un terzo estraneo al sito e non sono un avallo indipendente di alcun fornitore. Se un punto proviene dalla documentazione di un fornitore, fa fede la pagina attuale di quel fornitore. Le pagine dei piani e gli articoli di aiuto possono contraddirsi, ed entrambi possono cambiare.

## A che serve questo repository

Le note riprendono alcune distinzioni già spiegate su ProxyVendors: un tipo di rete non è un protocollo di connessione, un ASN non è un paese né un tipo di IP, e prima di acquistare traffico contano diversi controlli. Sono un adattamento breve di quello sfondo, scritto per essere letto da solo, con collegamenti alle pagine più lunghe del sito principale.

## File

- [Tipi di proxy](guides/proxy-types.md) — uscite residenziali, di data center, ISP e mobili, più l’assegnazione statica rispetto a quella rotante.
- [Lista per l’acquisto](guides/buying-checklist.md) — controlli su costo, sessione, protocollo e verifica prima dell’acquisto.

## Approfondimenti su ProxyVendors

Queste pagine pubbliche entrano più nel dettaglio delle note qui:

- [ASN e targeting per ASN](https://proxyvendors.com/it/glossary/asn) — un ASN nomina l’operatore di routing, non un paese e non un tipo di IP.
- [Tunnel HTTP CONNECT](https://proxyvendors.com/it/glossary/http-connect) — come un proxy HTTP raggiunge un sito HTTPS e perché un 407 significa che il proxy richiede l’autenticazione oppure non ha accettato quella ricevuta.
- [Protocollo proxy SOCKS5](https://proxyvendors.com/it/glossary/socks5) — un metodo di connessione che inoltra byte; non è una classe di IP di uscita.
- [Controllo dell’IP di uscita](https://proxyvendors.com/it/ip-check) — l’IP pubblico, l’organizzazione e l’ASN realmente ricevuti, con controlli facoltativi di DNS e WebRTC.

## Come usare le note

Se le etichette del prodotto non sono chiare, leggi prima la [guida ai tipi di proxy](guides/proxy-types.md), poi applica la [lista per l’acquisto](guides/buying-checklist.md) alla pagina dei prezzi vigente, alle condizioni e a una piccola prova sul compito reale. Dopo la connessione, conferma l’uscita nella pagina di controllo dell’IP invece di fidarti solo della descrizione del piano.

Se trovi un errore in queste note, preferisci il glossario vivo di ProxyVendors e le pagine del fornitore.

— Northleaf Studio
