# Proxy-Typen: Netz, Zuweisung und Protokoll

Diesen Leitfaden veröffentlicht Northleaf Studio, das auch [ProxyVendors](https://proxyvendors.com/de/) betreibt, ein Verzeichnis zum Vergleichen von Anbietern nach Aufgabe, Sitzung, Ort und Kosten. Er ist Hintergrundmaterial derselben Stelle, keine unabhängige Prüfung dieser Website oder eines Anbieters durch einen unbeteiligten Dritten. Produktbezeichnungen ändern sich, und zwei offizielle Seiten desselben Anbieters können voneinander abweichen. Nutzen Sie den Text als Karte der Begriffe und prüfen Sie Einzelheiten in der aktuellen Dokumentation des Anbieters.

## Sprachen

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- [Español](../../es/guides/proxy-types.md)
- **Deutsch**
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

## Drei verschiedene Fragen

Oft werden drei Fragen in ein Wort gepackt, „Proxy“:

1. **Aus welcher Art von Netz kommt die Exit-IP?** Das ist die übliche Bedeutung von Privatanschluss, Rechenzentrum, ISP und Mobilfunk.
2. **Wie lange bleibt dieselbe Exit-IP zugewiesen?** Das ist statisch gegenüber rotierend, manchmal Sticky Session genannt.
3. **Wie verbindet sich der Client?** Das ist HTTP, einschließlich des [HTTP-CONNECT](https://proxyvendors.com/de/glossary/http-connect)-Tunnels für HTTPS, oder [SOCKS5](https://proxyvendors.com/de/glossary/socks5).

Eine statische IP kann trotzdem mit anderen Kunden geteilt sein. Ein SOCKS5-Endpunkt ist eine Verbindungsmethode, kein IP-Typ. Dieselbe privat oder im Rechenzentrum liegende Exit-IP ist oft über mehr als ein Protokoll erreichbar, und manche Produkte unterstützen nur HTTP oder HTTPS.

## Netzwerktypen

**Privatanschluss (Residential).** Die Exit-IP gehört zu einem Verbraucher- oder Breitbandnetz. Das ist die übliche Wahl, wenn ein Ziel Hosting-Bereiche empfindlich behandelt oder ein Ort wie ein gewöhnlicher Haushaltsanschluss aussehen soll. Residential-Traffic wird oft je Gigabyte berechnet. Die Pools sind geteilt und rotieren, sofern keine Sticky- oder dedizierte Option gekauft wird. Die Bezeichnung ist eine Einstufung des Anbieters oder einer Drittdatenbank; sie ist kein Feld, das die IP selbst mitführt.

**Rechenzentrum.** Die Exit-IP kommt aus einem Hosting- oder Cloud-Netz. Diese Produkte sind oft je Traffic-Einheit oder je IP günstiger und können bei vielen Anfragen mehr Durchsatz bieten. Viele Websites behandeln Rechenzentrumsbereiche strenger. Prüfen Sie vor einem großen Tarif, ob das Ziel über diese Art von Exit tatsächlich gültige Inhalte liefert.

**ISP, manchmal als statisches Residential verkauft.** Die Adresse ist typischerweise auf einen Internetzugangsanbieter für Haushalte registriert, während der Proxy-Host selbst oft in einem Rechenzentrum steht. ISP benennt diese Registrierung; daraus folgt für sich genommen nicht, dass die Exit-IP fest bleibt. Anbieter koppeln die Bezeichnung oft mit einer länger gehaltenen Zuweisung. Das passt häufig zu Anmeldungen, IP-Freigabelisten und einem festen Ort. Klären Sie, ob die IP exklusiv oder geteilt ist, was bei Trennung oder Verlängerung geschieht, und ob Identitätsprüfungen gelten.

**Mobilfunk.** Die Exit-IP kommt aus dem Netz eines Mobilfunkanbieters, meist 4G oder 5G. Das wird für mobile Anzeigen, anbieterspezifische Seiten und regionale Inhalte genutzt, die sich im Mobilfunk unterscheiden. Abgerechnet wird je Gigabyte, je Tag oder je Port. Prüfen Sie Bestand nach Anbieter und Land, Rotationsregeln und Nutzungslimits, denn mobiles Inventar ist oft knapper als Residential-Pools.

Keine dieser Bezeichnungen ist eine Qualitätsnote. Ob ein Ziel die Anfrage annimmt, hängt vom Exit, vom Anfragemuster und von der eigenen Richtlinie des Ziels ab.

## Zuweisung: statisch, rotierend und sticky

Rotierend heißt meist, dass je Anfrage oder in kurzem Abstand ein neuer Exit gewählt wird. Sticky oder statisch heißt meist, dass derselbe Exit für eine Sitzung oder eine Mietdauer gehalten wird. Anbieter verwenden diese Wörter nicht einheitlich, und offizielle Seiten nennen manchmal zwei verschiedene Sitzungsdauern. Wenn die Aufgabe dieselbe IP braucht, holen Sie die genaue Haltezeit, die Bedingungen, die sie beenden, und die Aussage, ob eine Ersatz-IP zugesichert ist.

## ASN ist kein vierter Typ

Eine [ASN](https://proxyvendors.com/de/glossary/asn) bezeichnet den Routing-Betreiber, der einen Adressblock ankündigt. Sie kann genauer sein als ein Land, wenn das Netz eines bestimmten Anbieters gebraucht wird. Sie ist kein Land und sagt nicht, ob die IP residential oder aus einem Rechenzentrum stammt. Die Vorgabe einer ASN verkleinert den Pool; fehlt ein Exit, kann die Anfrage scheitern.

## Nach der Typwahl den Exit prüfen

Tarifseiten beschreiben das Produkt, das gekauft werden sollte. Die [IP-Prüfung](https://proxyvendors.com/de/ip-check) zeigt die tatsächlich erhaltene öffentliche IP, die Organisation und die ASN, dazu optionale DNS- und WebRTC-Prüfungen. Passen die Ergebnisse nicht zum gekauften Produkt, halten Sie an und klären Sie das, bevor Sie die Menge erhöhen.

Wenn Sie einen konkreten Tarif vergleichen, nutzen Sie die [Einkaufsliste](./buying-checklist.md).

— Northleaf Studio
