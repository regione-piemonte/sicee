# Project Title
Sistema Informativo per la Prestazione Energetica degli Edifici (SIPEE ex SICEE)

# Project Description
Il SIPEE gestisce l'elenco regionale dei soggetti abilitati al rilascio dell'Attestato di Prestazione Energetica (APE), i dati inseriti negli APE e la raccolta degli attestati trasmessi dai professionisti.


# Getting Started
Il prodotto SICEE è composto dalle seguenti componenti:
- [SICEEWEB](https://github.com/regione-piemonte/sicee-siceeweb) (web application che consente il caricamento e la gestione degli APE, gestione dei dati del certificatore)
- [SICEEBO](https://github.com/regione-piemonte/sicee-siceebo) (web application che consente agli enti formatori la gestire delle informazioni inerenti i corsi di formazione ed alla PA la consultazione degli APE caricati a sistema)
- [SICEEFREE](https://github.com/regione-piemonte/sicee-siceefree) (web application ad accesso libero per Cittadini e Notai)
- [SICEEORCH](https://github.com/regione-piemonte/sicee-siceeorch) (orchestratore utilizzato dalle web application per indirizzare le chiamate verso i servizi SOA e per chiamare servizi esterni)
- [SICEESRV](https://github.com/regione-piemonte/sicee-siceesrv) (componente di esposizione servizi raggiungibile dall'orchestratore che permette la lettura dei dati su DB)
- [SICEEWS](https://github.com/regione-piemonte/sicee-siceews) (componente di esposizione servizi per ricevere l'RT e per servire siceebo)
- [SICEEGWACTA](https://github.com/regione-piemonte/sicee-siceegwacta) (componente per archiviazione e protocollazione APE su ACTA)
- [SICEEGWSIAPE](https://github.com/regione-piemonte/sicee-siceegwsiape) (componente di integrazione con i Web Service SIAPE (ENEA) per conferimento certificati APE)
- [SICEEDB](https://github.com/regione-piemonte/sicee-siceedb) (script per creazione e mantenimento DB proprietario)

# Prerequisites
I prerequisiti per l'installazione della componente sono i seguenti:
## Software
- [JDK 8](https://www.apache.org)
- [Apache 2.4](https://www.apache.org)
- [RedHat JBoss 6.4 GA](https://developers.redhat.com)  
- [Oracle Database 10.2](https://www.oracle.com/)  

- Tutte le librerie elencate nel BOM.csv devono essere accessibili per compilare il progetto. Le librerie sono pubblicate su http://repart.csi.it, ma per semplicità sono state incluse nella cartella lib/ di ogni singola componente, ad esclusione della libreria weblogic-client-3.0.0.jar che deve essere scaricata autonomamente dal sito di Oracle.

# Versioning
Per la gestione del codice sorgente viene utilizzata Git. Per la gestione del versioning si fa riferimento alla metodologia [Semantic Versioning](https://semver.org/) 

# Copyrights
(C) Copyright 2020 Regione Piemonte

# License
Questo software è distribuito con licenza EUPL-1.2
Consultare i file EUPL v1_2 IT-LICENSE.txt e EUPL v1_2 EN-LICENSE.txt per maggiorni dettagli.
