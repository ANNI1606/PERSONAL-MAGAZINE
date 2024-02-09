**ABSTRACT**
L'applicazione "MyNews" funziona come un "meta-giornale". Si tratta di un aggregatore di notizie che crea un _personal magazine_ su misura dell'utente/lettore. "MyNews" permette agli utenti di organizzare le notizie in base ai propri interessi, con il fine di costruire un'esperienza personalizzata soddisfacente.

**BUSINESS LOGIC DI "MyNews"**

1. **Registrazione e Login degli Utenti**:

- Gli utenti possono registrarsi e creare un account personale;
- Possono accedere all'app tramite email/password.

2. **Profilo Utente**:

- Gli utenti possono creare e gestire il proprio profilo (username, foto profilo, interessi, ecc.).

3. **Selezione degli argomenti preferiti**:

- Gli utenti possono selezionare gli argomenti di loro interesse da una lista di categorie (sport, politica, tecnologia, cronaca, ecc.);
- Possono aggiornare le lore preferenze in qualsiasi momento.

4. **Filtraggio delle notizie**:

- L'app raccoglie notizie da fonti esterne tramite API di notizie o RSS feed;
- Le notizie sono categorizzate in base agli argomenti;
- Gli utenti possono applicare filtri avanzati per raffinare i risultati (data delle notizie, fonte, popolarità, localizzazione geografica, ecc.);
- Gli utenti possono anche cercare notizie utilizzando keywords o frasi.

5. **Memorizzazione dei dati**:

- Le preferenze di filtraggio vengono memorizzate in modo che non debbano essere reimpostate ogni volta che si accede all'app;
- I dati degli utenti(indirizzo email, password) sono anche questi memorizzati nel LocalStorage.

6. **Creazione e gestione di una Rivista**:

- L'utente può creare delle "riviste" con titolo e descrizione;
- L'utente può salvare le notizie, aggiungerle alla rivista dedicata e recuperarle in qualsiasi momento.

**USER INTERFACE DI "MyNews"**
Facilità d'uso e un design snello sono fondamntali per poter offrire all'utente un'esperienza gradevole.

1. **Schermata di Benvenuto/Registrazione/Login**:

- La prima schermata che gli utenti vedranno al caricamento della pagina con input per registrarsi o fare il login.

2. **Schermata Home**:

- Nella Home appare un "carosello" che mostra fino a nove riviste create dall'utente;
- Una barra di navigazione, in alto a destra, per accedere a diverse sezioni dell'applicazione, come la selezione degli argomenti preferiti, il profilo utente, le impostazione, ecc.

3. **Selezione degli argomenti preferiti**:

- Gli utenti possono visualizzare una lista di categorie da un menu ad hamburger e selezionare quelli di loro interesse;
- Possibilotà di cercare argomenti o esplorare categorie da una barra di ricerca.

4. **Visualizzazione delle notizie e Interazione**:

- Gli articoli sono visualizzati in una RecycleView che offre un'architettura più flessibile ed efficiente nella gestione di elenchi dinamici di dati;
- Ogni elemento dell'elenco delle notizie include il titolo, un'anteprima, immagine rappresentativa dell'articolo, data di pubblicazione, autore/fonte;
- Gli utenti possono fare clic sulla notizia per leggere l'articolo completo. Ogni articolo offre la possibilità all'utente, attraverso toggle specifici, di condividerlo sui social, di contrassegnarlo come preferito o di aggiungerlo a una rivista .

5.
