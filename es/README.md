# Notas sobre proxies de Northleaf Studio

Este repositorio reúne unas notas duraderas sobre tipos de IP de proxy, métodos de conexión y una lista práctica para comprar. Lo publica **Northleaf Studio**, que también opera [ProxyVendors](https://proxyvendors.com/es/), un directorio para comparar proveedores de proxy.

## Idiomas

- [English](../README.md)
- [简体中文](../zh-cn/README.md)
- **Español**
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
- [Italiano](../it/README.md)
- [ไทย](../th/README.md)
- [Українська](../uk/README.md)
- [Tiếng Việt](../vi/README.md)
- [Русский](../ru/README.md)

Estas notas son material complementario de la misma parte. No son una reseña de un tercero ajeno al sitio, ni un respaldo independiente de ningún proveedor. Si un dato procede de la documentación de un proveedor, la página vigente de ese proveedor es la referencia. Las páginas de planes y los artículos de ayuda pueden contradecirse, y ambos pueden cambiar.

## Para qué sirve este repositorio

Las notas retoman unas distinciones que ProxyVendors ya explica: el tipo de red no es un protocolo de conexión, un ASN no es un país ni un tipo de IP, y conviene hacer varias comprobaciones antes de comprar tráfico. Son una adaptación breve de ese contexto, escrita para leerse por sí sola, con enlaces a las páginas más largas del sitio principal.

## Archivos

- [Tipos de proxy](guides/proxy-types.md) — salidas residenciales, de centro de datos, ISP y móviles, y asignación estática frente a rotativa.
- [Lista de compra](guides/buying-checklist.md) — comprobaciones de coste, sesión, protocolo y verificación antes de comprar.

## Lectura adicional en ProxyVendors

Estas páginas públicas entran en más detalle que estas notas:

- [ASN y segmentación por ASN](https://proxyvendors.com/es/glossary/asn) — un ASN nombra al operador de enrutamiento, no un país ni un tipo de IP.
- [Túnel HTTP CONNECT](https://proxyvendors.com/es/glossary/http-connect) — cómo un proxy HTTP llega a un sitio HTTPS, y por qué un 407 significa que el proxy exige autenticación o no aceptó la que recibió.
- [Protocolo de proxy SOCKS5](https://proxyvendors.com/es/glossary/socks5) — un método de conexión que retransmite bytes; no es una clase de IP de salida.
- [Comprobación de la IP de salida](https://proxyvendors.com/es/ip-check) — revise la IP pública, la organización y el ASN recibidos, con comprobaciones opcionales de DNS y WebRTC.

## Cómo usar las notas

Si las etiquetas del producto no están claras, lea primero la [guía de tipos de proxy](guides/proxy-types.md) y después aplique la [lista de compra](guides/buying-checklist.md) a la página de precios vigente, a las condiciones y a una prueba pequeña con la tarea real. Después de conectar, confirme la salida en la página de comprobación de IP en lugar de fiarse solo de la descripción del plan.

Si encuentra un error en estas notas, prefiera el glosario vivo de ProxyVendors y las páginas del proveedor.

— Northleaf Studio
