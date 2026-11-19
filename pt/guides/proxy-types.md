# Tipos de proxy: rede, atribuição e protocolo

Este guia é publicado pela Northleaf Studio, que também opera o [ProxyVendors](https://proxyvendors.com/pt/), um diretório para comparar fornecedores por tarefa, sessão, local e custo. É material de contexto da mesma parte, não uma análise independente desse site ou de um fornecedor feita por um terceiro sem vínculo. Os rótulos mudam, e duas páginas oficiais do mesmo fornecedor podem divergir. Use o texto como um mapa dos termos e confirme os detalhes na documentação atual do fornecedor.

## Idiomas

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- [Español](../../es/guides/proxy-types.md)
- [Deutsch](../../de/guides/proxy-types.md)
- [Français](../../fr/guides/proxy-types.md)
- [日本語](../../ja/guides/proxy-types.md)
- **Português**
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

## Três perguntas diferentes

Muitas vezes três perguntas cabem numa só palavra, “proxy”:

1. **De que tipo de rede vem o IP de saída?** Esse é o sentido usual de residencial, data center, ISP e móvel.
2. **Por quanto tempo a mesma saída permanece atribuída?** Isso é estático diante de rotativo, às vezes chamado de sessão persistente.
3. **Como o cliente se conecta?** Isso é HTTP, inclusive o túnel [HTTP CONNECT](https://proxyvendors.com/pt/glossary/http-connect) usado para HTTPS, ou [SOCKS5](https://proxyvendors.com/pt/glossary/socks5).

Um IP estático ainda pode ser compartilhado com outros clientes. Um endpoint SOCKS5 é um método de conexão, não um tipo de IP. A mesma saída residencial ou de data center muitas vezes pode ser alcançada por mais de um protocolo, e alguns produtos só aceitam HTTP ou HTTPS.

## Tipos de rede

**Residencial.** A saída está associada a uma rede de consumo ou de banda larga. É a escolha usual quando o destino é sensível a faixas de hospedagem, ou quando é preciso um local que pareça uma conexão doméstica comum. O tráfego residencial costuma ser cobrado por gigabyte. Os pools são compartilhados e rotacionam, salvo uma opção persistente ou dedicada. O rótulo é uma classificação do fornecedor ou de bases de terceiros; não é um campo carregado pelo próprio IP.

**Data center.** A saída vem de uma rede de hospedagem ou nuvem. Esses produtos costumam ser mais baratos por unidade de tráfego ou por IP, e podem oferecer mais vazão para grandes volumes de pedidos. Muitos sites tratam faixas de data center com mais rigor. Antes de comprar um plano grande, verifique se o destino devolve conteúdo válido por esse tipo de saída.

**ISP, às vezes vendido como residencial estático.** O endereço em geral está registrado em nome de um provedor de acesso residencial, enquanto o host do proxy fica muitas vezes num data center. ISP nomeia esse registro; por si só, não significa que a saída permaneça fixa. Os vendedores costumam juntar o rótulo a uma atribuição mais longa, um encaixe comum para logins, listas de IP permitidos e um local fixo. Confirme se o IP é dedicado ou compartilhado, o que acontece na desconexão ou na renovação, e se há verificação de identidade.

**Móvel.** A saída vem da rede de uma operadora móvel, em geral 4G ou 5G. Serve para anúncios móveis, páginas específicas da operadora e conteúdo regional que muda nas redes celulares. A cobrança pode ser por gigabyte, por dia ou por porta. Confira o estoque por operadora e país, as regras de rotação e os limites de uso, porque o inventário móvel costuma ser mais escasso que os pools residenciais.

Nenhum desses rótulos é uma nota de qualidade. O destino aceitar o pedido depende da saída, do padrão de pedidos e da política do próprio destino.

## Atribuição: estática, rotativa e persistente

Rotativo em geral significa que uma nova saída é escolhida a cada pedido, ou em intervalo curto. Persistente ou estático em geral significa que a mesma saída é mantida por uma sessão ou por um prazo de aluguel. Os fornecedores não usam essas palavras do mesmo modo, e páginas oficiais às vezes informam duas durações de sessão. Se a tarefa precisa do mesmo IP, obtenha o tempo exato de retenção, as condições que o interrompem e se um IP substituto é garantido.

## ASN não é um quarto tipo

Um [ASN](https://proxyvendors.com/pt/glossary/asn) identifica o operador de roteamento que anuncia um bloco de endereços. Pode ser mais preciso que um país quando é preciso a rede de uma operadora específica. Não é um país e não diz se o IP é residencial ou de data center. Pedir um ASN também reduz o pool; se não houver saída disponível, o pedido pode falhar.

## Depois de escolher o tipo, confira a saída

As páginas de planos descrevem o produto que se pretendia comprar. A [verificação de IP](https://proxyvendors.com/pt/ip-check) mostra o IP público, a organização e o ASN realmente recebidos, além de verificações opcionais de DNS e WebRTC. Se esses resultados não baterem com o produto comprado, pare e resolva isso antes de aumentar o volume.

Ao comparar um plano específico, use a [lista de compra](./buying-checklist.md).

— Northleaf Studio
