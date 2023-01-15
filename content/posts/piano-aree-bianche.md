---
title: "Cos'è il piano aree bianche"
slug: piano-aree-bianche
date: 2019-03-24
lastmod: 2023-01-15T10:00:00+01:00
authors: [Matteo]
description: Il piano BUL è il progetto avviato nel 2015 dal governo Renzi per portare la banda ultralarga in tutte le case italiane entro il 2020.
categories: [Definizioni, Copertura, Piano BUL]
image: /social/piano-bul.jpg
---

Il **piano aree bianche** è il piano pubblico, parte della [Strategia nazionale per la banda ultralarga]({{< relref "/posts/piano-bul.md">}}), con l'obiettivo di **coprire le zone dette a "fallimento di mercato"**, cioè le aree dove gli operatori non hanno in previsione di portare la banda ultralarga ad almeno 30 Mbps.

Questo intervento è in corso e prevede nello specifico la copertura da parte di [**Open Fiber**]({{< relref "/posts/openfiber.md" >}}) di circa il 25% della popolazione italiana, in larga parte **in fibra ottica FTTH** (1 Gbps) e in parte **in wireless FWA (100 Mbps)**.

Il completato dei lavori in tutti i comuni coinvolti è previsto, dopo molti ritardi, tra il 2023 e il 2024.

I prossimi paragrafi approfondiscono più in dettaglio la nascita e gli sviluppi del piano.

{{< toc >}}

## Gli obiettivi europei

La **Commissione Europea** ha stabilito nel corso degli anni diversi obiettivi per lo sviluppo della banda ultralarga, su cui il piano BUL italiano si basa.

In particolare, l'**Agenda Digitale 2020** richiede che entro il 2020 tutti i cittadini siano coperti dalla banda larga veloce ad almeno 30 Mbps, e che almeno il 50% delle famiglie sia abbonata con connessioni ad almeno 100 Mbps.[^agendadigitale]

Il **piano BUL italiano del 2015** prevede di raggiungere l'obiettivo di copertura integrando gli investimenti delle aziende private con un **intervento pubblico diretto**, con lo scopo di realizzare una **rete pubblica in fibra ottica nelle aree bianche**.

[^agendadigitale]: *Agenda digitale europea 2020* https://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=COM:2010:0245:FIN:IT:PDF

{{< fig src="/images/pozzetto-bul1.jpg" caption="Un pozzetto della rete pubblica #BUL, elemento distintivo della rete realizzata da Open Fiber nelle aree bianche." alt="Chiusino di un pozzetto, con la scritta BUL rete pubblica." >}}

Nel 2016 la Commissione Europea ha aggiornato gli obiettivi dell'Agenda Europea, fissando nel documento "Verso la Gigabit Society" gli **obiettivi per il 2025**: scuole e uffici pubblici dovranno essere connessi ad almeno 1 Gbps, mentre tutte le famiglie dovranno avere accesso a una connettività di **almeno 100 Mbps ma espandibile al Gigabit**.[^gigabitsociety] Il piano aree bianche risulta in larghissima parte già conforme agli obiettivi del 2025.

[^gigabitsociety]: *Connettività per un mercato unico digitale competitivo: verso una società dei Gigabit europea* https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX:52016DC0587

## Chi viene coperto

Il progetto di copertura delle aree bianche riguarda **circa il 25% della popolazione italiana**.[^concessione] Approssimativamente, si tratta dei comuni o delle aree periferiche in cui è presente solo l'ADSL.

[^concessione]: https://bandaultralarga.italia.it/documenti-e-dati/concessioni/

Le aree bianche sono state identificate dal Ministero dello Sviluppo Economico tramite le **consultazioni Infratel**, nelle quali gli operatori hanno specificato in quali zone avevano intenzione di coprire autonomamente e in quali no.

