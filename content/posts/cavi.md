---
title: "Come scegliere un cavo di rete"
slug: cavi
date: 2020-10-04T13:00:00+02:00
lastmod: 2022-11-10T13:30:00+01:00
authors: [Andrea (Hadx)]
description: "Se stai pensando di cablare casa tua con un cavo Cat 8 piatto e schermato, fermati subito e leggi prima questo articolo."
categories: [Reti]
---

Con la progressiva diffusione delle connessioni a Internet ad altissima velocità, molti utenti si stanno interessando alle reti cablate, che a differenza del Wi-Fi permettono di **sfruttare al massimo le velocità e la stabilità di queste connessioni**.

Questo articolo vi aiuterà nella **scelta di un cavo di rete**, illustrandone le caratteristiche principali e presentando alcuni consigli pratici che vi saranno utili nella realizzazione della vostra rete locale (LAN).

{{< toc >}}

## Cavi per cablaggio vs cavi patch

I cavi dati non sono tutti uguali, e in particolare è possibile distinguerli in due tipologie:

- i cavi da **cablaggio strutturato**, a cui è principalmente rivolta questa guida. Sono cavi con **conduttori rigidi** e utilizzati solitamente su lunghe distanze;
- i cavi **patch**. Sono cavi **flessibili, con conduttori sottili** organizzati in trefoli. Vengono utilizzati per collegare ad esempio un computer ad un modem, o in generale per collegare qualsiasi dispositivo ad un "frutto" o "keystone" o a un apparato di rete.

Nella pratica, se vi serve un cavo da passare in tubi corrugati per poi installare un frutto/keystone in una scatola, il cavo da utilizzare è un cavo da cablaggio strutturato. Se invece dovete collegare un computer ad un frutto/keystone, dovrete utilizzare un cavo patch, facilmente riconoscibile dal fatto che è solitamente venduto già connettorizzato.

## Schermato o non schermato?

Si incontra spesso l'errata convinzione che i cavi schermati siano di qualità migliore o che permettano il cablaggio in coesistenza con cavi in tensione (230V).

