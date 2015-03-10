---
published: false
---

## Data Therapy e beni culturali con OSM e Wikipedia
La prima volta che ho sentito parlare di [#datatherapy](https://prezi.com/rwknn0wzqrh0/data-therapy-data-day/) è stato nella nostra lista di **OpenPuglia**, grazie a **Paola Liliana Buttiglione**, che [ne aveva già scritto su OpenPompei](http://www.openpompei.it/2015/02/25/progetto-europeo-ariadne-lo-stvdivm-come-archaeological-data-therapy/).

L’idea di _**curarsi con i dati**_ è al tempo stesso **bizzarra e geniale**, anzi, direi **necessaria**. Il motto del [progetto #datatherapy del MIT]() è infatti quello di diffondere “_creative data literacy for non-data people_”. La terapia dei dati è **“un processo pratico volto a costruire nelle persone la capacità di trovare e raccontare storie con i dati in maniera creativa”**.

Ed è esattamente **quello che abbiamo tentato di fare durante l’OpenDataDay** del 21 febbraio scorso, a Bari. Nella **track dedicata ai beni culturali** mi sono occupato di condurre un’attività dedicata proprio a coloro i quali hanno poca dimestichezza con i dati e la miriade di strumenti con i quali poterci lavorare, ma erano là animati da curiosità e una gran voglia di fare qualcosa, di **“sporcarsi le mani”**.

Per professione mi occupo di geomatica, e naturalmente ho voluto basare il lavoro da me proposto proprio sui **dati geografici**, una **tipologia di informazioni che sta letteralmente rivoluzionando le nostre vite**, poichè tutto, ma proprio tutto ciò che abbiamo intorno possiede un’informazione localizzata. Perfino noi stessi, mentre ci muoviamo con i nostri smartphone al seguito, siamo **inconsapevoli produttori di dati geografici**. Non ci credete? Se avete uno smartphone Android date un’occhiata alla [cronologia delle vostre posizioni](https://maps.google.com/locationhistory/b/0).

Nel lontano 2009 la Penn State University lanciò una serie di video divulgativi con il **[Geospatial Revolution Project](https://www.youtube.com/watch?v=poMGRbfgp38&list=PLB536E2CAE9CD2EE1)**. Con gli amici del [blog TANTO](http://blog.spaziogis.it/geospatial-revolution-project/) ne abbiamo curato la traduzione, vi invito -quando avrete tempo- a guardarli per intero se volete **capire come le informazioni spaziali hanno rivoluzionato le nostre vite**.

## Torniamo all’ODD
La terapia dei dati, da me proposta inconsapevolmente a chi ha partecipato all’attività il 21 febbraio scorso, si è basata su **due dei repository di informazioni e dati aperti e liberi** più noti al mondo: [OpenStreetMap](http://www.openstreetmap.org/) per i dati geografici e Wikipedia per le informazioni di carattere descrittivo. Si tratta entrambi di progetti supportati dalla [Wikimedia Foundation](https://wikimediafoundation.org/), interamente **costruiti con i liberi contributi di milioni di utenti da tutto il mondo**, in piena filosofia collaborativa peer to peer.

**L’obiettivo è stato quello di aggiornare OSM con le informazioni eventualmente presenti in Wikipedia** per elementi presenti sul territorio pugliese, nell’ambito dei beni culturali. Qui sotto trovate la mia presentazione con il workflow che abbiamo seguito durante l’attività.

<iframe src="//www.slideshare.net/slideshow/embed_code/44958077" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>

## Cos’è Wikipedia
Alzi il mouse chi non ha utilizzato la **notissima enciclopedia aperta e libera** almeno una volta nella vita. Nata nel 2011, i 124 milioni di pagine in 288 lingue che la compongono possono essere **modificate da chiunque** dei 49 milioni di suoi utenti e non c’è un comitato di redazione né alcun controllo preventivo sul materiale inviato, che deve avere comunque un **punto di vista neutrale**. I suoi contenuti sono distribuiti con licenza [CC BY-SA 3.0](http://it.wikipedia.org/wiki/Licenze_Creative_Commons) che ne consente il **riuso allo stesso modo**.

## Cos’è OpenStreetMap
OSM è un progetto nato nel 2004 che punta a **creare e rendere disponibili dati geografici, liberi e gratuiti a chiunque ne abbia bisogno**. Il progetto è stato lanciato perché la gran parte delle mappe online disponibili normalmente si pensano libere, ma hanno in realtà restrizioni legali o tecniche. **Chiunque può utilizzare i dati di OpenStreetMap a qualsiasi scopo** (anche commerciale) e **senza costi di licenza** ([ODbL](http://opendatacommons.org/licenses/odbl/)), purché ne citi la fonte. I suoi utenti attualmente sono quasi 2 milioni, mentre gli oggetti che la compongono (vedi slide 16 della presentazione) sono complessivamente più di 3 miliardi.

## Cosa abbiamo fatto?
All’attività hanno partecipato **Antonella Ciociola** e due ragazzi, ingegneri informatici, dei quali purtroppo non ricordo il nome e ne ho perso le tracce. Siamo partiti da uno strumento web che possiamo considerare **l’anello di congiunzione tra Wikipedia e OSM**, si tratta di **WTOSM**, un acronimo che sta appunto per “Wikipedia To OpenStreetMap”. Si tratta di una piattaforma sviluppata in seno alla [Fondazione Bruno Kessler](http://www.fbk.eu/) da Simone Groppo e Cristian Consonni. L’istanza pubblica che abbiamo usato durante l’ODD15 è ospitata dalla Fondazione Edmund Mach a [questo link](http://geodati.fmach.it/gfoss_geodata/osm/wtosm/it_IT/index_1.html).

Viene usata una simbologia per indicare quali articoli in Wikipedia sono totalmente privi di coordinate, quali le possiedono ma non sono collegati a oggetti in OSM, e quali invece sono geocodificati in Wikipedia e viceversa in OSM possiedono anche il tag al relativo articolo nell’enciclopedia.

Dopo aver familiarizzato con l’interfaccia web e la struttura dati di OSM, **Antonella ha scelto di dedicarsi ai teatri pugliesi presenti in Wikipedia**. Prima del suo lavoro, quelli collegati tra l’enciclopedia e OSM erano solo 2 su 11 totali, alla fine è riuscita a concludere il lavoro: 10 su 11, l’undicesimo è il [Teatro Real Borbone di San Severo](https://it.wikipedia.org/wiki/Teatro_Real_Borbone), che è stato demolito negli anni ‘30 e non andrebbe considerato da WTOSM.

**Il workflow di lavoro adottato** è stato grosso modo il seguente:
1. scegliamo l’articolo da mappare basandoci sulla legenda;
2. il modo più facile per creare/modificare gli elementi in OSM (bisogna creare un proprio account ovviamente) è l’editor web ID, che si aprirà direttamente sulle coordinate in OSM una volta cliccato sull’icona in WTOSM;
3. individuiamo sulla mappa l’elemento al quale si riferisce l’articolo di Wikipedia;
4. se l’elemento esiste come nodo o poligono, aggiorneremo solo la [key Wikipedia](http://wiki.openstreetmap.org/wiki/Key:wikipedia);
5. se l’elemento non esiste affatto, lo creeremo noi stessi come nodo o poligono, aggiungendo anche la key Wikipedia.

**A [questo link](https://www.youtube.com/watch?v=_2ouZ7jK5TE) è possibile guardare un utilissimo tutorial di Andrea Borruso che mostra in pochi minuti l’intero processo.**

## Au contraire: aggiornare le coordinate in Wikipedia
**Nei casi in cui siano gli articoli di Wikipedia ad essere privi di coordinate**, è possibile aggiornare il [template Coordinate](https://it.wikipedia.org/wiki/Template%3ACoord). Questi sono contrassegnati in WTOSM con l’icona di una W rossa. In sostanza si tratta di **invertire il processo**:
1. individuiamo in OSM l’oggetto cui l’articolo in Wikipedia si riferisce;
2. posizioniamo la mappa OSM con al centro l’oggetto;
3. copiamo dall’URL nel browser le coordinate (es. 40.63893/17.94436);
4. andiamo ad editare in wikitesto l’articolo in Wikipedia (anche in questo caso, bisogna avere un account) inserendo il template Coordinate es. {{coord|40.63893|17.94436|display=title}};
5. una volta pubblicate le modifiche, l’articolo sarà geotaggato.

Nel mio videotutorial qui sotto il procedimento viene illustrato nei dettagli.

<iframe width="560" height="315" src="https://www.youtube.com/embed/1RF2DdNSC9s" frameborder="0" allowfullscreen></iframe>

## Sporchiamoci le mani: i teatri pugliesi tra OSM e Wikipedia (di Antonella Ciociola)
**Avevo una missione per l’OpenDataDay 2015**: trovare un esperto di open data per il project work dei ragazzi dell’IISS Giulio Cesare di Bari per [A Scuola di Open Coesione](http://www.ascuoladiopencoesione.it/). **L’idea di mettermi a “giocare” con i dati in prima persona non mi aveva mai sfiorato**. Da insegnante di lettere, **le grandi questioni teoriche su partecipazione, beni comuni e cultura condivisa mi hanno sempre affascinato**: come questioni teoriche, appunto, sulle quali è difficile non essere d’accordo e su cui speculare all’infinito. Tuttavia, il piacere di “sporcarmici le mani” l’ho sperimentato con una attività molto pratica e apparentemente semplice, per la quale sono stata “cooptata” da Pietro Blu: aggiornamento di OSM con informazioni presenti in Wikipedia, attraverso la categoria di WTOSM da me scelta: Teatri della Puglia (il teatro è una mia grande passione, e in qualche modo mi sembra di averle così reso omaggio).

A rispondere **“Prego, nessuna domanda è stupida”**, con un sorriso d’incoraggiamento, sono abituata, è una routine per me: ma quanto può essere entusiasmante porla, anche timidamente, quella domanda stupida, lasciarsi guidare dalla risposta, risolvere un problema? Può essere addirittura inebriante, a volte.

**Sono partita press’a poco così: “Pietro, scusami, ma io non so cosa sia una ortofoto…”**; sono entrata in confidenza con nodi, vie e relazioni (elementi, primitive geometriche che rappresentano gli oggetti reali su OSM); ho creato gli account necessari; ho spulciato ben benino le categorie di WTOSM; dopodiché, seguendo le istruzioni del tutorial di Andrea Borruso e i pronti suggerimenti di Pietro, dopo un paio d’ore ho raggiunto l’obiettivo di aggiungere, per tutti i teatri pugliesi presenti su OSM, la key Wikipedia. Nella maggior parte dei casi, l’unico elemento da aggiornare è stata solo la key Wikipedia; in due casi, il teatro Mediterraneo di Bisceglie e il teatro Traetta di Bitonto, è stato necessario creare il poligono (attraverso lo strumento area) che identificasse l’edificio su OSM e poi aggiungere la key Wikipedia (“E come devo disegnare il poligono?”). In ultimo, Pietro ha aggiunto le coordinate in Wikipedia anche al teatro Petruzzelli di Bari, che ne era orfano.

A fine hackathon, ne rimaneva soltanto uno, il teatro Mercadante di Cerignola, privo di coordinate in Wikipedia… ancora per poco. **Ormai le mani me le sono sporcate, e il lavoro l’ho ultimato**, seguendo il videotutorial “au contraire” prima citato, qualche giorno dopo, in autonomia: nella tabella della categoria Teatri della Puglia di WTOSM non ci sono più icone rosso-allarme. **E una grande, eccitata soddisfazione che mi ha prima sorpreso e poi interrogato: missione (davvero) conclusa? Piuttosto, comincia adesso!** Durante l’attività appena descritta ho conosciuto alcuni teatri pugliesi di cui ignoravo l’esistenza, e contemporaneamente ho notato l’assenza di altri, che invece frequento regolarmente, in OSM e in Wikipedia. Ora so che su OSM posso mapparli, su Wikipedia posso scriverci degli articoli, e poi posso collegare le informazioni. **E magari troverò anche qualcuno insieme a cui provare a raccontare questa nuova storia condivisa… insieme all’esperto di analisi open data, di cui ancora ho bisogno**.

## Estrarre dati da OSM
I due **ingegneri informatici**, più interessati allo **sfruttamento dei dati da OSM**, hanno preferito giocare con [overpass-turbo](http://overpass-turbo.eu/), un tool web sviluppato da [Martin Raifer](https://www.linkedin.com/pub/martin-raifer/22/957/474/en) che sfrutta le omonime [API](http://wiki.openstreetmap.org/wiki/Overpass_API) per l’estrazione di dati da OpenStreetMap, con query basate sui [numerosissimi tag](http://wiki.openstreetmap.org/wiki/Map_Features) che descrivono gli oggetti presenti nel repository OSM.

**Con overpass-turbo è possibile creare delle query in maniera molto semplice**, anche utilizzando il wizard che consente ad esempio di cercare i teatri presenti a Bari. Ulteriori informazioni su come costruire query le trovate [qui](http://wiki.openstreetmap.org/wiki/Overpass_API/Overpass_QL).

I dati estratti possono poi essere esportati in molti modi:
1. come geoJSON da scaricare in locale sul vostro computer;
2. come GPX per poterli usare nel vostro dispositivo GPS;
3. come dati grezzi;
4. usando l’interpreter delle API di Overpass;
5. caricandoli in un editor OSM come [JOSM](https://josm.openstreetmap.de/) o Level0;
6. o, cosa molto interessante, **salvandoli in geoJSON direttamente come gist**.