# Eine kurze Liste vor dem Kauf eines Proxy-Tarifs

Diese Liste veröffentlicht Northleaf Studio, das auch [ProxyVendors](https://proxyvendors.com/de/) betreibt. Sie ist Begleitmaterial derselben Stelle, keine Empfehlung eines unbeteiligten Dritten. Legen Sie sie neben die aktuelle Preisseite, die Bedingungen und einen kleinen Test. Sie garantiert nicht, dass ein Tarif für Ihr Ziel funktioniert.

## Sprachen

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- **Deutsch**
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

## 1. Aufgabe benennen, dann das Netz wählen

Notieren Sie, was der Exit tun soll: eine langlebige Anmeldung, öffentliche Daten eines bestimmten Orts, viele Anfragen oder ein Test im Mobilfunknetz. Ordnen Sie das einem Netzwerktyp zu, wie im [Leitfaden zu den Proxy-Typen](./proxy-types.md) beschrieben: Privatanschluss, Rechenzentrum, ISP oder Mobilfunk. Wenn Startseite und Preisseite unterschiedliche Einstiegspreise oder Länderzahlen nennen, schreiben Sie beide auf und fragen Sie, welche Zahl für die genaue Stufe gilt, die Sie kaufen würden.

## 2. Das Sitzungsverhalten prüfen

Entscheiden Sie, ob Sie denselben Exit für Minuten, Stunden oder die ganze Mietdauer brauchen oder bei jeder Anfrage einen neuen. Bestätigen Sie die Sticky- oder statische Dauer, was sie beendet, und ob eine ausgefallene IP ersetzt wird. Offizielle Dokumentation nennt manchmal zwei verschiedene Haltezeiten; lassen Sie den Punkt offen, bis der Anbieter ihn bestätigt.

## 3. Protokolle und Authentifizierung bestätigen

HTTP, einschließlich [HTTP CONNECT](https://proxyvendors.com/de/glossary/http-connect) für HTTPS-Websites, ist nicht dasselbe wie [SOCKS5](https://proxyvendors.com/de/glossary/socks5). Manche Residential-Produkte unterstützen nur HTTP und HTTPS. Wenn Sie SOCKS5 brauchen, oder UDP über SOCKS5, prüfen Sie, ob Produkt und Client das unterstützen. Bestätigen Sie Eingangshost, Port und Authentifizierung: Benutzername und Passwort, eine IP-Freigabeliste oder beides. Eine 407-Antwort während CONNECT kommt vom Proxy. Der Status bedeutet Proxy Authentication Required: Der Proxy verlangt Authentifizierung, oder er hat die erhaltene Authentifizierung nicht angenommen. Der Tunnel wurde nicht aufgebaut, und die Zielwebsite hat die Anfrage nie gesehen.

## 4. Die echten Kosten zusammenzählen

Schauen Sie über den hervorgehobenen Stückpreis hinaus. Notieren Sie die Mindestabnahme, die Gültigkeit oder das Ablaufdatum des Pakets, Mehrnutzungsgebühren, Verlust durch Wiederholungen, Aufschläge für feine Zielauswahl, die Mehrwertsteuer und automatische Aufladungen oder Verlängerungen. Ein hervorgehobener Preis kann zu einer großen Mengenstufe gehören, nicht zu dem Paket, mit dem Sie anfangen würden. Wenn ein Test eine Karte verlangt und automatische Aufladungen einschaltet, entscheiden Sie vor dem Start, ob Sie das abschalten.

## 5. Test, Erstattung und Zugangsregeln lesen

Prüfen Sie Umfang und Dauer des Tests, das Erstattungsfenster, Nutzungslimits und ob eine Erstattung einen dokumentierten Netzfehler voraussetzt. Beachten Sie Identitäts- oder KYC-Prüfungen, gesperrte Kategorien wie Bank- oder Behördenseiten und Fair-Use-Grenzen bei statischen oder dedizierten Produkten. Wenn Herkunft oder Compliance für Sie zählen, verlangen Sie Unterlagen vom Anbieter, statt sich nur auf Werbetext zu stützen.

## 6. Das Netz nachschlagen und dann testen

Wenn Sie einen bestimmten Anbieter brauchen, bestätigen Sie, dass [ASN-Targeting](https://proxyvendors.com/de/glossary/asn) unterstützt wird und was geschieht, wenn kein Exit verfügbar ist. Führen Sie danach eine kleine, echte Aufgabe aus: gültige Antworten des Ziels, Sitzungsabbrüche, Genauigkeit des Orts und tatsächlich verbrauchter Traffic. Vergleichen Sie nach dem Verbinden mit der [IP-Prüfung](https://proxyvendors.com/de/ip-check) öffentliche IP, Organisation und ASN mit dem gekauften Produkt, und führen Sie die DNS- und WebRTC-Prüfungen aus, wenn diese Wege wichtig sind.

Entscheiden Sie erst dann, wie viel Sie kaufen.

— Northleaf Studio