Le abitazioni effettivamente coperte vengono però decise con precisione solo in fase di redazione del **progetto esecutivo** del comune. Una volta disponibile, il progetto viene pubblicato [sul sito BUL](https://bandaultralarga.italia.it/mappa/), dove è possibile vedere per ciascun comune i tracciati in fibra ottica previsti e quali edifici saranno raggiunti in fibra. Se il tuo comune è in fase di esecuzione o con lavori completati e non vedi le tratte, puoi segnalare il problema [a Infratel](https://www.infratelitalia.it/contatti).

Circa l'81% delle aree bianche coinvolte sarà coperto in [FTTH]({{< relref "/posts/architetture.md#ftth-fiber-to-the-home" >}}) (*Fiber To The Home*), cioè in fibra ottica a 1 Gbps (e fino a 300 Mbps in upload), mentre il restante 19% sarà coperto con connessioni wireless [FWA]({{< relref "/posts/architetture.md#fwa-fixed-wireless-access" >}}) (*Fixed Wireless Access*) a 100 Mbps (50 Mbps in upload).[^buldashboard]

{{< fig src="/images/sitobul-mappa.jpg" caption="Le tratte della rete pubblica in fibra ottica realizzata in un comune delle aree bianche." >}}

{{< green >}}
###### I vincoli dell'aiuto di Stato

L'intervento pubblico previsto dal piano BUL è considerato un **aiuto di Stato** e deve quindi sottostare a determinate norme in tutela del mercato e degli investimenti privati.

Per questo motivo, il piano aree bianche **non può intervenire nelle aree in cui un operatore ha dichiarato di voler portare copertura a banda ultralarga nel breve periodo**, anche nel caso in cui questa copertura non sia nei fatti praticabile come nel caso di linee FTTC molto lunghe che non garantiscono 30 Mbps.
{{< /green >}}

{{< warn >}}
🦠 Durante l'**emergenza sanitaria COVID-19** il decreto Cura Italia ha autorizzato **in via eccezionale l'attivazione** di infrastrutture di telecomunicazioni anche nelle aree bianche. Concretamente significa che la **FTTC** attivata nelle aree bianche e derivante dal [piano Cassiopea]({{< relref "/posts/cassiopea.md" >}}) [non influirà](https://openfiber.it/app/uploads/2020/06/Domande-e-risposte-Report.pdf) sulla realizzazione della rete pubblica nelle stesse aree.
{{< /warn >}}

## Chi fa i lavori

I lavori per le aree bianche sono stati affidati all'azienda [**Open Fiber**]({{< relref "/posts/openfiber.md" >}}) tramite tre gare pubbliche dal valore complessivo di 2,7 miliardi di euro, a valere dai fondi FSC (nazionali), FESR e FEASR (europei).[^camera]

[^camera]: http://www.camera.it/temiap/documentazione/temi/pdf/1104721.pdf

Open Fiber si è aggiudicata tutte e tre le gare per 1,5 miliardi di euro complessivi, con un ribasso del 9%, se si tengono in considerazione i proventi che deriveranno dalla concessione fino al 2037.[^concessione][^ribasso]

[^ribasso]: https://twitter.com/OpenFiberIT/status/1267580298079997952

La rete realizzata, 80mila km in fibra ottica, è infatti **di proprietà pubblica** ma è data in **concessione a Open Fiber per 20 anni**, che ne gestisce anche la manutenzione. Open Fiber è un operatore "wholesale-only": non vende direttamente ai clienti finali ma mette a disposizione la rete realizzata a tutti gli operatori interessati (vedi la sezione *Come attivare una linea su rete BUL*).[^concessione][^pianoof]

L'esecuzione effettiva dei lavori è affidata da Open Fiber a diverse aziende del settore[^aziende]. Tramite [il sito Open Fiber](https://openfiber.it/area-infratel/piano-copertura/) è possibile verificare l'azienda o il consorzio incaricati in ciascun comune.

[^aziende]: https://openfiber.it/informazioni-sulle-gare/

{{< info >}}
**Per approfondire:**

- [Cos'è e cosa fa Open Fiber]({{< relref "/posts/openfiber.md" >}})
- [Come riconoscere la rete pubblica BUL]({{< relref "/posts/rete-bul.md" >}})
{{< /info >}}

## L'avanzamento del progetto

Per via dei numerosi ricorsi e dei tempi richiesti per ottenere le autorizzazioni, la copertura è stata avviata solo durante il 2018, con notevole ritardo.

A fine 2022, **i comuni con rete FTTH realizzata erano 4054 su un totale previsto di circa 6200 comuni**. In termini di unità immobiliari (UI), il dato corrisponde a 3,8 milioni di UI su un totale previsto di 6,4 milioni.

I comuni effettivamente **vendibili** erano circa **3000**, corrispondenti a 2,9 milioni di unità immobiliari.[^of2022]

[^of2022]: *Avanzamento lavori Aree Bianche* https://openfiber.it/piano-copertura/avanzamento-lavori-aree-bianche/ (https://archive.is/H28AC)

{{< green >}}
Le unità immobiliari inizialmente previste erano 9,6 milioni, poi ridotte a 7,9 milioni, di cui 6,4 milioni da coprire in FTTH e il restante in FWA.
{{< /green >}}

Secondo Open Fiber, il ritmo di realizzazione dell'infrastruttura rilevato a fine 2022 consentirà di terminare il piano secondo il cronoprogramma presentato al Governo durante il 2022. Il piano prevede il completamento di tutti i comuni finanziati con fondi europei **FESR** (Fondo europeo di sviluppo regionale) **entro giugno 2023**, i comuni **FEASR** (Fondo europeo agricolo per lo sviluppo rurale) entro **dicembre 2023** e i comuni finanziati con fondi nazionali **FSC** (Fondo di sviluppo e coesione) **entro settembre 2024**.[^pianoof2022]

Un piano precedente di Open Fiber, reso noto nell'estate del 2020, prevedeva di completare la copertura del 65% delle abitazioni entro il 2021, e il 92% entro il 2022. Il restante 8% si trovava in 4 regioni particolarmente impegnative come quantità di abitazioni da coprire, cioè Lombardia, Veneto, Piemonte e Liguria. In queste regioni era previsto che la copertura terminasse nel corso del 2023, anno entro cui dovrebbero essere rendicontati i fondi europei.[^pianoof]

[^pianoof]: *Linee guida del piano di azioni Open Fiber a supporto del Piano 2020-2023* https://bandaultralarga.italia.it/wp-content/uploads/2020/07/Linee-guida-piano-di-azione-a-supporto-delle-realizzazioni-BUL-CD-8-sent.cleaned-1.pdf
[^pianoof2022]: *Urso in audizione alla Camera: ‘Gravi i ritardi di Open Fiber’* https://www.key4biz.it/urso-in-audizione-alla-camera-gravi-i-ritardi-di-open-fiber/430570/

Lo **stato dei lavori** è pubblicato e aggiornato periodicamente sul sito istituzionale [Banda Ultra Larga](https://bandaultralarga.italia.it/), dove si possono trovare anche le stime di avvio e termine dei lavori per ciascun comune. Alcune informazioni aggiuntive sono pubblicate anche da Open Fiber nelle pagine [Avanzamento lavori](https://openfiber.it/piano-copertura/stato-dei-lavori/) e [Avanzamento lavori aree bianche](https://openfiber.it/piano-copertura/avanzamento-lavori-aree-bianche/) del sito ufficiale.

## Come attivare una linea su rete BUL

Open Fiber è un operatore **wholesale-only** (all'ingrosso), e non vende quindi gli abbonamenti direttamente ai clienti finali. Tramite la homepage del [sito di Open Fiber](https://openfiber.it/) è possibile **verificare se la vendibilità è stata aperta** nel proprio comune, se il proprio indirizzo è coperto e vedere anche la **lista degli operatori** tramite cui è possibile richiedere l'attivazione del servizio.

Alcuni grandi operatori che vendono in area bianca sono attualmente **Tiscali** (dall'estate 2019) e **WINDTRE** (da settembre 2020). Anche [Fastweb](https://www.fastweb.it/corporate/media/comunicati-stampa/fastweb-e-open-fiber-accordo-per-l-utilizzo-da-parte-di-fastweb-delle-connessioni-ftth-di-open-fiber-e-l-accesso-reciproco-alle-rispettive-infrastrutture-di-rete/) e [Vodafone](http://www.vodafone.it/portal/StreamLine/Vodafone-Italia---TEST-COMUNICATI/Dettaglio-Comunicato-stampa-test?idCom=236) hanno annunciato accordi con Open Fiber per le aree bianche.

Nel caso di attivazione di una linea **FTTH**, l'**intervento di allaccio** prevede la stesura della **tratta "verticale"** in fibra ottica dalla strada fino all'interno dell'abitazione, solitamente sfruttando tubazioni esistenti (telefono, citofono, ecc.).

Nel caso di **FWA**, è prevista l'installazione di una **piccola parabola esterna** (sul tetto, balcone, ecc.), che deve avere visibilità ottica con la stazione radio base di Open Fiber.

## Approfondimento: i bandi pubblici e l'offerta di Open Fiber

La realizzazione della rete pubblica è stata messa a gara da Infratel tramite **tre bandi pubblici**, ciascuno dei quali riguardante un sottoinsieme di regioni o province autonome italiane.[^relazione]

[^relazione]: *Stato di avanzamento del piano BUL*, 31 luglio 2020 https://bandaultralarga.italia.it/stato-di-avanzamento-del-piano-strategico-per-la-banda-ultralarga-2/

Nello specifico:

- **BUL1**: Abruzzo, Molise, Emilia Romagna, Lombardia, Toscana e Veneto;
- **BUL2**: Basilicata, Campania, Friuli Venezia Giulia, Lazio, Liguria, Marche, Piemonte, Provincia Autonoma di Trento, Sicilia, Umbria e Valle d’Aosta;
- **BUL3**: Calabria, Puglia e Sardegna.

{{< warn >}}
La provincia di Bolzano non partecipa al piano BUL nazionale.
{{< /warn >}}

{{< warn >}}
Il bando BUL3 è di dimensione ridotta ed è stato avviato più tardi perché nelle tre regioni coinvolte la copertura a banda ultralarga era già in stato avanzato prima dei bandi.
{{< /warn >}}

**Open Fiber** ha vinto tutti e tre i bandi Infratel (per il terzo bando c'è stata una sola offerta), grazie a delle offerte fortemente vantaggiose rispetto a quanto richiesto dal bando e dagli obiettivi europei.[^relazione]

In particolare, la proposta di Open Fiber è così articolata (le percentuali si riferiscono alle unità immobiliari previste dal bando):

- **Primo bando**
  - 87% di copertura FTTH (>100 Mbps)
  - 4% di copertura FTTH facoltativa (>100 Mbps)
  - 8% di copertura FWA facoltativa (>30 Mbps)
  - 1% non coperto

{{< fig src="/images/bando1.jpg" caption="Confronto tra requisiti del bando BUL1 e l'offerta di Open Fiber." alt="Grafici che mostrano le percentuali del bando e dell'offerta Open Fiber." >}}

{{< fig src="/images/bando1b.jpg" caption="L'offerta economica di Open Fiber per i lotti del bando BUL1." >}}

- **Secondo bando**
  - 75% di copertura FTTH (>100 Mbps)
  - 8% di copertura FWA (>30 Mbps)
  - 16% di copertura FWA facoltativa (>30 Mbps)
  - 1% non coperto

{{< fig src="/images/bando2.jpg" caption="Confronto tra requisiti del bando BUL2 e l'offerta di Open Fiber." alt="Grafici che mostrano le percentuali del bando e dell'offerta Open Fiber" >}}

{{< fig src="/images/bando2b.jpg" caption="L'offerta economica di Open Fiber per i lotti del bando BUL2." >}}

- **Terzo bando**
  - 59% di copertura FTTH (>100 Mbps)
  - 41% di copertura FWA (>30 Mbps)

{{< fig src="/images/bando3.jpg" caption="Confronto tra requisiti del bando BUL3 e l'offerta di Open Fiber." alt="Grafici che mostrano le percentuali del bando e dell'offerta Open Fiber" >}}

{{< fig src="/images/bando3b.jpg" caption="L'offerta economica di Open Fiber per i lotti del bando BUL3." >}}

{{< footer >}}
