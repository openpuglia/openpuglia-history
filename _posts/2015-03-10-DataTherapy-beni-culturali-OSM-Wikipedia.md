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

**L’obiettivo è stato quello di aggiornare OSM con le informazioni eventualmente presenti in Wikipedia** per elementi presenti sul territorio pugliese, nell’ambito dei beni culturali. Qui sotto trovate la presentazione con il workflow che abbiamo seguito durante l’attività.

<iframe src="//www.slideshare.net/slideshow/embed_code/44958077" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/pietroblu/opendataday-2015-bari-odd15-i-luoghi-degli-opendata" title="OpenDataDay 2015 Bari #ODD15 - I luoghi degli #opendata" target="_blank">OpenDataDay 2015 Bari #ODD15 - I luoghi degli #opendata</a> </strong> from <strong><a href="//www.slideshare.net/pietroblu" target="_blank">Pietro Blu Giandonato</a></strong> </div>

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