# Notas sobre proxy da Northleaf Studio

Este repositório reúne notas duráveis sobre tipos de IP de proxy, métodos de conexão e uma lista prática de compra. Quem publica é a **Northleaf Studio**, que também opera o [ProxyVendors](https://proxyvendors.com/pt/), um diretório para comparar fornecedores de proxy.

## Idiomas

- [English](../README.md)
- [简体中文](../zh-cn/README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [日本語](../ja/README.md)
- **Português**
- [한국어](../ko/README.md)
- [اردو](../ur/README.md)
- [Bahasa Indonesia](../id/README.md)
- [Türkçe](../tr/README.md)
- [العربية](../ar/README.md)
- [Polski](../pl/README.md)
- [Italiano](../it/README.md)
- [ไทย](../th/README.md)
- [Українська](../uk/README.md)
- [Tiếng Việt](../vi/README.md)
- [Русский](../ru/README.md)

Estas notas são material complementar da mesma parte. Não são uma análise de um terceiro sem vínculo com o site, nem um endosso independente de fornecedor. Quando um ponto vem da documentação de um fornecedor, a página atual desse fornecedor é a referência. Páginas de planos e artigos de ajuda podem divergir, e ambos podem mudar.

## Para que serve este repositório

As notas retomam distinções que o ProxyVendors já explica: o tipo de rede não é um protocolo de conexão, um ASN não é um país nem um tipo de IP, e várias verificações importam antes de comprar tráfego. São uma adaptação curta desse contexto, escrita para ser lida sozinha, com links para as páginas mais longas do site principal.

## Arquivos

- [Tipos de proxy](guides/proxy-types.md) — saídas residenciais, de data center, ISP e móveis, além da atribuição estática ou rotativa.
- [Lista de compra](guides/buying-checklist.md) — verificações de custo, sessão, protocolo e conferência antes da compra.

## Leitura adicional no ProxyVendors

Estas páginas públicas detalham mais do que as notas daqui:

- [ASN e segmentação por ASN](https://proxyvendors.com/pt/glossary/asn) — um ASN nomeia o operador de roteamento, não um país nem um tipo de IP.
- [Túnel HTTP CONNECT](https://proxyvendors.com/pt/glossary/http-connect) — como um proxy HTTP alcança um site HTTPS, e por que um 407 significa que o proxy exige autenticação ou não aceitou a autenticação recebida.
- [Protocolo de proxy SOCKS5](https://proxyvendors.com/pt/glossary/socks5) — um método de conexão que retransmite bytes; não é uma classe de IP de saída.
- [Verificação da IP de saída](https://proxyvendors.com/pt/ip-check) — a IP pública, a organização e o ASN realmente recebidos, com verificações opcionais de DNS e WebRTC.

## Como usar as notas

Se os rótulos do produto estiverem pouco claros, leia primeiro o [guia de tipos de proxy](guides/proxy-types.md) e depois aplique a [lista de compra](guides/buying-checklist.md) à página de preços vigente, aos termos e a um teste pequeno com a tarefa real. Depois de conectar, confirme a saída na página de verificação de IP em vez de confiar apenas na descrição do plano.

Se houver um erro nestas notas, prefira o glossário atual do ProxyVendors e as páginas do fornecedor.

— Northleaf Studio