Va quindi innanzitutto chiarito che **la schermatura** (o l'assenza di schermatura) **non implica la possibilità di posare i cavi a fianco a cavi in tensione**: esiste invece una specifica tipologia di cavi compatibile con tali applicazioni, di cui parleremo più avanti nell'articolo.

Allo stesso modo, **un cavo schermato non è di per sé un cavo qualitativamente migliore** rispetto ad un cavo non schermato. È invece un tipo di cavo con caratteristiche particolari e progettato per essere utilizzato in ambiti specifici, ad esempio:[^schermatura]

- situazioni in cui sono presenti apparecchiature industriali ad alta potenza e con caratteristiche particolari, che generano elevate interferenze elettromagnetiche;
- situazioni in cui ci sono centinaia o migliaia di cavi di rete che viaggiano paralleli per lunghe distanze. (In questi casi si tende però a preferire la fibra ottica, e va anche considerato che le coppie contenute nei cavi di rete sono intrecciate per ridurre le interferenze.)

[^schermatura]: *Shielded vs Unshielded Ethernet Cable: Which Should You Use?* http://www.fiber-optic-components.com/shielded-vs-unshielded-ethernet-cable-use.html

**In un contesto casalingo la schermatura non porta quindi nei fatti ad alcun beneficio**, anzi: nella maggior parte dei casi serve solo ad aumentare la complessità dell'impianto. La schermatura richiede infatti la selezione di componenti (frutti, connettori, switch, ecc.) compatibili, nonché la loro contemporanea (e corretta) messa a terra.

Se ciò non viene fatto la presenza della schermatura diventa del tutto inutile, e anzi in alcuni casi potrebbe addirittura peggiorare le prestazioni dell'impianto rispetto ad un cavo non schermato (seppur in ambiente domestico probabilmente non ci si accorgerebbe).[^schermatura]

Pertanto, **quando scegliete un cavo di rete per il cablaggio domestico assicuratevi che sia non schermato**, più precisamente di tipo UTP (o U/UTP), perfettamente in grado di offrire le prestazioni di cui avete bisogno.[^utp]

[^utp]: *What does UTP, S/UTP, FTP, STP and SFTP mean?* https://www.universalnetworks.co.uk/faq/what-does-utp-s-utp-ftp-stp-and-sftp-mean/

## Cat 6, 7, 8, o...?

I cavi di rete vengono **classificati in categorie**, che si distinguono in base a caratteristiche come la **velocità massima raggiungibile e a quale distanza**.

Spesso si è indotti a scegliere cavi della categoria maggiore disponibile pensando che "più grande è meglio". Tuttavia, **i cavi di categoria superiore a 6 sono rivolti ad installazioni particolari** in cui si richiedono caratteristiche specifiche. Ad esempio, i cavi Cat 7 offrono una maggiore protezione dalle interferenze elettromagnetiche e richiedono per questo la schermatura, mentre i cavi Cat 8 sono pensati per trasferimenti ad altissime velocità su brevi distanze, caratteristiche che però non sono richieste in un impianto domestico.

Pertanto, la scelta di un cavo di categoria 7, 8, ecc. avrà il solo effetto di aumentare i costi (nel caso in cui acquistiate cavi di marca da fornitori qualificati), oppure il rischio di trovarsi cavi di scarsa qualità marchiati Cat 7, Cat 8, ecc., ma senza alcuna garanzia che soddisfino realmente tali caratteristiche (o anche solo le categorie inferiori!).

Se guardiamo le velocità suppportate dalle categorie di cavi, abbiamo che dal punto di vista teorico **tutti i cavi da Cat 6 in su supportano il trasferimento di dati a 10 Gbps**.

**Dal punto di vista pratico**, invece, anche i cavi **Cat 5e**, se di buona qualità, **supportano trasferimenti a 10 Gbps su brevi distanze**.

Va da sé quindi che anche se si vogliono sfruttare apparati di rete a 10 Gbps non è necessario puntare a cavi di categorie elevate: un cavo Cat 6 è infatti già in grado di reggere velocità di quel tipo.

La tabella che segue indica per ciascuna categoria la velocità massima raggiungibile in base alla lunghezza del cavo:[^cat]

[^cat]: *ISO/IEC 11801* https://en.wikipedia.org/wiki/ISO/IEC_11801

| Categoria | Velocità | Lunghezza | Disponibile senza schermatura |
| --------- | -------- | --------- | ----------------------------- |
| Cat 5e    | 5 Gbps*  | 100 metri | Sì |
| Cat 6     | 10 Gbps  | 55 metri  | Sì |
| Cat 6     | 5 Gbps   | 100 metri | Sì |
| Cat 6A    | 10 Gbps  | 100 metri | Sì |
| Cat 7     | 10 Gbps  | 100 metri | No |
| Cat 8     | 40 Gbps  | ~30 metri | No |

*\*anche 10 Gbps con cavi di buona qualità e brevi distanze.*

Risulta quindi evidente che **un cavo Cat 6 è più che sufficiente per pressoché qualsiasi impianto domestico presente e futuro**.

Solo nel caso in cui ci si trovi a dover stendere tratte particolarmente lunghe si consiglia di utilizzare cavi di categoria 6A.

{{< green >}}
###### Cat 5e e velocità superiori al Gigabit

In seguito all'aumentare della banda richiesta, nel 2016 la IEEE ha preparato un nuovo standard (IEEE Std 802.3bz-2016) in cui ratifica ufficialmente il **supporto dei cavi di Categoria 5e alle velocità di 2,5 e 5 Gb/s per distanze fino a 100 metri**.

Va sottolineato, tuttavia, che il supporto a tali velocità non è incondizionato, ma è anzi soggetto al rispetto di alcuni requisiti prestazionali aggiuntivi*, definiti all’interno dello standard.

Per tali ragioni si raccomanda quindi, in caso di nuovo cablaggio, di **preferire sempre cavi di categoria superiore quando possibile**.

(*\*Si veda ISO/IEC/IEEE 8802-3:2017 Amendment 7, Clausola 126.7 e successive per i dettagli.*)
{{< /green >}}

## Va bene un cavo "piatto"?

**No**. I cavi di rete devono essere intrecciati (*twisted*) per assicurare una buona resistenza contro la diafonia (*crosstalk*). I cavi piatti non sono conformi allo standard e vanno quindi evitati.

## Coesistenza con cavi in tensione

Nel caso in cui si debbano far passare cavi di rete accanto a cavi elettrici in tensione, **il cavo deve riportare la seguente certificazione**:[^tensione]

<p style="text-align: center">
<strong>CEI-UNEL 36762 C-4 (U0=400V)</strong>
</p>

[^tensione]: *Coesistenza tra cavi per telecomunicazioni e cavi energia* https://www.cavel.it/it/supporto-tecnico/certificazioni/coesistenza-tra-cavi-per-telecomunicazioni-e-cavi-energia

Anche i cavi conformi a tale requisito, tuttavia, non possono essere terminati (più in generale, non potete "spellarlo" della guaina esterna) in una scatola di derivazione dove passino anche cavi elettrici o nella stessa scatola dove ci siano frutti in tensione, come nelle foto che seguono.

{{< fig src="/images/cavi-tensione.jpg" caption="Esempi di scatole dove **non è possibile** terminare i cavi di rete, anche se sono certificati CEI-UNEL 36762 C-4 (U0=400V). [Fonte foto](https://forum.fibra.click/d/4599-predisporre-impianto-ethernet-a-casa)." alt="" >}}

Per evitare contatti accidentali tra conduttori del cavo di rete e conduttori in tensione, infatti, la guaina esterna del cavo può essere tolta solo ed esclusivamente in scatole vuote oppure in scatole dove passino solo cavi di antenna, telefonici, del citofono, del sistema di allarme, ecc.

{{< fig src="/images/cavi-scatolatv.jpg" caption="Esempio di cavo di rete terminato su frutto in una scatola della antenna TV. Notare anche le \"piegature\" subite dal cavo di rete." alt="" >}}

## Uso dei connettori

È possibile usare i **connettori** (*plug*) sui cavi di rete per il cablaggio strutturato?

**No**, si tratta di **cavi rigidi che non sopportano bene "movimenti" frequenti**. Andare dunque a crimpare dei connettori per poi connetterli direttamente a un computer o a un dispositivo potrebbe portare nel tempo a un danneggiamento del cavo.

La soluzione migliore è quindi **utilizzare dei keystone** (o dei frutti, magari della stessa serie civile che avete in casa, come nella foto sopra), installandoli in una scatola dell'antenna TV o del telefono, su cui andare poi a terminare i cavi di rete.

In questo modo **dal keystone/frutto al dispositivo sarà sufficiente utilizzare un cavo di rete patch**  della lunghezza desiderata e della stessa categoria del cavo utilizzato per il cablaggio. (Anche i frutti e i keystone devono essere della medesima categoria.)

## Rame o alluminio?

A causa del costo del rame, in tutti gli ambiti è diventato ormai sempre più comune usare cavi in alluminio al posto di cavi in rame. Anche **i cavi dati per il cablaggio di rete sono disponibili in alluminio**, e vengono chiamati **cavi CCA** (Copper Clad Aluminum).

Tuttavia, le specifiche dei cavi di rete richiedono l'**uso obbligatorio di conduttori in rame**[^cca]. Ciò significa che i cavi CCA non soddisfano i requisiti della categoria a cui sono associati, e pertanto non ha senso parlare di CAT 5e, 6, 7 quando ci si riferisce a cavi in alluminio.

[^cca]: *Copper Clad Aluminum vs. Pure Copper Cables* https://www.showmecables.com/blog/post/copper-clad-aluminum-vs-pure-copper-cables

Inoltre, i cavi in alluminio presentano dei problemi nel caso sia necessario sfruttare la funzionalità PoE (*Power Over Ethernet*, per alimentare dispositivi come access point Wi-Fi tramite il cavo di rete), per via della maggiore resistenza dell'alluminio.

**Assicuratevi quindi che i cavi che scegliete siano in rame.**

{{< green >}}
###### I diversi significati di "CCA"

È opportuno sottolineare che all'interno del nostro mercato la sigla "CCA" può avere anche un secondo significato. Sono infatti definite, per le guaine dei cavi, delle **classi di comportamento al fuoco** e una di queste è proprio la classe Cca.

Questa classe, in particolare, implica la non propagazione dell'incendio e indica un cavo utilizzabile all'interno della maggior parte delle case e degli uffici.

In tal senso, dunque, è bene prestare attenzione quando si valuta un cavo:
- un cavo con conduttore CCA è un cavo di bassa qualità;
- un cavo con guaina rispondente alla classe Cca e con conduttore in rame puro è un ottimo cavo.
{{< /green >}}

## Conclusione

In sintesi, quando dovete acquistare un cavo di rete per una rete LAN è più che sufficiente scegliere un cavo di tipo **Cat 6** (o Cat 6A se la lunghezza è maggiore di 55 metri) **di tipologia U/UTP**.

Nel caso in cui si renda necessaria la coesistenza con cavi in tensione a 230V, bisogna assicurarsi che il cavo scelto abbia la **certificazione CEI-UNEL 36762 C-4 (U0=400V)**.

{{< footer >}}
