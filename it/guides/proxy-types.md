# Tipi di proxy: rete, assegnazione e protocollo

Questa guida è pubblicata da Northleaf Studio, che gestisce anche [ProxyVendors](https://proxyvendors.com/it/), una directory per confrontare i fornitori per compito, sessione, luogo e costo. È materiale di contesto della stessa parte, non una recensione indipendente di quel sito o di un fornitore fatta da un terzo estraneo. Le etichette dei prodotti cambiano e due pagine ufficiali dello stesso fornitore possono divergere. Usala come mappa dei termini, poi conferma i dettagli nella documentazione attuale del fornitore.

## Lingue

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
- [Polski](../../pl/guides/proxy-types.md)
- **Italiano**
- [ไทย](../../th/guides/proxy-types.md)
- [Українська](../../uk/guides/proxy-types.md)
- [Tiếng Việt](../../vi/guides/proxy-types.md)
- [Русский](../../ru/guides/proxy-types.md)

## Tre domande diverse

Spesso tre domande finiscono in una sola parola, «proxy»:

1. **Da che tipo di rete arriva l’IP di uscita?** È il senso abituale di residenziale, data center, ISP e mobile.
2. **Per quanto tempo resta assegnata la stessa uscita?** È la differenza tra statico e rotante, a volte chiamata sessione persistente.
3. **Come si collega il client?** È HTTP, compreso il tunnel [HTTP CONNECT](https://proxyvendors.com/it/glossary/http-connect) usato per HTTPS, oppure [SOCKS5](https://proxyvendors.com/it/glossary/socks5).

Un IP statico può comunque essere condiviso con altri clienti. Un endpoint SOCKS5 è un metodo di connessione, non un tipo di IP. La stessa uscita residenziale o di data center è spesso raggiungibile con più di un protocollo, e alcuni prodotti supportano solo HTTP o HTTPS.

## Tipi di rete

**Residenziale.** L’uscita è associata a una rete di consumo o a banda larga. È la scelta abituale quando la destinazione è sensibile agli intervalli di hosting, oppure quando serve un luogo che sembri una connessione domestica ordinaria. Il traffico residenziale è spesso fatturato a gigabyte. I pool sono condivisi e ruotano, salvo l’acquisto di un’opzione persistente o dedicata. L’etichetta è una classificazione del fornitore o di banche dati terze; non è un campo portato dall’IP stesso.

**Data center.** L’uscita proviene da una rete di hosting o cloud. Questi prodotti sono spesso più economici per unità di traffico o per IP e possono offrire più capacità per grandi volumi di richieste. Molti siti trattano in modo più rigoroso gli intervalli dei data center. Prima di acquistare un piano ampio, verifica se la destinazione restituisce contenuto valido attraverso quel tipo di uscita.

**ISP, a volte venduto come residenziale statico.** L’indirizzo è di solito registrato a nome di un fornitore di accesso residenziale, mentre l’host del proxy sta spesso in un data center. ISP nomina quella registrazione; da solo non significa che l’uscita resti fissa. I venditori spesso abbinano l’etichetta a un’assegnazione più lunga, adatta ad accessi, elenchi di IP consentiti e a un luogo fisso. Conferma se l’IP è dedicato o condiviso, che cosa succede alla disconnessione o al rinnovo e se si applicano controlli di identità.

**Mobile.** L’uscita proviene dalla rete di un operatore mobile, di solito 4G o 5G. Si usa per annunci mobili, pagine specifiche dell’operatore e contenuti regionali che cambiano sulle reti cellulari. La fatturazione può essere a gigabyte, al giorno o per porta. Controlla la disponibilità per operatore e paese, le regole di rotazione e i limiti d’uso, perché l’inventario mobile è spesso più sottile dei pool residenziali.

Nessuna di queste etichette è un punteggio di qualità. L’accettazione della richiesta dipende dall’uscita, dallo schema delle richieste e dalla politica della destinazione.

## Assegnazione: statica, rotante e persistente

Rotante di solito significa che una nuova uscita viene scelta a ogni richiesta, o a breve intervallo. Persistente o statica di solito significa che la stessa uscita è mantenuta per una sessione o per un periodo di noleggio. I fornitori non usano queste parole allo stesso modo e le pagine ufficiali a volte indicano due durate di sessione. Se il compito richiede lo stesso IP, ottieni il tempo esatto di mantenimento, le condizioni che lo interrompono e se un IP sostitutivo è garantito.

## L’ASN non è un quarto tipo

Un [ASN](https://proxyvendors.com/it/glossary/asn) identifica l’operatore di routing che annuncia un blocco di indirizzi. Può essere più preciso di un paese quando serve la rete di un operatore preciso. Non è un paese e non dice se l’IP è residenziale o di data center. Chiedere un ASN riduce anche il pool; se non c’è un’uscita disponibile, la richiesta può fallire.

## Dopo aver scelto il tipo, controlla l’uscita

Le pagine dei piani descrivono il prodotto che si intendeva acquistare. Il [controllo IP](https://proxyvendors.com/it/ip-check) mostra l’IP pubblico, l’organizzazione e l’ASN realmente ricevuti, più controlli facoltativi di DNS e WebRTC. Se quei risultati non corrispondono al prodotto acquistato, fermati e risolvi la differenza prima di aumentare il volume.

Quando confronti un piano specifico, usa la [lista per l’acquisto](./buying-checklist.md).

— Northleaf Studio
