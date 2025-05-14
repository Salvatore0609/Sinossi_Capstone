Presentazione del progetto. Archiplanner è una web app innovativa progettata per gestire e archiviare le pratiche edilizie, rivolta a professionisti del settore come architetti, ingegneri e geometri. L'obiettivo dell'applicazione è semplificare l’organizzazione del lavoro, migliorare la gestione delle scadenze e dei documenti, e prevenire la perdita di informazioni cruciali legate al progetto.

Gli utenti possono caricare e salvare documenti come PDF (es. relazioni, autorizzazioni, certificazioni) e file DWG, relativi a tutte le fasi del progetto edilizio, comprese quelle burocratiche, tecniche ed economiche. L’app funge da archivio digitale sicuro e sempre accessibile, per tenere traccia di tutte le pratiche in corso.

L’architettura del sistema si basa su React per il frontend e Java (Spring Boot) per il backend, con PostgreSQL come database, garantendo scalabilità, affidabilità e possibilità di estensione ad altri territori comunali.

In mancanza di API pubbliche ufficiali per il Piano Urbanistico Comunale (PUC) e il Piano Regolatore Generale (PRG), è stato realizzato manualmente un dataset JSON basato sul PUC del Comune di Sassari. Esiste il servizio UrbisMap, che dispone di un database nazionale e offre API, ma l’accesso è subordinato a una richiesta ufficiale, che comporta un allungamento dei tempi a causa delle pratiche burocratiche. Per questa ragione, tale opzione è stata scartata.

Archiplanner non si limita alla gestione documentale, ma propone una guida strutturata che segue tutte le fasi progettuali, accompagnando i professionisti dalla fase iniziale (studio di fattibilità e analisi normativa) fino alla chiusura lavori e aggiornamenti catastali, includendo:

-Analisi preliminari

-Progettazione preliminare

-Progettazione definitiva e autorizzazioni

-Progettazione esecutiva e appalti

-direzioni lavori e cantiere

-Consegna finale al cliente (fine lavoro e aggiornamenti catastali)

Ogni fase è supportata da strumenti che aiutano l’utente a rispettare tempi e compiti, creando un flusso operativo ordinato e completo.

A completare il sistema, Archiplanner integra diversi servizi Google:

-Google Maps: per geolocalizzare e visualizzare i progetti in modo interattivo.

-Google Calendar: per gestire scadenze, incontri e promemoria direttamente dalla web app.

-Google Login (OAuth): per un accesso sicuro, rapido e senza necessità di creare nuove credenziali.

Infine, per quanto riguarda i dati catastali, la complessità di accesso al portale SISTER dell’Agenzia delle Entrate – che richiede autenticazione tramite SPID – ha reso difficile l'integrazione diretta. Tuttavia, Archiplanner offre comunque un collegamento rapido a questi dati attraverso link esterni o i-frame, garantendo la consultazione senza appesantire la struttura dell’applicazione.

In sintesi, Archiplanner è uno strumento completo per la gestione del progetto edilizio, dalla documentazione alla pianificazione, pensato per ottimizzare i processi quotidiani dei professionisti del settore.