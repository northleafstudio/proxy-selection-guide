# Una lista breve prima di acquistare un piano proxy

Questa lista è pubblicata da Northleaf Studio, che gestisce anche [ProxyVendors](https://proxyvendors.com/it/). È materiale di accompagnamento della stessa parte, non una raccomandazione di un terzo estraneo. Usala sulla pagina dei prezzi vigente, sulle condizioni e su una prova piccola. Non garantisce che un piano funzioni per la tua destinazione.

## Lingue

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
- [Polski](../../pl/guides/buying-checklist.md)
- **Italiano**
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- [Tiếng Việt](../../vi/guides/buying-checklist.md)
- [Русский](../../ru/guides/buying-checklist.md)

## 1. Definisci il compito, poi scegli la rete

Scrivi che cosa deve fare l’uscita: un accesso duraturo, dati pubblici di una zona precisa, un alto volume di richieste o una prova su un operatore mobile. Abbinalo a un tipo di rete, come descritto nella [guida ai tipi di proxy](./proxy-types.md): residenziale, data center, ISP o mobile. Se la home page e la pagina dei prezzi pubblicizzano prezzi di partenza o numeri di paesi diversi, annota entrambi e chiedi quale cifra vale per il livello esatto che acquisteresti.

## 2. Controlla il comportamento della sessione

Decidi se ti serve la stessa uscita per minuti, ore o l’intero noleggio, oppure una nuova uscita a ogni richiesta. Conferma la durata persistente o statica, che cosa la interrompe e se un IP caduto viene sostituito. La documentazione ufficiale a volte indica due tempi di mantenimento; consideralo non risolto finché il fornitore non lo conferma.

## 3. Conferma protocolli e autenticazione

HTTP, compreso [HTTP CONNECT](https://proxyvendors.com/it/glossary/http-connect) per i siti HTTPS, non è la stessa cosa di [SOCKS5](https://proxyvendors.com/it/glossary/socks5). Alcuni prodotti residenziali supportano solo HTTP e HTTPS. Se ti serve SOCKS5, o UDP attraverso SOCKS5, verifica che lo supportino sia il prodotto sia il client. Conferma l’host di ingresso, la porta e il metodo di autenticazione: nome utente e password, un elenco di IP consentiti, oppure entrambi. Una risposta 407 durante CONNECT arriva dal proxy. Lo stato significa Proxy Authentication Required: il proxy richiede l’autenticazione, oppure non ha accettato l’autenticazione ricevuta. Il tunnel non è stato stabilito e il sito di destinazione non ha mai visto la richiesta.

## 4. Somma il costo reale

Guarda oltre il prezzo unitario del titolo. Annota l’acquisto minimo, la validità o la scadenza del pacchetto, i costi di eccedenza, lo spreco dei tentativi ripetuti, i supplementi per un targeting fine, l’IVA e le ricariche o i rinnovi automatici. Un prezzo in evidenza può appartenere a una fascia di grande volume, non al pacchetto con cui inizieresti. Se la prova richiede una carta e attiva le ricariche automatiche, decidi se disattivarle prima di cominciare.

## 5. Leggi le regole di prova, rimborso e accesso

Controlla dimensione e durata della prova, la finestra di rimborso, i tetti d’uso e se il rimborso richiede un guasto di rete documentato. Nota i controlli di identità o KYC, le categorie bloccate come i siti bancari o pubblici e i limiti di uso equo sui prodotti statici o dedicati. Se l’origine o la conformità ti interessano, chiedi documentazione al fornitore invece di basarti solo sul testo commerciale.

## 6. Individua la rete, poi prova

Se ti serve un operatore preciso, conferma che il [targeting per ASN](https://proxyvendors.com/it/glossary/asn) sia supportato e che cosa succede quando non c’è un’uscita disponibile. Poi esegui un compito reale e piccolo: risposte valide della destinazione, cadute di sessione, accuratezza del luogo e traffico effettivamente consumato. Dopo la connessione, usa il [controllo IP](https://proxyvendors.com/it/ip-check) per confrontare l’IP pubblico, l’organizzazione e l’ASN con il prodotto acquistato ed esegui i controlli DNS e WebRTC se quei percorsi contano.

Solo allora decidi quanto acquistare.

— Northleaf Studio
