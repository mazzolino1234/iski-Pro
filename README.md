# iski-Pro

--------

Il problema che mi sono posto nel pensare di realizzare questo programma è stato la necessità di voler registrare i vari dati caratterizzanti ogni discesa sciistica in modo tale da poter confrontare tali dati nel tempo e visualizzare l'andamento nel corso degli anni. Inoltre un altro problema, risolvibile con la stessa applicazione, è stato il caso valanghe: negli ultimi anni sempre più sciatori vengono travolti e spesso non vengono trovati in tempo. Analizzando il problema è dunque nata l'idea di questa applicazione che non solo permette la registrazione discese ma anche un servizio di geolocalizzazione GPS.

Requisiti dell'applicazione:

1. Registrazione delle discese:
   * Requisiti funzionali:
     * Utente:
       * L'applicazione deve fornire un'interfaccia utente chiara e intuitiva che consenta agli utenti di avviare e interrompere la registrazione delle discese senza complicazioni.
       * Gli utenti devono poter facilmente accedere alle proprie registrazioni delle discese e visualizzare i dati associati a ciascuna di esse.
     * Sistema:
       * Gli utenti devono poter avviare e interromprere la registrazione delle loro discese in maniera facile e funzionale.
       * L'applicazione dovrà, per ogni discesa, registrare dati come la velocità massima, la velocità media, il tempo e la lunghezza della discesa.
       * I dati delle discese registrate devono essere conservati in modo sicuro e accessibili agli utenti per un periodo di tempo specificato.
     
   * Requisiti non funzionali:
     * Sistema:
       * La registrazione delle discese deve essere precisa e affidabile.
       * Deve essere possibile visualizzare i dati delle discese in un formato leggibile.
      
   * Requisiti di dominio:
     * L'applicazione deve rispettare le leggi e i regolamenti relativi alla raccolta e alla conservazione dei dati personali.
     *  L'applicazione deve essere compatibile con i dispositivi GPS per la registrazione dei dati delle discese.
     
2. Geolocalizzatore GPS per Valanghe:
   * Requisiti funzionali:
     * Utente:
       * Deve permettere agli utenti di poter diramare una segnalazione di soccorso con la loro posizione esatta ai contatti di emergenza più vicini.
       *  L'applicazione deve avere un'interfaccia utente semplice e intuitiva per consentire agli utenti di segnalare una valanga e attivare il geolocalizzatore GPS senza difficoltà.
     * Sistema:
       * L'applicazione deve essere in grado di rilevare automaticamente un evento di valanga e attivare il geolocalizzatore GPS in risposta a questo evento.
              
   * Requisiti non funzionali:
     * Sistema:
       * La geolocalizzazione GPS deve essere accurata per fornire informazioni precise sulla posizione dell'utente.
       * Il ritardo tra la valanga e l'invio delle informazione ai servizi di soccorso deve essere il più breve possibile
       * L'applicazione dovrebbe essere progettata per funzionare anche in condizioni di scarsa connessione o in caso di assenza di segnale.

   * Requisiti di dominio:
     * L'applicazione deve saper utilizzazre mezzi specifici al fine di comprendere cambiamenti molto rapidi di velocità per verificare la presenza di una valanga.
     * La privacy dell'utente deve essere protetta e crittografata.
     * Si devono impedire accessi indesiderati da parte di utenti esterni.

3. Confronto con Amici e Utenti Globali:
   * Requisiti funzionali:
     * Utente:
       * Gli utenti devono poter facilmente aggiungere amici attraverso la ricerca di altri utenti tramite il nome utente in app.
       * Gli utenti devono poter confrontare i loro risultati con quelli dei propri amici aggiunti in App.
       * Una leaderbord globale deve mostrare gli utenti con risultati migliori in modo di potersi confrontare.
     * Sistema:
       * Gli utenti devono poter confrontare i propri risultati con quelli dei propri amici.
       * L'applicazione deve fornire una leaderboard globale che mostri gli utenti con i migliori risultati sportivi a livello mondiale.

   * Requisiti non funzionali:
     * Sistema:
       * Il sistema deve essere in grado di gestire un numero crescente di utenti e dei loro specifici risultati

   * Requisiti di dominio:
     * L'app deve rispettare le normative relative la privacy per quanto riguarda la condivisione dei risultati e l'accesso a dati con altri utenti.
     * L'applicazione deve gestire la presenza di utenti provenienti da diverse parti del mondo, considerando le differenze linguistiche.
     * L'applicazione dovrebbe consentire agli utenti di condividere i propri risultati sportivi su piattaforme di social media 

3. Modalità duella:
   * Modalità che permette ad utenti vicini tra di loro di registrare la prossima discesa e confrontare i risultati ottenuti decretando un vincitore.1
   * L'app deve permettere agli utenti di avviare la modalità duella solo dopo aver verificato la vicinanza tra i dispositivi.

4. Registrazione e autenticazione:
   * Gli utenti devono avere la possibilità di registrarsi ed accedere all'applicazione.
   * Dare la possibilità di reset-password in caso di dimenticanza.
   * Possibilità di attivare l'autenticazione a due fattori (2FA) in modo da aggiungere una sicurezza in più all'utente.

5. Profilo:
   * L'utente deve poter visualizzare il proprio profilo e poter modificare i propri dati in base alle proprie esigenze.
   * Ogni utente deve avere un profilo personale che mostri le statistiche e discese in uno storico.

6. Gps e tracciamento:
   * L'applicazione deve poter avere accesso al sistema GPS del dispositivo per poter registrare i dati e aver la       
     possibilità di essere localizzati in caso di valanga.

7. Database:
   * Deve essere presente un database che permette di archiviare tutti gli utenti, le discese registrate e tutti gli utenti.

8. Condivisione:
    * L'app permette di condividere i risultati di una singola discesa

9. Mappa:
    * Tramite la mappa è possibile visualizzare le piste intorno a me con gli impianti sciistici attivi.
    * Visualizzazione satellite per osservare la conformazione del territorio, le montagne e le cime intorno a me.
      
10. Modalità premium:
    * L'applicazione, tramite pagamento mensile, permetterà di avere accesso a maggiori funzionalità.
    11.1 Sistema di tracciamento migliorato.
    * 11.2 Mappa discesa:
       * La modalità premium permette di avere una visualizzazione su mappa del percorso effettuato.
    * 11.3 Confronto automatico:
       * Tramite la modalità premium sarà possibile confrontare la discesa effettuata con una precedente in modo tale da avere un confronto reale.
    * 11.4 Allarme pericoli:
       * L'app appremium deve poter segnalare la possibilità di valanghe nella località sciistica selezionata e inviare una notifica all'utente.
    * 11.5 Modalità fuori pista:
        * Nella modalità premium deve essere presente la possibilità di scegliere la modalità fuori pista in modo da registrare le sciate su neve fresca.
    * 11.6 Report:
       * Nella versione premium sarà possibile creare e stampare (PDF) un report automatico dei record di sciate
    * 11.7 Modalità duella ampliata:
       * Tramite la versione premium dell'applicazione il numero di contendenti nella modalità duella (PUNTO 4) sarà ampliato da 2 a 4 persone massime.
     
11. Soddisfazione requisiti GDPR:
    * L'applicazione deve rispettare le norme europee, il regolamento generale sulla protezione dei dati (GDPR) -- non funzionale
      




