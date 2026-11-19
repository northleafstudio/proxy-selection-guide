# Types de proxy : réseau, attribution et protocole

Ce guide est publié par Northleaf Studio, qui exploite aussi [ProxyVendors](https://proxyvendors.com/fr/), un annuaire pour comparer les fournisseurs selon la tâche, la session, le lieu et le coût. C’est un texte de contexte de la même partie, pas une revue indépendante de ce site ou d’un fournisseur par un tiers étranger. Les libellés changent, et deux pages officielles du même fournisseur peuvent diverger. Servez-vous-en comme d’une carte des termes, puis confirmez le détail dans la documentation actuelle du fournisseur.

## Langues

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- [Español](../../es/guides/proxy-types.md)
- [Deutsch](../../de/guides/proxy-types.md)
- **Français**
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

## Trois questions différentes

On réunit souvent trois questions dans un seul mot, « proxy » :

1. **De quel type de réseau vient l’IP de sortie ?** C’est le sens habituel de résidentiel, centre de données, FAI et mobile.
2. **Combien de temps la même sortie reste-t-elle attribuée ?** C’est l’opposition entre statique et tournant, parfois appelée session collante.
3. **Comment le client se connecte-t-il ?** C’est HTTP, y compris le tunnel [HTTP CONNECT](https://proxyvendors.com/fr/glossary/http-connect) utilisé pour HTTPS, ou [SOCKS5](https://proxyvendors.com/fr/glossary/socks5).

Une IP statique peut rester partagée avec d’autres clients. Un point d’accès SOCKS5 est une méthode de connexion, pas un type d’IP. La même sortie résidentielle ou de centre de données est souvent joignable par plus d’un protocole, et certains produits ne prennent en charge que HTTP ou HTTPS.

## Types de réseau

**Résidentiel.** La sortie est associée à un réseau grand public ou à une connexion large bande. C’est le choix habituel quand la cible est sensible aux plages d’hébergement, ou quand il faut un lieu qui ressemble à une connexion domestique ordinaire. Le trafic résidentiel est souvent facturé au gigaoctet. Les pools sont partagés et tournent, sauf option collante ou dédiée. L’étiquette est un classement du fournisseur ou d’une base tierce ; ce n’est pas un champ porté par l’IP elle-même.

**Centre de données.** La sortie vient d’un réseau d’hébergement ou de cloud. Ces produits sont souvent moins chers par unité de trafic ou par IP, et ils peuvent offrir un débit plus élevé pour de gros volumes de requêtes. Beaucoup de sites traitent plus strictement les plages de centres de données. Avant d’acheter une grande offre, vérifiez que la cible renvoie un contenu valide par ce type de sortie.

**FAI, parfois vendu comme résidentiel statique.** L’adresse est en général enregistrée auprès d’un fournisseur d’accès résidentiel, tandis que l’hôte du proxy se trouve souvent dans un centre de données. FAI désigne cet enregistrement ; cela ne signifie pas, à soi seul, que la sortie reste fixe. Les vendeurs associent souvent l’étiquette à une attribution plus longue, ce qui convient aux connexions de compte, aux listes d’IP autorisées et à un lieu fixe. Confirmez si l’IP vous est dédiée ou partagée, ce qui se passe à la déconnexion ou au renouvellement, et si des contrôles d’identité s’appliquent.

**Mobile.** La sortie vient du réseau d’un opérateur mobile, en général 4G ou 5G. On l’utilise pour la publicité mobile, les pages propres à un opérateur et les contenus régionaux qui diffèrent sur les réseaux cellulaires. La facturation peut être au gigaoctet, à la journée ou au port. Vérifiez le stock par opérateur et par pays, les règles de rotation et les limites d’usage, car l’inventaire mobile est souvent plus mince que les pools résidentiels.

Aucune de ces étiquettes n’est une note de qualité. L’acceptation d’une requête dépend de la sortie, du rythme des requêtes et de la politique de la cible.

## Attribution : statique, tournante et collante

Tournant signifie en général qu’une nouvelle sortie est choisie à chaque requête, ou à court intervalle. Collant ou statique signifie en général que la même sortie est conservée pour une session ou une durée de location. Les fournisseurs n’emploient pas ces mots de la même façon, et les pages officielles donnent parfois deux durées de session. Si la tâche exige la même IP, obtenez la durée exacte de maintien, les conditions qui l’interrompent et l’existence ou non d’une IP de remplacement garantie.

## L’ASN n’est pas un quatrième type

Un [ASN](https://proxyvendors.com/fr/glossary/asn) identifie l’opérateur de routage qui annonce un bloc d’adresses. Il peut être plus précis qu’un pays lorsqu’il faut le réseau d’un opérateur précis. Ce n’est pas un pays, et il ne dit pas si l’IP est résidentielle ou de centre de données. Demander un ASN réduit aussi le pool ; s’il n’y a pas de sortie disponible, la requête peut échouer.

## Après le choix du type, contrôlez la sortie

Les pages d’offres décrivent le produit que vous comptiez acheter. Le [contrôle d’IP](https://proxyvendors.com/fr/ip-check) montre l’IP publique, l’organisation et l’ASN réellement reçus, ainsi que des contrôles DNS et WebRTC facultatifs. Si ces résultats ne correspondent pas au produit acheté, arrêtez-vous et réglez cela avant d’augmenter le volume.

Pour comparer une offre précise, utilisez la [liste d’achat](./buying-checklist.md).

— Northleaf Studio
