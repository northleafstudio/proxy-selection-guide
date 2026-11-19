# Une courte liste avant d’acheter une offre de proxy

Cette liste est publiée par Northleaf Studio, qui exploite aussi [ProxyVendors](https://proxyvendors.com/fr/). C’est un complément de la même partie, pas une recommandation d’un tiers étranger au site. Appliquez-la à la page de prix actuelle du fournisseur, à ses conditions et à un petit essai. Elle ne garantit pas qu’une offre fonctionnera pour votre cible.

## Langues

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- **Français**
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

## 1. Posez la tâche, puis choisissez le réseau

Notez ce que la sortie doit faire : une connexion de compte durable, des données publiques d’une zone précise, un fort volume de requêtes, ou un test chez un opérateur mobile. Faites correspondre cela à un type de réseau, comme dans le [guide des types de proxy](./proxy-types.md) : résidentiel, centre de données, FAI ou mobile. Si la page d’accueil et la page de prix annoncent des prix de départ ou des nombres de pays différents, notez les deux et demandez quel chiffre s’applique au palier exact que vous achèteriez.

## 2. Vérifiez le comportement de session

Décidez s’il vous faut la même sortie pendant des minutes, des heures ou toute la location, ou une nouvelle sortie à chaque requête. Confirmez la durée collante ou statique, ce qui l’interrompt, et si une IP perdue est remplacée. La documentation officielle donne parfois deux durées de maintien ; considérez le point comme non tranché tant que le fournisseur ne l’a pas confirmé.

## 3. Confirmez les protocoles et l’authentification

HTTP, y compris [HTTP CONNECT](https://proxyvendors.com/fr/glossary/http-connect) pour les sites HTTPS, n’est pas la même chose que [SOCKS5](https://proxyvendors.com/fr/glossary/socks5). Certains produits résidentiels ne prennent en charge que HTTP et HTTPS. S’il vous faut SOCKS5, ou de l’UDP via SOCKS5, vérifiez que le produit et votre client le permettent. Confirmez l’hôte d’entrée, le port et la méthode d’authentification : nom d’utilisateur et mot de passe, une liste d’IP autorisées, ou les deux. Une réponse 407 pendant CONNECT vient du proxy. Le statut signifie Proxy Authentication Required : le proxy exige une authentification, ou il n’a pas accepté l’authentification reçue. Le tunnel n’a pas été établi, et le site cible n’a jamais vu la requête.

## 4. Additionnez le coût réel

Regardez au-delà du prix unitaire mis en avant. Notez l’achat minimal, la validité ou l’expiration du pack, les frais de dépassement, le trafic perdu en nouvelles tentatives, les suppléments de ciblage fin, la TVA, ainsi que les recharges ou renouvellements automatiques. Un prix affiché peut appartenir à un palier de gros volume, pas au pack par lequel vous commenceriez. Si un essai exige une carte et active les recharges automatiques, décidez de les couper avant de commencer.

## 5. Lisez les règles d’essai, de remboursement et d’accès

Vérifiez la taille et la durée de l’essai, la fenêtre de remboursement, les plafonds d’usage, et si le remboursement exige une panne réseau documentée. Notez les contrôles d’identité ou KYC, les catégories bloquées comme les sites bancaires ou publics, et les limites d’usage raisonnable sur les produits statiques ou dédiés. Si l’origine ou la conformité vous importe, demandez des documents au fournisseur plutôt que de vous fier au seul texte commercial.

## 6. Identifiez le réseau, puis testez

S’il vous faut un opérateur précis, confirmez que le [ciblage par ASN](https://proxyvendors.com/fr/glossary/asn) est pris en charge et ce qui se passe lorsqu’aucune sortie n’est disponible. Lancez ensuite une petite tâche réelle : réponses valides de la cible, ruptures de session, exactitude du lieu et trafic réellement consommé. Après la connexion, utilisez le [contrôle d’IP](https://proxyvendors.com/fr/ip-check) pour comparer l’IP publique, l’organisation et l’ASN au produit acheté, et lancez les contrôles DNS et WebRTC si ces chemins comptent.

Décidez seulement ensuite du volume à acheter.

— Northleaf Studio
