# Una lista breve antes de comprar un plan de proxy

Esta lista la publica Northleaf Studio, que también opera [ProxyVendors](https://proxyvendors.com/es/). Es material complementario de la misma parte, no una recomendación de un tercero ajeno. Úsela frente a la página de precios vigente del proveedor, sus condiciones y una prueba pequeña. No garantiza que un plan funcione con su destino.

## Idiomas

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- **Español**
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
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

## 1. Defina la tarea y después elija la red

Anote qué debe hacer la salida: un inicio de sesión duradero, datos públicos de una zona concreta, un gran volumen de peticiones o una prueba con un operador móvil. Empareje eso con un tipo de red, como se describe en la [guía de tipos de proxy](./proxy-types.md): residencial, centro de datos, ISP o móvil. Si la portada y la página de precios anuncian precios de partida o números de países distintos, anote ambos y pregunte cuál corresponde al nivel exacto que compraría.

## 2. Compruebe el comportamiento de la sesión

Decida si necesita la misma salida durante minutos, horas o todo el alquiler, o una salida nueva en cada petición. Confirme la duración persistente o estática, qué la interrumpe y si una IP caída se sustituye. La documentación oficial a veces da dos tiempos de retención distintos; déjelo como no resuelto hasta que el proveedor lo confirme.

## 3. Confirme protocolos y autenticación

HTTP, incluido [HTTP CONNECT](https://proxyvendors.com/es/glossary/http-connect) para sitios HTTPS, no es lo mismo que [SOCKS5](https://proxyvendors.com/es/glossary/socks5). Algunos productos residenciales solo admiten HTTP y HTTPS. Si necesita SOCKS5, o UDP a través de SOCKS5, compruebe que tanto el producto como su cliente lo admiten. Confirme el host de entrada, el puerto y el método de autenticación: usuario y contraseña, una lista de IP permitidas, o ambos. Una respuesta 407 durante CONNECT proviene del proxy. El estado significa Proxy Authentication Required: el proxy exige autenticación, o no aceptó la autenticación que recibió. El túnel no se estableció, y el sitio de destino nunca vio la petición.

## 4. Sume el coste real

Mire más allá del precio unitario del titular. Anote la compra mínima, la vigencia o caducidad del paquete, los recargos por exceso, el tráfico perdido en reintentos, los suplementos por segmentación fina, el IVA y las recargas o renovaciones automáticas. Un precio destacado puede pertenecer a un tramo de gran volumen, no al paquete con el que empezaría. Si la prueba exige una tarjeta y activa recargas automáticas, decida si las desactiva antes de empezar.

## 5. Lea las reglas de prueba, reembolso y acceso

Revise el tamaño y la duración de la prueba, el plazo de reembolso, los topes de uso y si el reembolso exige una avería de red documentada. Tenga en cuenta las comprobaciones de identidad o KYC, las categorías bloqueadas, como sitios bancarios o gubernamentales, y los límites de uso razonable en productos estáticos o dedicados. Si el origen o el cumplimiento le importan, pida documentación al proveedor en lugar de basarse solo en el texto comercial.

## 6. Identifique la red y después pruebe

Si necesita un operador concreto, confirme que la [segmentación por ASN](https://proxyvendors.com/es/glossary/asn) está disponible y qué ocurre cuando no hay salida. Después ejecute una tarea real y pequeña: respuestas válidas del destino, caídas de sesión, exactitud de la ubicación y tráfico realmente consumido. Tras conectar, use la [comprobación de IP](https://proxyvendors.com/es/ip-check) para comparar la IP pública, la organización y el ASN con el producto comprado, y ejecute las comprobaciones de DNS y WebRTC si esas rutas importan.

Solo entonces decida cuánto comprar.

— Northleaf Studio
