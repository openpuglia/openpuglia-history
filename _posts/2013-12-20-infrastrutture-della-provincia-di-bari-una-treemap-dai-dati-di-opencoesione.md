---
layout: post
title: 'Infrastrutture della Provincia di Bari: una treemap dai dati di OpenCoesione'
date: 2013-12-20
categories:
- OpenData
tags:
- #opencoesione
status: publish
type: post
published: true
author: Chiara Ciociola
email: chiara.ciociola@gmail.com
twitter:
linkedin:
---
<p>Duccio Schiavon, fondatore di <a href="http://www.stat-project.com/">Statistica@ning</a> e docente di Data Mining per Open Data in Action, ha elaborato questa treemap relativa ai finanziamenti al settore delle infrastrutture per la Provincia di Bari scaricati dal portale <a href="http://www.opencoesione.gov.it/">OpenCoesione</a>.<!--more--></p>
<p><iframe style="width: 100%; height: 600px;" src="http://datalab.stat-project.com/bariopencoesione/bariviz.htm" height="240" width="320" frameborder="0" scrolling="no"></iframe></p>
<p>Quali elaborazioni ci sono dietro a questo lavoro? Quali informazioni possiamo ricavarne? Ecco il post <a href="http://www.stat-project.com/group/graficievisualizzazioni/forum/topics/opencoesione-treemap-dei-dati-di-bari?xg_source=activity">via statistica@ning</a> di Duccio Schiavon dedicato alla ricerca effettuata.</p>

<!--more-->

<p><em><span style="font-size: 13px; line-height: 19px;">La visualizzazione in D3, che potete trovare nella sua versione interattiva in fondo al post, è una treemap realizzata nell'ambito del lavoro svolto per Open Data in Action!</span></em></p>
<p><em>Per la sua realizzazione sono stati considerati i soli finanziamenti stanziati per la provincia di Bari (15872), in particolare, dal database di OpenCoesione (file Puglia scaricato alla voce progetti da http://www.dps.tesoro.it/opencoesione/dati_attuazione.asp) sono stati considerati tre fonti d'informazione:</em><br />
<em> - FINANZ_TOTALE_PUBBLICO (Somma delle fonti di finanziamento pubbliche)</em><br />
<em> - CUP_DESCR_SETTORE (Settore infrastrutturale di un progetto secondo il CUP)</em><br />
<em> - CUP_CUP_DESCR_SOTTOSETTORE (Sottosettore infrastrutturale di un progetto secondo il CUP).</em></p>
<p><em>Queste informazioni sono state utilizzate per dimostrare quanto i progetti siano caratterizzati da uno "sbilanciamento" sia in termini di quantità media di denaro stanziato sia in termini di numero di finanziamenti concessi per finalità d'investimento.</em></p>
<p><em>Per "Finanziamento Medio" s'intende il valore medio di FINANZ_TOTALE_PUBBLICO calcolato per ognuna delle voci di CUP_DESCR_SOTTOSETTORE. In questo caso la dimensione di ogni riquadro è proporzionale all'ammontare dei soldi finanziati per il rispettivo sottosettore.</em></p>
<p><em> Per "Numero Progetti" s'intende il numero totale di progetti calcolato per ogni voce di CUP_DESCR_SOTTOSETTORE. In questo caso la dimensione di ogni riquadro è proporzionale al numero totale di progetti finanziati per il rispettivo sottosettore.</em><br />
<em> </em></p>
<p><em>Selezionando "Finanziamento Unico", ogni voce di CUP_DESCR_SOTTOSETTORE ha peso uguale all'interno della visualizzazione. In questo caso è come se ogni sottosettore avesse ricevuto in media lo stesso ammontare di denaro per il medesimo numero di progetti.</em></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
