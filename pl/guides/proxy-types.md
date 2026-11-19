# Typy proxy: sieć, przydział i protokół

Ten przewodnik publikuje Northleaf Studio, które prowadzi też [ProxyVendors](https://proxyvendors.com/pl/), katalog do porównywania dostawców według zadania, sesji, lokalizacji i kosztu. To materiał tła tej samej strony, a nie niezależna recenzja tej witryny albo dostawcy sporządzona przez niepowiązaną osobę trzecią. Etykiety produktów się zmieniają, a dwie oficjalne strony tego samego dostawcy mogą się różnić. Traktuj tekst jako mapę pojęć, a szczegóły potwierdź w aktualnej dokumentacji dostawcy.

## Języki

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- [Español](../../es/guides/proxy-types.md)
- [Deutsch](../../de/guides/proxy-types.md)
- [Français](../../fr/guides/proxy-types.md)
- [日本語](../../ja/guides/proxy-types.md)
- [Português](../../pt/guides/proxy-types.md)
- [한국어](../../ko/guides/proxy-types.md)
- [اردو](../../ur/guides/proxy-types.md)
- [Bahasa Indonesia](../../id/guides/proxy-types.md)
- [Türkçe](../../tr/guides/proxy-types.md)
- [العربية](../../ar/guides/proxy-types.md)
- **Polski**
- [Italiano](../../it/guides/proxy-types.md)
- [ไทย](../../th/guides/proxy-types.md)
- [Українська](../../uk/guides/proxy-types.md)
- [Tiếng Việt](../../vi/guides/proxy-types.md)
- [Русский](../../ru/guides/proxy-types.md)

## Trzy różne pytania

Ludzie często zamykają trzy pytania w jednym słowie, „proxy”:

1. **Z jakiej sieci pochodzi adres IP wyjścia?** To zwykłe znaczenie określeń: domowy, centrum danych, ISP i mobilny.
2. **Jak długo ten sam adres wyjścia pozostaje przydzielony?** To różnica między adresem statycznym a rotacyjnym, czasem nazywana sesją lepką.
3. **Jak łączy się klient?** To HTTP, w tym tunel [HTTP CONNECT](https://proxyvendors.com/pl/glossary/http-connect) używany dla HTTPS, albo [SOCKS5](https://proxyvendors.com/pl/glossary/socks5).

Statyczny adres IP nadal może być współdzielony z innymi klientami. Punkt końcowy SOCKS5 jest metodą połączenia, a nie typem IP. To samo wyjście domowe albo z centrum danych często da się osiągnąć więcej niż jednym protokołem, a część produktów obsługuje tylko HTTP albo HTTPS.

## Typy sieci

**Domowy.** Wyjście jest powiązane z siecią konsumencką albo szerokopasmową. To zwykły wybór, gdy cel jest wrażliwy na zakresy hostingowe albo gdy potrzebna jest lokalizacja wyglądająca jak zwykłe łącze domowe. Ruch domowy często rozlicza się za gigabajt. Pule są współdzielone i rotują, chyba że kupiono opcję lepką albo dedykowaną. Etykieta jest klasyfikacją dostawcy albo zewnętrznej bazy; nie jest polem niesionym przez sam adres IP.

**Centrum danych.** Wyjście pochodzi z sieci hostingowej albo chmurowej. Te produkty bywają tańsze za jednostkę ruchu albo za adres IP i mogą dawać większą przepustowość przy dużej liczbie żądań. Wiele witryn traktuje zakresy centrów danych surowiej. Zanim kupisz duży plan, sprawdź, czy cel zwraca prawidłową treść przez taki rodzaj wyjścia.

**ISP, czasem sprzedawany jako statyczny domowy.** Adres jest zwykle zarejestrowany na dostawcę dostępu dla gospodarstw domowych, a sam host proxy często stoi w centrum danych. ISP nazywa tę rejestrację; samo to nie oznacza, że wyjście pozostaje stałe. Sprzedawcy często łączą etykietę z dłuższym przydziałem, co pasuje do logowań, list dozwolonych adresów IP i stałej lokalizacji. Potwierdź, czy adres jest dedykowany czy współdzielony, co dzieje się przy rozłączeniu albo odnowieniu i czy obowiązują kontrole tożsamości.

**Mobilny.** Wyjście pochodzi z sieci operatora komórkowego, zwykle 4G albo 5G. Służy do reklam mobilnych, stron właściwych operatorowi i treści regionalnych, które różnią się w sieciach komórkowych. Rozliczenie może być za gigabajt, za dzień albo za port. Sprawdź zapas według operatora i kraju, zasady rotacji i limity użycia, bo zasób mobilny bywa cieńszy niż pule domowe.

Żadna z tych etykiet nie jest oceną jakości. To, czy cel przyjmie żądanie, zależy od wyjścia, wzorca żądań i własnej polityki celu.

## Przydział: statyczny, rotacyjny i lepki

Rotacyjny zwykle oznacza, że nowe wyjście jest wybierane przy każdym żądaniu albo w krótkim odstępie. Lepki albo statyczny zwykle oznacza, że to samo wyjście jest trzymane przez sesję albo okres najmu. Dostawcy nie używają tych słów tak samo, a strony oficjalne podają czasem dwa czasy sesji. Jeśli zadanie wymaga tego samego adresu IP, uzyskaj dokładny czas utrzymania, warunki, które go przerywają, i informację, czy adres zastępczy jest gwarantowany.

## ASN nie jest czwartym typem

[ASN](https://proxyvendors.com/pl/glossary/asn) wskazuje operatora routingu, który ogłasza blok adresów. Może być dokładniejszy niż kraj, gdy potrzebna jest sieć jednego operatora. Nie jest krajem i nie mówi, czy adres IP jest domowy czy z centrum danych. Żądanie jednego ASN zmniejsza też pulę; gdy brakuje wyjścia, żądanie może się nie powieść.

## Po wyborze typu sprawdź wyjście

Strony planów opisują produkt, który zamierzano kupić. [Sprawdzenie IP](https://proxyvendors.com/pl/ip-check) pokazuje rzeczywiście otrzymany publiczny adres IP, organizację i ASN oraz opcjonalne sprawdzenia DNS i WebRTC. Jeśli wyniki nie zgadzają się z kupionym produktem, zatrzymaj się i wyjaśnij to, zanim zwiększysz skalę.

Gdy porównujesz konkretny plan, użyj [listy zakupowej](./buying-checklist.md).

— Northleaf Studio
