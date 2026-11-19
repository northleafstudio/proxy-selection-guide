# Uma lista curta antes de comprar um plano de proxy

Esta lista é publicada pela Northleaf Studio, que também opera o [ProxyVendors](https://proxyvendors.com/pt/). É material complementar da mesma parte, não uma recomendação de um terceiro sem vínculo. Use-a diante da página de preços vigente, dos termos e de um teste pequeno. Ela não garante que um plano funcione para o seu destino.

## Idiomas

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- [日本語](../../ja/guides/buying-checklist.md)
- **Português**
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

## 1. Defina a tarefa e depois escolha a rede

Anote o que a saída precisa fazer: um login duradouro, dados públicos de uma região, alto volume de pedidos ou um teste numa operadora móvel. Relacione isso a um tipo de rede, como no [guia de tipos de proxy](./proxy-types.md): residencial, data center, ISP ou móvel. Se a página inicial e a página de preços anunciam preços iniciais ou quantidades de países diferentes, registre os dois e pergunte qual número vale para o nível exato que você compraria.

## 2. Verifique o comportamento da sessão

Decida se precisa da mesma saída por minutos, horas ou todo o aluguel, ou de uma saída nova a cada pedido. Confirme a duração persistente ou estática, o que a interrompe e se um IP que cai é substituído. A documentação oficial às vezes informa dois tempos de retenção; trate isso como não resolvido até o fornecedor confirmar.

## 3. Confirme protocolos e autenticação

HTTP, inclusive [HTTP CONNECT](https://proxyvendors.com/pt/glossary/http-connect) para sites HTTPS, não é o mesmo que [SOCKS5](https://proxyvendors.com/pt/glossary/socks5). Alguns produtos residenciais só aceitam HTTP e HTTPS. Se você precisa de SOCKS5, ou de UDP via SOCKS5, verifique se o produto e o seu cliente oferecem isso. Confirme o host de entrada, a porta e o método de autenticação: usuário e senha, uma lista de IP permitidos, ou ambos. Uma resposta 407 durante o CONNECT vem do proxy. O status significa Proxy Authentication Required: o proxy exige autenticação, ou não aceitou a autenticação que recebeu. O túnel não foi estabelecido, e o site de destino nunca viu o pedido.

## 4. Some o custo real

Olhe além do preço unitário do título. Anote a compra mínima, a validade ou o vencimento do pacote, taxas de excedente, desperdício com novas tentativas, acréscimos de segmentação fina, impostos e recargas ou renovações automáticas. Um preço de destaque pode pertencer a uma faixa de grande volume, não ao pacote com o qual você começaria. Se o teste exige um cartão e liga recargas automáticas, decida se vai desligá-las antes de começar.

## 5. Leia as regras de teste, reembolso e acesso

Verifique o tamanho e a duração do teste, a janela de reembolso, os limites de uso e se o reembolso exige uma falha de rede documentada. Observe verificações de identidade ou KYC, categorias bloqueadas, como sites bancários ou governamentais, e limites de uso justo em produtos estáticos ou dedicados. Se a origem ou a conformidade importam, peça documentação ao fornecedor em vez de depender só do texto de marketing.

## 6. Identifique a rede e depois teste

Se precisa de uma operadora específica, confirme que a [segmentação por ASN](https://proxyvendors.com/pt/glossary/asn) existe e o que acontece quando não há saída disponível. Depois rode uma tarefa real e pequena: respostas válidas do destino, quedas de sessão, precisão do local e tráfego de fato consumido. Depois de conectar, use a [verificação de IP](https://proxyvendors.com/pt/ip-check) para comparar o IP público, a organização e o ASN com o produto comprado, e execute as verificações de DNS e WebRTC se esses caminhos importarem.

Só então decida quanto comprar.

— Northleaf Studio
