# Krótka lista przed zakupem planu proxy

Tę listę publikuje Northleaf Studio, które prowadzi też [ProxyVendors](https://proxyvendors.com/pl/). To materiał uzupełniający tej samej strony, a nie rekomendacja niepowiązanej osoby trzeciej. Zestaw ją z aktualną stroną cen dostawcy, warunkami i małą próbą. Nie gwarantuje, że plan zadziała dla twojego celu.

## Języki

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- [日本語](../../ja/guides/buying-checklist.md)
- [Português](../../pt/guides/buying-checklist.md)
- [한국어](../../ko/guides/buying-checklist.md)
- [اردو](../../ur/guides/buying-checklist.md)
- [Bahasa Indonesia](../../id/guides/buying-checklist.md)
- [Türkçe](../../tr/guides/buying-checklist.md)
- [العربية](../../ar/guides/buying-checklist.md)
- **Polski**
- [Italiano](../../it/guides/buying-checklist.md)
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- [Tiếng Việt](../../vi/guides/buying-checklist.md)
- [Русский](../../ru/guides/buying-checklist.md)

## 1. Opisz zadanie, potem wybierz sieć

Zapisz, co ma robić wyjście: długotrwałe logowanie, publiczne dane z określonego miejsca, duża liczba żądań albo test operatora komórkowego. Dopasuj to do typu sieci opisanego w [przewodniku po typach proxy](./proxy-types.md): domowy, centrum danych, ISP albo mobilny. Jeśli strona główna i strona cen podają różne ceny początkowe albo liczby krajów, zapisz obie i zapytaj, która liczba dotyczy dokładnie tego poziomu, który kupiłbyś.

## 2. Sprawdź zachowanie sesji

Zdecyduj, czy ten sam adres wyjścia jest potrzebny przez minuty, godziny albo cały najem, czy nowy przy każdym żądaniu. Potwierdź czas lepki albo statyczny, co go przerywa i czy utracony adres IP jest zastępowany. Oficjalna dokumentacja podaje czasem dwa czasy utrzymania; traktuj to jako nierozstrzygnięte, dopóki dostawca tego nie potwierdzi.

## 3. Potwierdź protokoły i uwierzytelnienie

HTTP, w tym [HTTP CONNECT](https://proxyvendors.com/pl/glossary/http-connect) dla witryn HTTPS, nie jest tym samym co [SOCKS5](https://proxyvendors.com/pl/glossary/socks5). Część produktów domowych obsługuje tylko HTTP i HTTPS. Jeśli potrzebujesz SOCKS5 albo UDP przez SOCKS5, sprawdź, czy obsługują to zarówno produkt, jak i klient. Potwierdź host wejściowy, port i metodę uwierzytelnienia: nazwa użytkownika i hasło, lista dozwolonych adresów IP albo oba sposoby. Odpowiedź 407 podczas CONNECT pochodzi od proxy. Status oznacza Proxy Authentication Required: proxy wymaga uwierzytelnienia albo nie przyjęło otrzymanego uwierzytelnienia. Tunel nie został zestawiony, a witryna docelowa nigdy nie zobaczyła żądania.

## 4. Zsumuj rzeczywisty koszt

Spójrz dalej niż na cenę jednostkową z nagłówka. Zapisz minimalny zakup, ważność albo wygaśnięcie pakietu, opłaty za przekroczenie, stratę na ponowieniach, dopłaty za wąskie kierowanie, VAT oraz automatyczne doładowania albo odnowienia. Wyróżniona cena może należeć do dużego progu wolumenu, a nie do pakietu, od którego byś zaczął. Jeśli próba wymaga karty i włącza automatyczne doładowania, zdecyduj przed startem, czy je wyłączyć.

## 5. Przeczytaj zasady próby, zwrotu i dostępu

Sprawdź wielkość i czas próby, okno zwrotu, limity użycia oraz to, czy zwrot wymaga udokumentowanej usterki sieci. Zwróć uwagę na kontrole tożsamości albo KYC, zablokowane kategorie, takie jak strony banków albo urzędów, i limity uczciwego użycia przy produktach statycznych albo dedykowanych. Jeśli pochodzenie albo zgodność mają dla ciebie znaczenie, poproś dostawcę o dokumenty, zamiast opierać się tylko na tekście marketingowym.

## 6. Ustal sieć, a potem przetestuj

Jeśli potrzebujesz konkretnego operatora, potwierdź, że [wybór według ASN](https://proxyvendors.com/pl/glossary/asn) jest dostępny i co się dzieje, gdy brakuje wyjścia. Potem wykonaj małe, prawdziwe zadanie: prawidłowe odpowiedzi celu, zrywanie sesji, dokładność lokalizacji i rzeczywiście zużyty ruch. Po połączeniu użyj [sprawdzenia IP](https://proxyvendors.com/pl/ip-check), aby porównać publiczny adres IP, organizację i ASN z kupionym produktem, a jeśli te ścieżki mają znaczenie, uruchom też sprawdzenia DNS i WebRTC.

Dopiero wtedy zdecyduj, ile kupić.

— Northleaf Studio
