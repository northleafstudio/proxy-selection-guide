# Tipos de proxy: red, asignación y protocolo

Esta guía la publica Northleaf Studio, que también opera [ProxyVendors](https://proxyvendors.com/es/), un directorio para comparar proveedores por tarea, sesión, ubicación y coste. Es material de contexto de la misma parte, no una reseña independiente de ese sitio ni de ningún proveedor. Las etiquetas de producto cambian, y dos páginas oficiales del mismo proveedor pueden discrepar. Úsela como un mapa de los términos y confirme los detalles en la documentación vigente del proveedor.

## Idiomas

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- **Español**
- [Deutsch](../../de/guides/proxy-types.md)
- [Français](../../fr/guides/proxy-types.md)
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

## Tres preguntas distintas

A menudo se meten tres preguntas en una sola palabra, «proxy»:

1. **¿De qué tipo de red sale la IP de salida?** Este es el sentido habitual de residencial, centro de datos, ISP y móvil.
2. **¿Cuánto tiempo permanece asignada la misma salida?** Esto es estático frente a rotativo, a veces llamado sesión persistente.
3. **¿Cómo se conecta el cliente?** Esto es HTTP, incluido el túnel [HTTP CONNECT](https://proxyvendors.com/es/glossary/http-connect) usado para HTTPS, o [SOCKS5](https://proxyvendors.com/es/glossary/socks5).

Una IP estática puede seguir compartiéndose con otros clientes. Un extremo SOCKS5 es un método de conexión, no un tipo de IP. La misma salida residencial o de centro de datos a menudo se alcanza por más de un protocolo, y algunos productos solo admiten HTTP o HTTPS.

## Tipos de red

**Residencial.** La salida está asociada a una red de consumo o de banda ancha. Es la opción habitual cuando el destino es sensible a los rangos de alojamiento, o cuando hace falta una ubicación que parezca una conexión doméstica ordinaria. El tráfico residencial suele cobrarse por gigabyte. Los grupos son compartidos y rotan, salvo que se compre una opción persistente o dedicada. La etiqueta es una clasificación del proveedor o de bases de datos de terceros; no es un campo que viaje en la propia IP.

**Centro de datos.** La salida procede de una red de alojamiento o de la nube. Estos productos suelen ser más baratos por unidad de tráfico o por IP, y pueden ofrecer más caudal para grandes volúmenes de peticiones. Muchos sitios tratan con más rigor los rangos de centro de datos. Antes de comprar un plan grande, compruebe si el destino devuelve contenido válido a través de ese tipo de salida.

**ISP, a veces vendido como residencial estático.** La dirección suele estar registrada a nombre de un proveedor de acceso residencial, mientras que el equipo proxy suele estar en un centro de datos. ISP describe ese registro; por sí solo no significa que la salida permanezca fija. Los vendedores suelen emparejar la etiqueta con una asignación de mayor duración, un encaje habitual para inicios de sesión, listas de IP permitidas y una ubicación fija. Confirme si la IP es dedicada o compartida, qué ocurre al desconectar o al renovar, y si hay comprobaciones de identidad.

**Móvil.** La salida procede de la red de un operador móvil, normalmente 4G o 5G. Se usa para anuncios móviles, páginas propias del operador y contenido regional que cambia en las redes celulares. El cobro puede ser por gigabyte, por día o por puerto. Revise el stock por operador y país, las reglas de rotación y los límites de uso, porque el inventario móvil suele ser más escaso que los grupos residenciales.

Ninguna de estas etiquetas es una puntuación de calidad. Que un destino acepte la petición depende de la salida, del patrón de peticiones y de la política del propio destino.

## Asignación: estática, rotativa y persistente

Rotativa suele significar que se elige una salida nueva en cada petición, o a intervalos cortos. Persistente o estática suele significar que la misma salida se mantiene durante una sesión o un periodo de alquiler. Los proveedores no usan estas palabras del mismo modo, y las páginas oficiales a veces dan dos duraciones de sesión distintas. Si la tarea necesita la misma IP, obtenga el tiempo exacto de retención, las condiciones que lo interrumpen y si se garantiza una IP de sustitución.

## El ASN no es un cuarto tipo

Un [ASN](https://proxyvendors.com/es/glossary/asn) identifica al operador de enrutamiento que anuncia un bloque de direcciones. Puede ser más preciso que un país cuando se necesita la red de un operador concreto. No es un país, y no indica si la IP es residencial o de centro de datos. Pedir un ASN también reduce el grupo disponible; si no hay salida, la petición puede fallar.

## Después de elegir un tipo, compruebe la salida

Las páginas de planes describen el producto que se pretendía comprar. La [comprobación de IP](https://proxyvendors.com/es/ip-check) muestra la IP pública, la organización y el ASN realmente recibidos, además de comprobaciones opcionales de DNS y WebRTC. Si esos resultados no coinciden con el producto comprado, deténgase y resuélvalo antes de ampliar el uso.

Cuando compare un plan concreto, use la [lista de compra](./buying-checklist.md).

— Northleaf Studio
